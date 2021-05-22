# Angular-cadastro
<hello name="{{ name }}"></hello>
<p>
  Start formulario de segurança :)
</p>
<img src="https://www.dnkinfotelecom.com.br/wp-content/uploads/2019/06/atendimento.jpg">
<div class="container" >
    <a class="links" id="paracadastro"></a>
    <a class="links" id="paralogin"></a>
    
    <div class="content">      
      <!--FORMULÁRIO DE LOGIN-->
      <div id="login">
        <form method="post" action=""> 
          <h1>Login</h1> 
          <p> 
            <label for="email_login">Seu e-mail</label>
            <input id="email_login" name="email_login" required="required" type="text" placeholder="contato@htmlecsspro.com"/>
          </p>
          
          <p> 
            <label for="senha_login">Sua senha</label>
            <input id="senha_login" name="senha_login" required="required" type="password" placeholder="1234" /> 
          </p>
          
          
          <p> 
            <input type="checkbox" name="manterlogado" id="manterlogado" value="" /> 
            <label for="manterlogado">Manter-me logado</label>
          </p>
          
          <p> 
            <input type="submit" value="Logar" /> 
          </p>
          
          <p class="link">
            Ainda não tem conta?
            <a href="#paracadastro">Cadastre-se</a>
          </p>
        </form>
      </div>

      <!--FORMULÁRIO DE CADASTRO-->
      <div id="cadastro">
        <form method="post" action=""> 
          <h1>Cadastro</h1> 
          
          <p> 
            <label for="nome_cad">Seu nome</label>
            <input id="nome_cad" name="nome_cad" required="required" type="text" placeholder="Analista Matheus" />
          </p>
          
          <p> 
            <label for="nome_cad">Seu RG</label>
            <input id="nome_cad" name="nome_cad" required="required" type="text" placeholder="Analista Matheus" />
          </p>
          
          <p> 
            <label for="nome_cad">Seu CPF</label>
            <input id="nome_cad" name="nome_cad" required="required" type="text" placeholder="Analista Matheus" />
          </p>
          
          <p> 
            <label for="nome_cad">Seu Endereço</label>
            <input id="nome_cad" name="nome_cad" required="required" type="text" placeholder="Analista Matheus" />
          </p>
          <label for="nome_cad">Cidade</label>
            <input id="cidade_cad" name="cidade_cad" required="required" type="text" placeholder="Analista Matheus" />
          <p> 
            <label for="nome_cad">Seu Telefone</label>
            <input id="nome_cad" name="nome_cad" required="required" type="text" placeholder="Analista Matheus" />
          </p>
          <p> 
            <label for="email_cad">Seu e-mail</label>
            <input id="email_cad" name="email_cad" required="required" type="email" placeholder="contato@htmlecsspro.com"/> 
          </p>
          
          <p> 
            <label for="senha_cad">Sua senha</label>
            <input id="senha_cad" name="senha_cad" required="required" type="password" placeholder="1234"/>
          </p>
          <label for="codigo entrada_cad">Seu codigo de entrada</label>
            <input id="codigo de entrada_cad" name="codigo de entrada_cad" required="required" type="password" placeholder="digite aqui"/>
          <p> 
            <input type="submit" value="Cadastrar"/> 
            <input type="submit" value="Enviar"/> 
          </p>
          
          <p class="link">  
            Não é Cadastrado!
            <a href="#paralogin"> Faça Login </a>
            
          </p>
        </form>
      </div>
    </div>
  </div> 
 
