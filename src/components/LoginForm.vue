<template>
    <div class="wrapper">
        <div class="logo">
            <img src="src/assets/maxvidro.svg" width="239" height="141">
        </div>
        <form action="#">
            <h1>Entrar</h1>
            <div class="input-box">
                <input type="text" placeholder="Nome de Usuário" required>
                <box-icon name="user" size="24px" color="#ffffff" class="lead" />
            </div>
            <div class="input-box">
                <input type="password" placeholder="Senha" required>
                <box-icon name="lock-alt" size="24px" color="#ffffff" class="lead" />
                <box-icon name="show" size="24px" color="#ffffff" class="trail" />
            </div>

            <div class="remember-forgot">
                <label class="remember">
                    <input type="checkbox" /> Lembrar de mim
                </label>
                <a href="#">Esqueci a Senha</a>
            </div>


                <button type="submit" class="btn">
                    <box-icon name="log-in" color="#04BEC8" class="lead" /> Login
                </button>
            
                
            <div class="register-link">
                <p>Não tem uma conta?<a href="#">Registre-se</a></p>
            </div>
        </form>
    </div>
</template>