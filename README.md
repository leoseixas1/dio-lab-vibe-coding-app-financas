# 💸 App de Finanças Pessoais do Leonardo Seixas (FinChat) com Vibe Coding

PRD refinado no Copilot Chat (M365):

```markdown
# PRD Revisado: App de Organização de Finanças Pessoais Conversacional

## Contexto
Criar um aplicativo que permita organizar finanças pessoais por meio de conversas em linguagem natural.  
O objetivo é simplificar o controle financeiro, evitando formulários complexos e planilhas, tornando a experiência mais intuitiva e acessível.

## Problema
A maioria dos aplicativos de finanças exige inserção manual detalhada e oferece pouca personalização, o que desmotiva os usuários.  
Queremos resolver isso com uma experiência conversacional e recomendações automáticas que incentivem hábitos financeiros saudáveis.

## Público-Alvo
- Pessoas que desejam começar a organizar suas finanças de forma prática e sem complicações.
- Principalmente iniciantes que não têm familiaridade com ferramentas tradicionais.

## Princípio de Design
A solução deve seguir **Design Universal**, garantindo que o aplicativo seja acessível e proporcione uma boa experiência para o maior número possível de usuários, independentemente de idade, habilidades, limitações físicas ou cognitivas.

## Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural.
2. Classificação automática das transações.
3. Definição e acompanhamento de metas financeiras.
4. Dicas de economia fornecidas por um “Agente Financeiro” virtual.
5. Relatórios simples e personalizados para visualização clara.

## Entregável da IA
- Gerar um plano de MVP com:
  - Principais telas.
  - Recursos necessários.
  - Esboço de validação inicial.
- Linguagem acessível e tom educativo, em português.

## Conceito de Design Universal
Design Universal é uma abordagem que busca criar produtos, serviços e ambientes que possam ser utilizados pelo maior número possível de pessoas, sem necessidade de adaptação ou projeto especializado.  
Princípios:
1. Uso equitativo.
2. Flexibilidade no uso.
3. Uso simples e intuitivo.
4. Informação perceptível.
5. Tolerância ao erro.
6. Baixo esforço físico.
7. Dimensão e espaço apropriados.
```

Interações com o Lovable:

> Crie um app de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): {PRD}
> implemente autenticação segura (email e senha) e habilite Lovable Cloud


Resultado final no Lovable: https://financial-chat.lovable.app/auth

<img width="1919" height="907" alt="image" src="https://github.com/user-attachments/assets/0579b228-5e0f-4961-83bc-736b22644bc9" />

<img width="1919" height="908" alt="image" src="https://github.com/user-attachments/assets/95dbfc2a-8ad6-460d-9c28-d6d77826179f" />


# Plano de MVP: FinChat – Organização Financeira Conversacional

## 1. Objetivo do MVP
Validar a proposta de um aplicativo que organiza finanças pessoais por meio de conversas em linguagem natural, com interface simples, acessível e baseada em **Design Universal**.

---

## 2. Principais Telas

### **2.1 Dashboard Financeiro**
- Exibe:
  - Saldo atual.
  - Receitas do mês (+ variação).
  - Despesas do mês (+ variação).
- Componentes:
  - Lista de transações recentes com categorias.
  - Metas financeiras com barra de progresso.
- Requisitos de acessibilidade:
  - Contraste adequado.
  - Texto legível e escalável.
  - Layout responsivo.

### **2.2 Tela de Chat com Agente Financeiro**
- Funções:
  - Registrar gastos via linguagem natural.
  - Definir metas financeiras.
  - Solicitar dicas de economia.
- Requisitos:
  - Campo de entrada com suporte a comandos simples.
  - Mensagens claras e com feedback imediato.
  - Compatibilidade com leitores de tela.

### **2.3 Tela de Metas**
- Exibe:
  - Lista de metas criadas pelo usuário.
  - Progresso em porcentagem e valores acumulados.
- Permite:
  - Criar novas metas via chat ou interface.
  - Editar ou excluir metas.

---

## 3. Funcionalidades-Chave do MVP
1. Registro de transações via chat (entrada em linguagem natural).
2. Classificação automática das transações por categoria.
3. Definição e acompanhamento de metas financeiras.
4. Dicas de economia fornecidas pelo Agente Financeiro.
5. Relatórios simples no dashboard.

---

## 4. Fluxo Conversacional (Exemplo)
```
Usuário: "Gastei R$ 50 no supermercado hoje."
Agente: "Transação registrada: R$ 50 em Alimentação. Deseja definir um limite para essa categoria?"
Usuário: "Sim, R$ 500 por mês."
Agente: "Limite definido. Vou avisar quando você se aproximar do valor."
```

---

## 5. Validação Inicial
- **Critérios de sucesso**:
  - Usuário consegue registrar gastos sem esforço.
  - Usuário entende relatórios e metas sem ajuda externa.
  - Feedback positivo sobre experiência conversacional.
- **Testes rápidos**:
  - 5 a 10 usuários simulando uso real.
  - Coleta de feedback sobre clareza, acessibilidade e utilidade.

---

## 6. Princípios de Design Universal Aplicados
- Interface simples e intuitiva.
- Opções de personalização (tamanho de fonte, contraste).
- Compatibilidade com tecnologias assistivas.
- Navegação clara e tolerante a erros.


## Reflexão

### O que funcionou bem?
O refinamento do PRD previamente feito no Copilot ajudou muito, pois os créditos do Lovable acabaram em apenas 2 interações.

### O que não funcionou como esperado?
Esperava poder interagir mais vezes gratuitamente com o Lovable, mas as interações feitas já foram de grande valia para aprender mais sobre Vibe Coding.

### O que aprendeu sobre conversar com IAs?
Aprendi que é basicamente igual a conversar com uma pessoa, quanto mais detalhes e clareza você dá, melhor é a interação.
