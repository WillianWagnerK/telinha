# telinha
<html lang="en">

<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="loguin.css">
    <style type="text/css">
    .Login{
    color: rgb(255, 255, 255);
    }
</style>
</head>
<body>

<div id="Fundo">
    <img id="image" src="Logomarca-Unifimes.png" alt="some text" width=500 height=100>
	<div class="Login">
		<h1 class="ls-login-logo">Unifimes Teste</h1>
       
		<form role="form">
			<fieldset>
 
				<div class="Usuario">
					<label for="userLogin">Usuário</label>
					<input class="form-control ls-login-bg-user input-lg" id="userLogin" type="text" aria-label="Usuário" placeholder="Usuário">
				</div>
 
				<div class="Senha">
					<label for="userPassword">Senha</label>
					<input class="form-control ls-login-bg-password input-lg" id="userPassword" type="password" aria-label="Senha" placeholder="Senha">
				</div>
 
				<a href="#" class="ls-login-forgot">Esqueci minha senha</a>
 
				<input type="submit" value="Entrar" class="btn btn-primary btn-lg btn-block">
				<p class="txt-center ls-login-signup">Não possui um usuário na Unifimes Teste?
					<a href="#">Cadastre-se agora</a>
				</p>
 
			</fieldset>
		</form>
	</div>
</div>
</body>
</html>
