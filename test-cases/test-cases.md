# Casos de Teste

## Sistema testado

SauceDemo

## Objetivo

Validar as principais funcionalidades da aplicação, verificando se o sistema apresenta o comportamento esperado durante a execução dos testes.

## Casos de Teste

### CT-001 — Login com credenciais válidas

**Pré-condição:** Usuário deve estar na página de login.

**Passos:**
1. Acessar a página de login.
2. Informar um usuário válido.
3. Informar uma senha válida.
4. Clicar no botão de login.

**Resultado esperado:**
O usuário deve ser direcionado para a página de produtos.

**Resultado obtido:**
O usuário foi direcionado para a página de produtos.

**Status:**
PASS

---

### CT-002 — Login com senha inválida

**Pré-condição:** Usuário deve estar na página de login.

**Passos:**
1. Acessar a página de login.
2. Informar um usuário válido.
3. Informar uma senha inválida.
4. Clicar no botão de login.

**Resultado esperado:**
O sistema deve impedir o acesso e apresentar uma mensagem informando que as credenciais são inválidas.

**Resultado obtido:**
O sistema impediu o login e exibiu a mensagem: "Username and password do not match any user in this service".

**Status:**
PASS
