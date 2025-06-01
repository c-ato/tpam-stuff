<%*
tp.app.vault.getall
const titleStem = await tp.system.prompt("Please enter Title Stem ([Title Stem] note 3)")
const newTitle = titleStem  + " note";
await tp.file.create_new("",newTitle, true);
const uri = await tp.app.commands.executeCommandById("workspace:copy-url") + "%20";

const files = app.vault.getMarkdownFiles()
const PDFlink = (await tp.system.suggester((files) => files.basename, files)).basename;


const cont = `---
Note number: 1
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
${files}
`;
tp.file.rename(newTitle + " 1")
tp.app.commands.executeCommandById("automatic-tags:add-tags")
%>