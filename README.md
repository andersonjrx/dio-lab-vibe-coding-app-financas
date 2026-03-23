# 💸 App de Organização de Finanças Pessoais com Vibe Coding

---

## 📄 Prompt Final (PRD)

```
PRD – Aplicativo de Organização de Finanças Pessoais

1. Contexto  
Criar um aplicativo de organização de finanças pessoais que funcione por meio de conversas em linguagem natural.  
A proposta é simplificar o controle financeiro, eliminando formulários complexos ou planilhas manuais, tornando o processo acessível e intuitivo.

2. Problema  
Muitos usuários abandonam aplicativos de finanças porque:  
- Exigem entradas manuais excessivas.  
- Oferecem pouca personalização.  
- Tornam o processo burocrático e pouco amigável.  

O aplicativo busca resolver isso com uma experiência conversacional e recomendações automáticas de economia.

3. Público-Alvo  
- Pessoas que desejam começar a organizar suas finanças de forma prática e sem complicação.  
- Principalmente iniciantes que não têm familiaridade com planilhas ou apps tradicionais.  
- Nota importante: o design deve ser universal, garantindo que o máximo de pessoas, com diferentes perfis e necessidades, possam usar o app com boa experiência.

4. Funcionalidades-Chave  
1. Registro de gastos via chat em linguagem natural.  
2. Classificação automática das transações (alimentação, transporte, lazer etc.).  
3. Definição e acompanhamento de metas financeiras (ex.: guardar R$200/mês).  
4. Criar, editar e excluir metas financeiras por meio de formulário acessível.  
5. Agente Financeiro com integração real de IA para fornecer dicas personalizadas de economia.  
6. Relatórios simples e visuais (gráficos e resumos adaptados ao perfil do usuário).  
7. Banco de dados iniciado com valores zerados para cada usuário, permitindo que insiram seus próprios dados financeiros.  
8. Tela de login para múltiplos usuários.  
9. Função de criar conta caso o usuário ainda não tenha cadastro.  
10. Design Universal: acessibilidade integrada (suporte a leitores de tela, contraste adequado, navegação simplificada).

5. Entregável da IA  
- Plano de MVP contendo:  
  - Principais telas (chat, metas, relatórios, login/criação de conta).  
  - Recursos necessários (NLP para chat, categorização automática, motor de recomendações, banco de dados multiusuário).  
  - Esboço de validação inicial (testes com usuários iniciantes e diversidade de perfis).  
- Linguagem acessível e educativa, em português.  
- Garantia de Design Universal como requisito central.
```

Interações com o Lovable: 

> Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

> O chat bot deve poder criar, editar e excluir metas na parte de metas

Resultado final no Lovable: https://chatfinanceiro.lovable.app/

---

## 📹 Vídeo da aplicação

https://github.com/user-attachments/assets/3511f156-d392-43a1-94f8-0411ac735aba

---

## 📝 Resumo do App
O **App de Finanças Pessoais** permite que o usuário organize seus gastos e metas financeiras de forma simples e natural, por meio de conversas em linguagem natural.  
Ele oferece:  
- Registro de gastos via chat.  
- Classificação automática de transações.  
- Criação, edição e exclusão de metas financeiras.  
- Relatórios visuais e personalizados.  
- Dicas de economia fornecidas por um agente financeiro com IA integrada.  
- Suporte a múltiplos usuários com login e criação de conta.  
- Design Universal para garantir acessibilidade e inclusão.

---

## 🤔 Reflexão sobre o Processo

**O que funcionou bem?**  
- As telas de login, metas e relatórios funcionaram corretamente.  
- O chat também funcionou bem.  
- A adição das funcionalidades de criar, editar e excluir metas foi implementada de forma satisfatória.  

**O que não funcionou como o esperado?**  
- Houve um erro ao tentar adicionar dinheiro em duas metas ao mesmo tempo, que não foi executado com exatidão.
- Também está com um problema em remover do saldo o valor que vai para a meta, o que afeta o cálculo correto do saldo disponível.    

**O que aprendi sobre conversar com IAs?**  
- Aprendi que conversar com IAs é como construir junto: você descreve suas intenções e ela ajuda a transformar em requisitos e funcionalidades.  
- O **PRD** (Product Requirements Document) é essencial para organizar e estruturar o que o produto precisa ter.  
- O conceito de **Vibe Coding** mostra que é possível programar por intenção, descrevendo a experiência desejada em vez de focar apenas na lógica técnica.  
- Juntos, PRD e Vibe Coding permitem alinhar ideias e transformar em código e design de forma prática e criativa.
