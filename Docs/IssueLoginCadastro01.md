
📌 Issue 01 - Tela LoginCadastro.js

## Mensagens no login

### 🧩 Contexto

Mensagem de conclusão de login em vermelho e mensagem de erro seguindo outro componente.

🔍 Passos para reproduzir 

Mensagem em vermelho:

Digite um e-mail já cadastrado com as credenciais válidas, 
após isto irá aparecer a mensagem porém em vermelho.

Mensagem seguindo componente de cadastro:

Após a conclusão de alguma ação, seja logar ou não preencher todos os campos no login,
a mensagem aparece no componente de cadastro. 

### ✅ Resultado esperado

A mensagem deveria estar em outra cor pois pode induzir o usuário a pensar que 
cometeu um erro.

A mensagem de erro/sucesso deveria apenas permanecer no componente de login. 

### 💡 Sugestão 

Mensagem em vermelho:

Criar outra const MensagemSucesso para estilização do texto em caso de sucesso, mandar
o MensagemSucesso para o hook de login. Colocar a MensagemSucesso em um p, do mesmo jeito que MensagemErro.

Mensagem duplicada em cadastro: 

Criar outra const para MensagemErro porém para cadastro, sendo assim, MensagemErroCadastro, passar esta MensagemErro para o hook de cadastro. Caso a mensagem de erro ocorra o mesmo erro de estar em vermelho, fazer os passos acima porém para MensagemSucessoCadastro.

### 🖼 Capturas de tela 



