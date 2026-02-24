#  Estratégia de Teste – Cadastro

---

##  Escopo

- Cadastro com e-mail válido e senha válida  
- E-mail já cadastrado e senha inválida  
- E-mail já cadastrado e senha válida  
- E-mail válido e senha inválida  
- E-mail inválido e senha válida  
- Cadastro com Google / Facebook / Apple  
- Botão "Acessar" redireciona para Login  
- Campos em branco  

---

##  Tipos de Testes Aplicados

- Teste Funcional  
- Teste Exploratório  
- Validação de Mensagens de Erro  

---

## Priorização

O fluxo principal de cadastro, a validação de campos obrigatórios e o cadastro com dados válidos devem ser executados antes dos testes secundários.

---

#  Análise de Risco – Funcionalidade de Cadastro

| Funcionalidade | Probabilidade | Impacto | Nível de Risco | Prioridade |
|---------------|--------------|----------|----------------|------------|
| Cadastro com e-mail válido e senha válida | Alta | Alto | Alto | Alta |
| E-mail já cadastrado e senha inválida | Média | Médio | Médio | Média |
| E-mail já cadastrado e senha válida | Média | Médio | Médio | Média |
| E-mail válido e senha inválida | Média | Médio | Médio | Médio |
| E-mail inválido e senha válida | Média | Médio | Médio | Médio |
| Cadastro com Google | Média | Médio | Médio | Média |
| Cadastro com Facebook | Média | Médio | Médio | Média |
| Cadastro com Apple | Média | Médio | Médio | Média |
| Botão "Acessar" redireciona para Login | Alta | Médio | Médio/Alto | Alta |
| Campos em branco | Alta | Alto | Alto | Alto |
