<%* 
// Making new stem and note chain

const titleStem = await tp.system.prompt("Choose a title stem ([Title Stem] note 3)")
await tp.file.create_new("",titleStem + " note",true)
await tp.app.commands.executeCommandById("workspace:copy-url");
const uri = await tp.system.clipboard() + "%20"

// Makes PDFlink

const Files = app.vault.getFiles(); 
const encodedFileName = encodeURIComponent(
	(await tp.system.suggester( 
		(file) => file.basename, Files )).path.replace(".md", "")); 
const vaultName = app.vault.getName();
const encodedVaultName = encodeURIComponent(vaultName);
const PDFlink = `obsidian://open?vault=${encodedVaultName}&file=${encodedFileName}`;
tp.file.rename((titleStem + " note 1"), true);
tp.app.commands.executeCommandById("automatic-tags:add-tags")
%>---
Note number: 1
PDF URI: <% PDFlink %>
Title Stem: <% titleStem %>
URI base: <% uri %>
---
<div style="display: flex; justify-content: center; gap: 10px;">
	<a 
	href="<%uri%>2" class="button">Next
	</a> 
	<a 
	href="<%PDFlink%>#page=1" class="button">Go to PDF beginning
	</a> 
</div>