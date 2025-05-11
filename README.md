
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Cadastre-se - Leka Calçados</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #000;
      color: #fff;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    header {
      background-color: #f26a21;
      padding: 20px 10px;
    }
    h1 {
      margin: 0;
      font-size: 26px;
    }
    .container {
      padding: 30px 20px;
    }
    form {
      background-color: #1a1a1a;
      max-width: 400px;
      margin: 0 auto;
      padding: 20px;
      border-radius: 10px;
    }
    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
      text-align: left;
    }
    .desc {
      font-size: 13px;
      text-align: left;
      color: #ccc;
      margin-bottom: 5px;
    }
    input, select {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: none;
      border-radius: 5px;
    }
    input[type="submit"] {
      background-color: #f26a21;
      color: white;
      font-weight: bold;
      cursor: pointer;
      margin-top: 20px;
    }
    .footer {
      margin-top: 30px;
      font-size: 14px;
      color: #ccc;
    }
  </style>
</head>
<body>

  <header>
    <h1>LEKA CALÇADOS E CONFECÇÕES</h1>
    <p>Fique por dentro das novidades e promoções exclusivas! Preencha rapidinho 😊</p>
  </header>

  <div class="container">
    <form action="https://formsubmit.co/lekacalcadoscg@gmail.com" method="POST">
      <input type="hidden" name="_captcha" value="false">
      <input type="hidden" name="_next" value="https://obrigado.netlify.app/">
      
      <label for="nome">Nome completo:</label>
      <div class="desc">Para que a gente possa te chamar pelo nome certo 🧡</div>
      <input type="text" id="nome" name="nome" required>

      <label for="whatsapp">WhatsApp:</label>
      <div class="desc">Enviamos promoções e novidades por aqui 📲</div>
      <input type="text" id="whatsapp" name="whatsapp" placeholder="(67) 99999-9999" required>

      <label for="nascimento">Data de nascimento:</label>
      <div class="desc">Clientes aniversariantes ganham descontos 🤑</div>
      <input type="text" id="nascimento" name="nascimento" placeholder="DD/MM/AAAA" required>

      <label for="sexo">Sexo:</label>
      <select id="sexo" name="sexo" required>
        <option value="">Selecione</option>
        <option value="Feminino">Feminino</option>
        <option value="Masculino">Masculino</option>
        <option value="Outro">Outro</option>
        <option value="Prefiro não dizer">Prefiro não dizer</option>
      </select>

      <label for="consentimento">Gostaria de receber nossas promoções via WhatsApp?</label>
      <select id="consentimento" name="consentimento" required>
        <option value="">Selecione</option>
        <option value="Sim">Sim</option>
        <option value="Não">Não</option>
      </select>

      <input type="submit" value="Cadastrar">
    </form>

    <div class="footer">
      Seus dados estão seguros com a gente! 🔒
    </div>
  </div>

</body>
</html>
