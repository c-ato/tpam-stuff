<%*
const files = app.vault.getMarkdownFiles()
const PDFlink = (await tp.system.suggester((files) => files.basename, files)).basename;
const cont = `PDF URI: ${PDFlink}
${files}
`;
tp.file.create_new(cont,"reeee" + " 1",true)
%>