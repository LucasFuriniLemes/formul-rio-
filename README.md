 1 Formulário 
<html>
<body>
 <form action="/pagina-processa-dados-do-form" method="post">
    <div>
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="usuario_nome" />
    </div>
    <div>
        <label for="email">E-mail:</label>
        <input type="email" id="email" name="usuario_email" />
    </div>
    <div>
        <label for="msg">Mensagem:</label>
        <textarea id="msg" name="usuario_msg"></textarea>
    </div>
    <div class="button">
        <button type="submit">Enviar sua mensagem</button>
    </div>
</form>
  </body>
</html>
