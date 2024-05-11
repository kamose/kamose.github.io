<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Raspunsuri pentru fraieri</title>
<style>
  body {
    background-image: url('https://images.pexels.com/photos/954739/pexels-photo-954739.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1');
  color: white;
  }
</style>
</head>
<body>  
  <h1>Raspunsuri pentru fraieri</h1>  

  <p id="paragraph1">Im sorry i cant help you</p> 
  <button onclick="copyToClipboard('paragraph1')">Copy</button>  

  <p id="paragraph2">did you make a ticket?.</p> 
  <button onclick="copyToClipboard('paragraph2')">Copy</button>  

  <p id="paragraph3">This is the third paragraph.</p> 
  <button onclick="copyToClipboard('paragraph3')">Copy</button>  

  <p id="paragraph4">This is the fourth paragraph.</p> 
  <button onclick="copyToClipboard('paragraph4')">Copy</button>  

  <p id="paragraph5">This is the fifth paragraph.</p> 
  <button onclick="copyToClipboard('paragraph5')">Copy</button>

  <p id="paragraph6">This is the sixth paragraph.</p>
  <button onclick="copyToClipboard('paragraph6')">Copy</button>

  <p id="paragraph7">This is the seventh paragraph.</p>
  <button onclick="copyToClipboard('paragraph7')">Copy</button>

  <script>
function copyToClipboard(elementId) {
  var copyText = document.getElementById(elementId);
  var textArea = document.createElement("textarea");
  textArea.value = copyText.textContent;
  document.body.appendChild(textArea);
  textArea.select();
  document.execCommand("copy");
  document.body.removeChild(textArea);
}
</script>
</body>
</html>
