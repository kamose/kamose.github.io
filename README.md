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
    display: flex;
    justify-content: space-between;
  }
  
  .column {
    width: 47%;
    margin-right: 20px;
    display: flex;
    flex-direction: column; /* Așezăm elementele pe coloană */
  }
  
  .paragraph-container {
    position: relative;
    display: flex; /* Așezăm butonul și textul pe aceeași linie */
    align-items: center; /* Aliniem vertical butonul și textul */
    margin-bottom: 20px;
  }
  
  .copy-button {
    margin-left: 10px; /* Adăugăm un spațiu mic între buton și text */
  }
</style>
</head>
<body>  
  <h1>Raspunsuri pentru fraieri</h1>  

  <div class="column">
    <div class="paragraph-container">
      <p id="paragraph1">Se anunta daca o sa fie ox</p> 
      <button class="copy-button" onclick="copyToClipboard('paragraph1')">Copy</button>
    </div>

    <div class="paragraph-container">
      <p id="paragraph2">Fa ticket pe discord.</p> 
      <button class="copy-button" onclick="copyToClipboard('paragraph2')">Copy</button>
    </div>

    <div class="paragraph-container">
      <p id="paragraph3">Cata decide daca baga sau nu barbut.</p> 
      <button class="copy-button" onclick="copyToClipboard('paragraph3')">Copy</button>
    </div>
        <div class="paragraph-container">
      <p id="paragraph4">Misiunea o iei de la magazinu general si ciclopii ii gasesti in mapa alaska </p>
      <button class="copy-button" onclick="copyToClipboard('paragraph4')">Copy</button>
    </div>
     <div class="paragraph-container">
      <p id="paragraph5">Elodia poate aparea in toate mapele in afara de map1/map2 si map2 campion/ map3 campion.</p> 
      <button class="copy-button" onclick="copyToClipboard('paragraph5')">Copy</button>
    </div>
      <div class="paragraph-container">
      <p id="paragraph11">Gasesti pe calendar langa mini mapa orele tuturor evenimentelor </p> 
      <button class="copy-button" onclick="copyToClipboard('paragraph11')">Copy</button>
    </div>
  </div>

  <div class="column">
    <div class="paragraph-container">
      <p id="paragraph6">https://forumalaska.ro/topic/41248-ghidcompletpvm//</p> 
      <button class="copy-button" onclick="copyToClipboard('paragraph6')">Copy</button>
    </div>

    <div class="paragraph-container">
      <p id="paragraph7">https://forumalaska.ro/topic/38132-ghidrun-uri//</p> 
      <button class="copy-button" onclick="copyToClipboard('paragraph7')">Copy</button>
    </div>

    <div class="paragraph-container">
      <p id="paragraph8">https://forumalaska.ro/topic/21989-ghidmonster-card//</p>
      <button class="copy-button" onclick="copyToClipboard('paragraph8')">Copy</button>
    </div>
     <div class="paragraph-container">
      <p id="paragraph9">https://forumalaska.ro/topic/35515-ghidevenimente-permanente/</p>
      <button class="copy-button" onclick="copyToClipboard('paragraph9')">Copy</button>
    </div>
    <div class="paragraph-container">
      <p id="paragraph10">https://forumalaska.ro/topic/40506-stagiu-campionevolutii-itememisiuni//</p>
      <button class="copy-button" onclick="copyToClipboard('paragraph10')">Copy</button>
    </div>
  </div>

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
