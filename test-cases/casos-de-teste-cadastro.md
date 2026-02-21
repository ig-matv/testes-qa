# Casos de Teste - Tela de Cadastro

---

## CT-001 - Cadastro com e-mail válido e senha válida

**Pré-condições:**
- Usuário não possuir cadastro no sistema
- Ter acesso à internet
- Estar na tela de cadastro

**Descrição:**
Validar cadastro com e-mail válido e ainda não cadastrado e senha em formato correto.

**Passos:**
1. Preencher com e-mail em formato válido e ainda não cadastrado
2. Preencher com senha em formato válido
3. Clicar no botão de cadastro

**Resultado Esperado:**
Mensagem informando que o cadastro foi realizado com sucesso e redirecionamento para a tela principal do site.

**Resultado Obtido:**
Mensagem informando que o cadastro foi realizado com sucesso e redirecionamento correto.

**Status:** ✅ Aprovado

---

## CT-002 - E-mail já cadastrado e senha inválida

**Pré-condições:**
- Usuário já cadastrado no sistema
- Ter acesso à internet
- Estar na tela de cadastro

**Descrição:**
Validar cadastro com e-mail já cadastrado e senha em formato inválido.

**Passos:**
1. Preencher com e-mail já cadastrado (ex: fulando@email.com)
2. Preencher com senha em formato inválido (senha123)
3. Clicar no botão de cadastro

**Resultado Esperado:**
Mensagem informando que o cadastro não foi realizado pois o e-mail já está cadastrado e a senha está em formato inválido.

**Resultado Obtido:**
Mensagem informando que o cadastro não foi realizado e senha está em formato inválido.

**Status:** ✅ Aprovado

---

## CT-003 - E-mail já cadastrado e senha válida

**Pré-condições:**
- Usuário já cadastrado no sistema
- Ter acesso à internet
- Estar na tela de cadastro

**Descrição:**
Validar cadastro com e-mail já cadastrado e senha válida.

**Passos:**
1. Preencher com e-mail já cadastrado
2. Preencher com senha válida (Senha@123)
3. Clicar no botão de cadastro

**Resultado Esperado:**
Mensagem informando que o cadastro não foi realizado pois o e-mail já está cadastrado.

**Resultado Obtido:**
Mensagem informando que o cadastro foi realizado com sucesso.

**Status:** ❌ Reprovado

---

## CT-004 - E-mail válido e senha inválida

**Pré-condições:**
- Usuário não possuir cadastro no sistema
- Ter acesso à internet
- Estar na tela de cadastro

**Descrição:**
Validar cadastro com e-mail válido e senha em formato inválido.

**Passos:**
1. Preencher com e-mail válido
2. Preencher com senha inválida (senha123)
3. Clicar no botão de cadastro

**Resultado Esperado:**
Mensagem informando que a senha está em formato inválido e precisa ser alterada.

**Resultado Obtido:**
Mensagem informando que a senha está em formato inválido.

**Status:** ✅ Aprovado

---

## CT-005 - E-mail inválido e senha válida

**Pré-condições:**
- Usuário não possuir cadastro no sistema
- Ter acesso à internet
- Estar na tela de cadastro

**Descrição:**
Validar cadastro com e-mail inválido e senha válida.

**Passos:**
1. Preencher com e-mail inválido
2. Preencher com senha válida (Senha@123)
3. Clicar no botão de cadastro

**Resultado Esperado:**
Mensagem informando que o e-mail está inválido e precisa ser alterado.

**Resultado Obtido:**
Cadastro realizado com sucesso.

**Status:** ❌ Reprovado

---

## CT-006 - Cadastro com Google

**Pré-condições:**
- Usuário possuir conta Google
- Não possuir cadastro no sistema
- Ter acesso à internet
- Estar na tela de cadastro

**Descrição:**
Validar se ao clicar no botão Google o usuário é redirecionado para autenticação.

**Passos:**
1. Clicar em "Continuar com Google"
2. Verificar redirecionamento para autenticação Google
3. Escolher conta ainda não cadastrada
4. Confirmar login

**Resultado Esperado:**
Usuário cadastrado com sucesso e redirecionado para a página principal.

**Resultado Obtido:**
Cadastro realizado com sucesso e redirecionado para página de compras.

**Status:** ❌ Reprovado

---

## CT-007 - Cadastro com Facebook

**Pré-condições:**
- Usuário possuir conta Facebook
- Não possuir cadastro no sistema
- Ter acesso à internet
- Estar na tela de cadastro

**Resultado Esperado:**
Usuário cadastrado com sucesso e redirecionado para página principal.

**Resultado Obtido:**
Cadastro realizado com sucesso e redirecionamento correto.

**Status:** ✅ Aprovado

---

## CT-008 - Cadastro com Apple

**Pré-condições:**
- Usuário possuir conta Apple
- Não possuir cadastro no sistema
- Ter acesso à internet
- Estar na tela de cadastro

**Resultado Esperado:**
Usuário cadastrado com sucesso e redirecionado para página principal.

**Resultado Obtido:**
Cadastro realizado com sucesso e redirecionamento correto.

**Status:** ✅ Aprovado

---

## CT-009 - Botão Acessar redireciona para Login

**Pré-condições:**
- Usuário já cadastrado
- Ter acesso à internet
- Estar na tela de cadastro

**Passos:**
1. Clicar no botão "Acessar"
2. Verificar redirecionamento para tela de login
3. Inserir dados válidos
4. Clicar em Login

**Resultado Esperado:**
Usuário redirecionado para página principal.

**Resultado Obtido:**
Redirecionamento correto.

**Status:** ✅ Aprovado

---

## CT-010 - Campos em branco

**Pré-condições:**
- Ter acesso à internet
- Estar na tela de cadastro

**Passos:**
1. Clicar no botão de cadastro sem preencher campos

**Resultado Esperado:**
Mensagem de erro informando que os campos não podem estar em branco.

**Resultado Obtido:**
Mensagem exibida corretamente.

**Status:** ✅ Aprovado