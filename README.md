# Test Plan – QA Portfolio (AcademyBugs / Find Bugs)

## 1. Introdução

Este plano de testes descreve a abordagem, o escopo, os recursos e o cronograma para a execução de testes no site **https://academybugs.com/find-bugs/**. O objetivo é identificar bugs propositalmente inseridos na aplicação, praticar técnicas de teste exploratório e registrar artefatos de teste conforme práticas recomendadas pelo CTFL (ISTQB Foundation Level).

Arquivos adicionais como Casos de teste, Execução de testes, report de Bugs encontram-se no WIKI
- https://github.com/Auxvip/Academy-Bugs/wiki

O uso deste site é **exclusivamente educacional para fins de estudo e portfólio de QA**.

---

## 2. Objetivo do Teste

- Explorar o site para localizar bugs propositais inseridos em diversas funcionalidades.
- Registrar evidências e relatórios de defeitos.  
- Demonstrar competência em teste exploratório, funcional e em documentação de artefatos de teste.  
- Produzir documentação de teste que pode ser incluída em um portfólio público.

---

## 3. Escopo de Teste

### 3.1 Itens em Escopo

- Navegação nas páginas de produtos. 
- Interações com botões (Add to Cart, Checkout, etc.).
- Validação visual, funcional e lógica de componentes.  
- Testes exploratórios para identificar bugs adicionais além dos bugs conhecidos.

### 3.2 Itens Fora de Escopo

- Testes de performance, segurança ou carga.  
- Testes de compatibilidade com múltiplos navegadores e dispositivos móveis.  
- Interação com APIs externas, a menos que claramente visível no UI.  
- Testes automatizados (opcional ser documentado em arquivo separado se realizados).

---

## 4. Estratégia de Teste

### 4.1 Abordagem

Testes exploratórios serão realizados para **descobrir bugs inseridos propositalmente** no fluxo de navegação, com ênfase em:

- Fluxos comuns de usuário (navegação por produtos, adicionar ao carrinho, checkout). 
- Validação de respostas de UI (mensagens, imagens, estados de botões).  
- Interações inesperadas ou comportamentos incorretos visíveis pela interface.

### 4.2 Tipos de Teste

- Testes funcionais manuais  
- Testes exploratórios  
- Testes de regressão simples (reexecutar após identificação de bugs)

---

## 5. Critérios de Entrada e Saída

### 5.1 Critérios de Entrada

- A página https://academybugs.com/find-bugs/ deve estar acessível.
- Plano de teste e casos de teste definidos.  
- Ferramentas de registro de defeitos prontas (ex.: documento Markdown ou planilha).

### 5.2 Critérios de Saída

- Todos os casos de teste executados.  
- Bugs identificados e documentados.  
- Evidências coletadas para todos os defeitos relevantes.

---

## 6. Ambiente de Teste

- Acesso a internet estável  
- Navegador moderno (por exemplo, Chrome ou Firefox)  
- URL de teste: https://academybugs.com/find-bugs/ 

---

## 7. Papéis e Responsabilidades

- **Tester:** execução dos testes exploratórios, identificação de bugs, documentação de resultados.  
- **Revisor (opcional):** revisão de artefatos de teste antes da publicação.

---

## 8. Riscos e Mitigações

| Risco | Impacto | Mitigação |
|-------|---------|-----------|
| Site temporariamente indisponível | Médio | Registrar indisponibilidade e retomar mais tarde |
| Bugs conhecidos não serem reunidos | Baixo | Reexplorar cuidadosamente todas as áreas |
| Ambiguidade em passos de reprodução | Médio | Documentar passos claros e capturas de tela |
| Indisponibilidade total de função | Critico | Documentar e informar imediatamente |
| Textos incorreto | Alto | Documentar e informar aos envolvidos |
| Direcionamento incorreto de pagina | Critico | Documentar e informar imediatamente |
---

## 9. Itens de Entrega
- https://github.com/Auxvip/Academy-Bugs/wiki
 
- TEST_CASES.md  
- EXECUTION_RESULTS.md  
- BUG_REPORTS.md  

---

## 10. Padronização de escrita dos casos de teste

### TC-001 – Título do Caso de Teste

**Objetivo:**  
Descrever de forma clara o que será validado.

**Pré-condições:**  
- Sistema disponível  
- Usuário na página inicial  
- Navegador aberto

**Dados de Teste:**  
- Usuário: user_test  
- Senha: password123  

**Passos:**
1. Acessar a URL do sistema
2. Clicar no botão "Login"
3. Informar usuário válido
4. Informar senha válida
5. Clicar em "Entrar"

**Resultado Esperado:**  
- Usuário autenticado com sucesso  
- Redirecionamento para a página inicial  
- Mensagem de sucesso exibida

**Resultado Obtido:**  
(A preencher após execução)

**Status:**  
- Não Executado / Aprovado / Reprovado / Bloqueado

**Observações:**  
- Campo para comentários adicionais ou evidências

---

## 11. Aprovação

Este plano de testes é aprovado para uso educacional e pode ser utilizado como referência em portfólios públicos.

**Autor:** Guilherme Salgado da Silva 
**Data:**  
**Versão:** 1.0
