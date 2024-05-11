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
    font-family: Arial, sans-serif;
    padding: 20px;
  }
  
  .paragraph-container {
    position: relative;
    margin-bottom: 20px;
  }
  
  .copy-button {
    position: absolute;
    top: 50%;
    right: 0;
    transform: translateY(-50%);
  }
</style>
</head>
<body>  
  <h1>Raspunsuri pentru fraieri</h1>  

  <div class="paragraph-container">
    <p id="paragraph1">Im sorry i cant help you</p> 
    <button class="copy-button" onclick="copyToClipboard('paragraph1')">Copy</button>
  </div>

  <div class="paragraph-container">
    <p id="paragraph2">did you make a ticket?.</p> 
    <button class="copy-button" onclick="copyToClipboard('paragraph2')">Copy</button>
  </div>

  <div class="paragraph-container">
    <p id="paragraph3">This is the third paragraph.</p> 
    <button class="copy-button" onclick="copyToClipboard('paragraph3')">Copy</button>
  </div>

  <!-- Adăugați alte paragrafe și butoane de copiere aici -->

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
