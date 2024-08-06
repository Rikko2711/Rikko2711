   const markdownText = document.getElementById('markdown-input').value;
   const htmlContent = marked(markdownText);
   document.getElementById('html-output').innerHTML = htmlContent;