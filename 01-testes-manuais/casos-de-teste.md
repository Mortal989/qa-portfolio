# Casos de Teste

## Projeto
Sistema Web de Compras

## Módulo: Login

### CT-001 — Login com credenciais válidas

**Objetivo:**
Verificar se o usuário consegue acessar o sistema utilizando credenciais válidas.

**Pré-condições:**
- Usuário cadastrado no sistema.
- Crendencias válidas.

**Passos:**
1. Acessar a página de login.
2. Informar o usuário `standard_user`.
3. Informar a senha válida.
4. Clicar no botão "Login".

**Resultado esperado:**
O sistema deve autenticar o usuário e direcioná-lo para a página de produtos.

**Resultado obtido:**
O usuário foi autenticado com sucesso e direcionado para a página de produtos.

**Status:**
APROVADO ✅
---

### CT-002 — Login com senha inválida

**Objetivo:**
Verificar se o sistema impede o acesso quando uma senha inválida é informada.

**Pré-condições:**
- Usuário cadastrado no sistema.
- Possuir um usuário válido.

**Passos:**
1. Acessar a página de login.
2. Informar o usuário `standard_user`.
3. Informar uma senha inválida.
4. Clicar no botão "Login".

**Resultado esperado:**
O sistema deve impedir o acesso e apresentar uma mensagem informando que as credenciais não são válidas.

**Resultado obtido:**
O sistema impediu o acesso e apresentou a mensagem: "Epic sadface: Username and password do not match any user in this service."

**Status:**
APROVADO ✅ 

---

### CT-003 — Login com campos vazios

**Objetivo:**
Verificar se o sistema impede o login quando os campos obrigatórios não são preenchidos.

**Pré-condições:**
- Estar na página de login.

**Passos:**
1. Acessar a página de login.
2. Não preencher o campo "Username".
3. Não preencher o campo "Password".
4. Clicar no botão "Login".

**Resultado esperado:**
O sistema deve impedir o login e informar que o campo "Username" é obrigatório.

**Resultado obtido:**
O sistema impediu o login e apresentou a mensagem: "Epic sadface: Username is required."

**Status:**
APROVADO ✅

