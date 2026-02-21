# Casos de Teste - Tela de Cadastro

---

## CT-001 - Cadastro com e-mail e senha válidos

**Pré-condição:**
- Usuário não ter cadastro no sistema
- Ter acesso à internet
- Estar na tela de cadastro

**Descrição:**  
Validar cadastro com e-mail válido não cadastrado e senha em formato correto.

**Passos:**
1. Preencher e-mail válido e não cadastrado
2. Preencher senha válida
3. Clicar em "Cadastrar"

**Resultado Esperado:**  
Mensagem de sucesso e redirecionamento para tela principal.

**Resultado Obtido:**  
Mensagem exibida e redirecionamento correto.

**Status:** ✅ Aprovado

---

## CT-002 - E-mail já cadastrado e senha inválida

**Pré-condição:**
- Usuário já cadastrado
- Ter acesso à internet
- Estar na tela de cadastro

**Passos:**
1. Inserir e-mail já cadastrado
2. Inserir senha inválida (senha123)
3. Clicar em "Cadastrar"

**Resultado Esperado:**  
Mensagem informando e-mail já cadastrado e senha inválida.

**Resultado Obtido:**  
Mensagem informando erro apenas na senha.

**Status:** ✅ Aprovado

---

## CT-003 - E-mail já cadastrado e senha válida

**Status:** ❌ Reprovado  
(Sistema permitiu cadastro indevidamente)

---

## CT-005 - E-mail inválido e senha válida

**Status:** ❌ Reprovado  
(Sistema permitiu cadastro com e-mail inválido)

---

## CT-006 - Cadastro com Google

**Status:** ❌ Reprovado  
(Redirecionou para página de compras ao invés da principal)

---

## CT-007 - Cadastro com Facebook

**Status:** ✅ Aprovado

---

## CT-008 - Cadastro com Apple

**Status:** ✅ Aprovado

---

## CT-009 - Botão Acessar redireciona para login

**Status:** ✅ Aprovado

---

## CT-010 - Campos em branco

**Status:** ✅ Aprovado