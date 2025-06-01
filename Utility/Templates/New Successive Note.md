<%* 
const pageNum = await tp.system.prompt("Please enter the current page")
const noteNum = parseInt(tp.frontmatter["Note number"]) + 1;
const PDFlink = tp.frontmatter["PDF URI"];
const newTitle = tp.frontmatter["Title Stem"]  + " note " + noteNum;
const uri = tp.frontmatter["URI base"];
const cont = `---
Note number: ${noteNum}
PDF URI: ${PDFlink}
Title Stem: ${tp.frontmatter["Title Stem"]}
URI base: ${uri}
---
<div style="display: flex; justify-content: center; gap: 10px;">
	<a 
	href="${uri + parseInt(noteNum + 1)}" class="button">Next
	</a> 
	<a 
	href="${PDFlink + "#page=" + pageNum}" class="button">Go to PDF Page ${pageNum}
	</a> 
	<a 
	href="${uri + parseInt(noteNum - 1)}" class="button">Previous
	</a> 
</div>
`;
await tp.file.create_new(cont,newTitle, true);
tp.app.commands.executeCommandById("automatic-tags:add-tags")
%>