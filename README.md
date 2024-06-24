<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Raspunsuri pentru fraieri</title>
<style>
  body {
    background-image: url('https://i.imgur.com/OxnnEdh.jpg'); /* Adaugăm imaginea de fundal */
    background-size: cover; /* Asigurăm că imaginea ocupă întregul spațiu disponibil */
    background-position: center; /* Centrăm imaginea pe ecran */
    color: white;
    font-family: Arial, sans-serif;
    padding: 20px;
    display: flex;
    justify-content: space-between;
  }
  
  .column {
    width: 30%; /* Ajustăm lățimea pentru a include o a treia coloană */
    margin-right: 20px;
    display: flex;
    flex-direction: column; /* Așezăm elementele pe coloană */
    background-color: rgba(0, 0, 0, 0.5); /* Adăugăm un fundal semitransparent pentru a evidenția textul */
    padding: 20px;
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
  
  p {
    margin: 0; /* Eliminăm marginile pentru paragrafe pentru a îmbunătăți aspectul */
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
      <p id="paragraph5">Elodia poate aparea in toate mapele in afara de map1/map2 si map2 campion/ map3 campion si v4.</p> 
      <button class="copy-button" onclick="copyToClipboard('paragraph5')">Copy</button>
    </div>
    
    <div class="paragraph-container">
      <p id="paragraph11">Gasesti pe calendar langa mini mapa un C cu orele tuturor evenimentelor </p> 
      <button class="copy-button" onclick="copyToClipboard('paragraph11')">Copy</button>
    </div>
  </div>

  <div class="column">
    <div class="paragraph-container">
      <p id="paragraph6"><a href="https://forumalaska.ro/topic/41248-ghidcompletpvm//" target="_blank">Ghid complet PvM</a></p> 
      <button class="copy-button" onclick="copyToClipboard('paragraph6')">Copy</button>
    </div>

    <div class="paragraph-container">
      <p id="paragraph7"><a href="https://forumalaska.ro/topic/38132-ghidrun-uri//" target="_blank">Ghid run-uri</a></p> 
      <button class="copy-button" onclick="copyToClipboard('paragraph7')">Copy</button>
    </div>

    <div class="paragraph-container">
      <p id="paragraph8"><a href="https://forumalaska.ro/topic/21989-ghidmonster-card//" target="_blank">Ghid monster card</a></p>
      <button class="copy-button" onclick="copyToClipboard('paragraph8')">Copy</button>
    </div>
    
    <div class="paragraph-container">
      <p id="paragraph9"><a href="https://forumalaska.ro/topic/35515-ghidevenimente-permanente/" target="_blank">Ghid evenimente permanente</a></p>
      <button class="copy-button" onclick="copyToClipboard('paragraph9')">Copy</button>
    </div>
    
    <div class="paragraph-container">
      <p id="paragraph10"><a href="https://forumalaska.ro/topic/40506-stagiu-campionevolutii-itememisiuni//" target="_blank">Stagiu campion, evoluții iteme, misiuni</a></p>
      <button class="copy-button" onclick="copyToClipboard('paragraph10')">Copy</button>
    </div>
    
    <div class="paragraph-container">
      <p id="paragraph12"><a href="https://forumalaska.ro/topic/38517-prezentare-skinuricostume//" target="_blank">Prezentare skinuri și costume</a></p>
      <button class="copy-button" onclick="copyToClipboard('paragraph12')">Copy</button>
    </div>
    
    <div class="paragraph-container">
      <p id="paragraph13"><a href="https://forumalaska.ro/topic/42267-ghidpescuit/" target="_blank">Ghid pescuit</a></p>
      <button class="copy-button" onclick="copyToClipboard('paragraph13')">Copy</button>
    </div>
    
    <div class="paragraph-container">
      <p id="paragraph14"><a href="https://forumalaska.ro/topic/40164-mount-uri-pet-uri-existente-pe-server/" target="_blank">Mount-uri și pet-uri existente pe server</a></p>
      <button class="copy-button" onclick="copyToClipboard('paragraph14')">Copy</button>
    </div>
  </div>

  <div class="column">
    <div class="paragraph-container">
      <p id="paragraph15"><a href="https://forumalaska.ro/topic/38477-ghidcurele/" target="_blank">Ghid curele</a></p>
      <button class="copy-button" onclick="copyToClipboard('paragraph15')">Copy</button>
    </div>
    
    <div class="paragraph-container">
      <p id="paragraph16"><a href="https://forumalaska.ro/topic/41621-prezentarea-skinurilor-de-pet/" target="_blank">Prezentarea skinurilor de pet</a></p>
      <button class="copy-button" onclick="copyToClipboard('paragraph16')">Copy</button>
    </div>
    
    <div class="paragraph-container">
      <p id="paragraph17"><a href="https://forumalaska.ro/topic/41246-ghidpersonalizare/" target="_blank">Ghid personalizare</a></p>
      <button class="copy-button" onclick="copyToClipboard('paragraph17')">Copy</button>
    </div>
    
    <div class="paragraph-container">
      <p id="paragraph18"><a href="https://forumalaska.ro/topic/42635-ghid-battlepass-uri-existente-pe-server/" target="_blank">Ghid battlepass-uri existente pe server</a></p>
      <button class="copy-button" onclick="copyToClipboard('paragraph18')">Copy</button>
    </div>
  </div>

  <script>
    function copyToClipboard(elementId) {
      var element = document.getElementById(elementId);
      var copyText = element.querySelector('a') ? element.querySelector('a').href : element.textContent;
      var textArea = document.createElement("textarea");
      textArea.value = copyText;
      document.body.appendChild(textArea);
      textArea.select();
      document.execCommand("copy");
      document.body.removeChild(textArea);
    }
  </script>
</body>
</html>
