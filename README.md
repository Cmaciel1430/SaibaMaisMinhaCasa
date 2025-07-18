[Upload<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Minha Casa Minha Vida</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <h1>Conquiste seu Imóvel!</h1>
  <p>Aproveite condições especiais do Minha Casa Minha Vida.</p>

  <input type="text" id="nome" placeholder="Seu nome" />
  <br />
  <input type="text" id="renda" placeholder="Sua renda" />
  <br />
  <button onclick="enviarWhatsApp()">Fale conosco pelo WhatsApp</button>

  <script>
    function enviarWhatsApp() {
      const nome = document.getElementById("nome").value.trim();
      const renda = document.getElementById("renda").value.trim();
      const numero = "5511953282008";

      if (!nome || !renda) {
        alert("Por favor, preencha seu nome e sua renda.");
        return;
     javascript
     function enviarWhatsApp() {
     const nome = document.getElementById("nome").value.trim();
     const renda = document.getElementById("renda").value.trim();
     const numero = "5511953282008"; // Substitua pelo seu número

     if (!nome || !renda) {
alert("Por favor, preencha todos os campos.");
       return;
     } }

      const texto = Olá, me chamo nome e minha renda é R renda. Gostaria de saber mais sobre o programa.;
      const url = https://wa.me/{numero}?text=${encodeURIComponent(texto)};

      window.open(url, "_blank");
    [Uplocss
body {
  background-color: #f9f9f9;
  font-family: Arial, sans-serif;
 color: #333;
  text-align: center;
  padding: 30px;
}

h1 {
  color: #004aad;
  margin-bottom: 10px;
}

p {
  font-size: 16px;
  color: #666;
  margin-bottom: 20px;
}

input {
  padding: 10px;
  margin: 10px 0;
  width: 80%;
  max-width: 300px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  padding: 10px 20px;
  background-color: #004aad;
  color: white;
  border: none;
  border-radius: 5px;
  font-weight: bold;
  cursor: pointer;
}

button:hover {
  background-color: #003280;
}ading style.css…]()

	
	
	}
</body>
</html>
ing index.html…]()
