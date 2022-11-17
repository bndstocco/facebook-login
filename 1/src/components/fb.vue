<template>
  <nav class="navbar navbar-expand-lg">
    <div class="container space-between">
      <a class="navbar-brand" href="#">Facebook</a>

      <form
        action="/pagina-processa-dados-do-form"
        method="post"
        class="formulario"
      >
        <div>
          <label for="nome">E-mail ou telefone</label>
          <input type="text" id="nome" />
        </div>
        <div>
          <label>
            <label for="senha">Senha</label>

            <input type="senha" id="senha" />
            Esqueceu a senha?
          </label>
        </div>
        <button type="button" class="button">Entrar</button>
      </form>
    </div>
  </nav>
  <div class="container">
    <div class="row">
      <div class="col-lg">
        <br />
        <h4>
          O Facebook ajuda você a se conectar e compartilhar com as pessoas que
          fazem parte da sua vida.
        </h4>
        <img
          src="../img/Sem título.png"
          class="mw-100"
          alt="..."
          style="width: 500px; height: 230px"
        />
      </div>
      <div class="col-lg">
        <h1>Abra uma conta</h1>
        <h3>É gratuito e sempre será</h3>
        <label>
          <input
            type="senha"
            id="senha"
            class="formulario2"
            placeholder="Nome"
          />
          <input
            type="senha"
            id="senha"
            class="formulario2"
            placeholder="Sobrenome"
          />
          <input type="senha" id="senha" placeholder="Celular ou e-mail" />
          <input type="senha" id="senha" placeholder="Nova senha" />
          <br />
          Data de nascimento
        </label>

        <div class="teste">
          <input id="date" type="date" />
          <p>Por que preciso informar minha data de nascimento?</p>
        </div>
        <form>
          <div class="genero">
            <input type="radio" id="css" name="fav_language" value="CSS" />
            <label for="html">Masculino</label><br />
            <input type="radio" id="css" name="fav_language" value="CSS" />
            <label for="css">Feminino</label>
          </div>
        </form>
        <br />
        <p>
          Ao clicar em cadastre-se, você concorda com nossos Termos, Política de
          Privacidade e Política de Cookies. Você poderá receber notificações
          por SMS e cancelar isso quando quiser.
        </p>

        <button class="btn-primary" type="button">Inscreva-se</button>
        <p><span>Criar uma página</span> para celebridade, banda ou empresa.</p>
      </div>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.min.css";
import "bootstrap/dist/js/bootstrap.min.js";

export default {
  name: "fb",
};
</script>

<style>
.navbar-expand-lg {
  background-color: #1d3e84;
}

.formulario {
  display: flex;
  font-size: small;
  gap: 15px;
}

input {
  display: block;
}

button {
  background-color: #1d3e84;
  height: 50px;
  margin-top: 20px;
}

body {
  background-color: rgb(119, 118, 118);
  font-family: sans-serif;
}

.col-lg {
  margin-top: 50px;
}

.teste {
  display: flex;
}

.genero {
  display: flex;
  gap: 5px;
}

.btn-primary {
  background-color: rgb(13, 92, 13);
  border-radius: 10px;
}

.navbar-brand {
  font-style: Klavika Bold;
}

h4 {
  color: #1d3e84;
}

h1 {
  font-weight: bold;
}
</style>
