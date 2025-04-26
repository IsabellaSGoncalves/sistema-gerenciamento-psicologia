📌 Issue 03 - Tela LoginCadastro.js

## Função lembre de mim não completa

### 🧩 Contexto

Mesmo que você clique em lembre de mim o email não é demonstrado na tela após o login.

### 🔍 Passos para reproduzir 

Ao clicar em lembre de mim após deslogar não é demonstrado sinal que o sistema tem o email salvo.

### ✅ Resultado esperado

Email seja demonstrado após o deslogin.

### 💡 Sugestão 

Colocar 

placeholder={email ? 'E-mail' : localStorage.getItem('emailSalvo') || 'E-mail'}

Na área de input do email (durante o form de login), assim mesmo que o login seja feito ele será demonstrado na área de placeholder. 
Colocar em value também funciona porém não é possível digitar algo além do emailSalvo.




