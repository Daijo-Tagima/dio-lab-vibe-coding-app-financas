# 💸 App de Finanças Pessoais do Daijo com Vibe Coding


## PRD Refinado no ChatGpt

``` Markdown

# PRD – Aplicativo de Organização de Finanças Pessoais Conversacional

## 1. Visão do Produto

Nome provisório: Agente Financeiro  
Categoria: Finanças pessoais com interface conversacional  

Proposta de Valor:
Ajudar pessoas iniciantes a organizar suas finanças por meio de conversas em linguagem natural, eliminando planilhas complexas e formulários manuais, com experiência simples, inclusiva e acessível para o maior número possível de usuários.

---

## 2. Problema

Muitas pessoas abandonam aplicativos de controle financeiro porque:

- Exigem entrada manual repetitiva
- Possuem interfaces complexas
- Não oferecem personalização
- Geram alto esforço cognitivo
- Não são acessíveis para diferentes perfis de usuários

Hipótese:
Se o usuário puder registrar informações financeiras por meio de conversa natural, com interface simples e universalmente acessível, a adesão e a retenção aumentarão.

---

## 3. Público-Alvo

Primário:
- Pessoas iniciantes em organização financeira
- Usuários com baixa familiaridade tecnológica
- Pessoas que desejam simplicidade e praticidade

Inclusão explícita:
- Usuários com deficiência visual (compatível com leitor de tela)
- Usuários com dificuldades motoras
- Pessoas com baixa escolaridade financeira
- Usuários idosos

---

## 4. Princípio Norteador: Design Universal

O produto deve seguir os princípios de Design Universal, garantindo que a solução possa ser utilizada com boa experiência pelo maior número possível de usuários, sem necessidade de adaptações posteriores.

Diretrizes obrigatórias:

- Linguagem simples e clara
- Interface intuitiva e sem sobrecarga visual
- Compatibilidade com leitores de tela
- Contraste adequado de cores (mínimo WCAG 2.1 nível AA)
- Navegação possível apenas por teclado
- Ícones sempre acompanhados de texto
- Feedback claro após cada ação
- Não depender exclusivamente de cores para transmitir informação
- Botões grandes e bem espaçados
- Possibilidade futura de entrada por voz

---

## 5. Objetivos do Produto

Objetivo Principal:
Simplificar o controle financeiro por meio de uma experiência conversacional acessível.

Objetivos Mensuráveis (MVP):

- 70% dos usuários conseguem registrar um gasto em menos de 10 segundos
- 50% retornam ao aplicativo na primeira semana
- Classificação automática com pelo menos 80% de acurácia percebida
- Pelo menos 80% dos usuários avaliam a interface como simples e clara

---

## 6. Funcionalidades-Chave (MVP)

### 6.1 Registro de Transações via Chat

O usuário poderá registrar gastos e receitas em linguagem natural.

Exemplo:
"Gastei 35 reais no mercado hoje"

O sistema deve extrair:
- Valor
- Categoria
- Data
- Tipo (despesa ou receita)

O sistema deve confirmar o registro antes de salvar.

---

### 6.2 Classificação Automática

Categorias iniciais:

- Alimentação
- Transporte
- Moradia
- Lazer
- Saúde
- Educação
- Outros

A classificação poderá ser corrigida pelo usuário.

---

### 6.3 Metas Financeiras

Exemplo:
"Quero economizar 2 mil reais até dezembro"

O sistema deve:

- Registrar meta
- Calcular prazo
- Acompanhar progresso
- Informar projeções simples

---

### 6.4 Agente Financeiro (IA)

Funções:

- Alertas simples de comportamento financeiro
- Sugestões práticas de economia
- Comparações entre meses
- Recomendações educativas em linguagem acessível

Exemplo:
"Você gastou 30% a mais com alimentação este mês."
"Se reduzir 15% do lazer, pode atingir sua meta um mês antes."

---

### 6.5 Relatórios Simples

- Resumo mensal
- Total gasto
- Total recebido
- Saldo atual
- Gráfico por categoria
- Comparativo com mês anterior
- Versão textual alternativa ao gráfico

---

## 7. Requisitos Funcionais

- Processamento de linguagem natural
- Extração automática de entidades (valor, data, categoria)
- Armazenamento de transações
- Sistema de metas
- Dashboard com resumo financeiro
- Sistema de confirmação e edição de registros

---

## 8. Requisitos Não Funcionais

- Resposta da IA em até 3 segundos
- Interface simples e responsiva
- Segurança de dados financeiros
- Adequação à LGPD
- Compatibilidade com leitores de tela
- Conformidade com WCAG 2.1 nível AA

---

## 9. Telas do MVP

### 9.1 Tela Principal (Chat)

- Campo de mensagem
- Histórico de conversas
- Sugestões rápidas
- Confirmação clara após cada registro

---

### 9.2 Tela de Resumo

- Total gasto no mês
- Total recebido
- Saldo atual
- Gráfico por categoria
- Resumo textual alternativo

---

### 9.3 Tela de Metas

- Lista de metas
- Barra de progresso
- Previsão de conclusão

---

### 9.4 Tela de Perfil

- Nome
- Preferências
- Configuração de categorias
- Configurações de acessibilidade

---

## 10. Validação Inicial

Fase 1 – Teste com 5 a 10 usuários:

- Medir tempo para registrar gasto
- Avaliar clareza das respostas
- Avaliar percepção de simplicidade
- Verificar acessibilidade básica

Fase 2 – Métricas:

- Retenção em 7 dias
- Número médio de registros por usuário
- Taxa de correção manual de categorias
- Avaliação subjetiva de confiança no sistema

```
# Interações com o Lovable

> Crie um App de Finanças pessoais com base no seguinte PRD (Product Requirements Document):{PRD}

> Teste o chat enviando mensagens como 'Gastei 50 reais no mercado' e navegue entre as abas para verificar se tudo funciona.

# Resultado final no Lovable:

> https://talk-your-finance.lovable.app/

> <img width="1410" height="921" alt="image" src="https://github.com/user-attachments/assets/eda1ef5b-c7d7-4f2a-ba7a-f8840e318c3a" />

> <img width="1261" height="921" alt="image" src="https://github.com/user-attachments/assets/de67f836-22c3-484a-b78a-241e243274fc" />

> <img width="1357" height="923" alt="image" src="https://github.com/user-attachments/assets/835c72ed-6bde-4105-bfa3-0370c930d219" />

# Funcionalidades do App Organização Financeira
```
# Agente Financeiro

Aplicativo de organização de finanças pessoais baseado em conversa em linguagem natural.

O objetivo é simplificar o controle financeiro para iniciantes, eliminando planilhas e formulários complexos, por meio de uma experiência intuitiva, acessível e orientada por IA.

---

## Visão do Produto

O Agente Financeiro permite que o usuário registre gastos e receitas conversando naturalmente com o sistema.  
A aplicação interpreta a mensagem, classifica automaticamente a transação e organiza os dados para análise e acompanhamento de metas.

O produto foi projetado seguindo princípios de Design Universal, garantindo boa experiência para o maior número possível de usuários.

## Principais Funcionalidades

### 1. Interface Conversacional

- Registro de gastos via linguagem natural  
  Exemplo: "Gastei 35 reais no mercado hoje"
- Registro de receitas
- Sugestões rápidas de ação
- Histórico em formato de conversa

---

### 2. Resumo Financeiro Mensal

- Saldo atual
- Total de receitas
- Total de despesas
- Comparativo com mês anterior
- Destaque de variações por categoria
- Gráfico de gastos por categoria
- Lista de transações recentes

---

### 3. Metas Financeiras

- Criação de metas com prazo definido
- Acompanhamento de progresso
- Percentual de conclusão
- Visão consolidada do progresso geral

---

### 4. Perfil e Configurações

- Estatísticas de uso
- Categorias personalizadas
- Notificações
- Configurações de acessibilidade
- Configurações de privacidade

---

## Estrutura de Navegação

Menu inferior fixo com quatro áreas principais:

- Chat
- Resumo
- Metas
- Perfil

Navegação simples, intuitiva e com ícones acompanhados de texto.

---

## Princípios de Design

O aplicativo foi desenvolvido com base em:

- Simplicidade
- Linguagem clara
- Baixo esforço cognitivo
- Acessibilidade (WCAG 2.1 nível AA)
- Compatibilidade com leitores de tela
- Não dependência exclusiva de cores para transmitir informação

---

## Objetivo do MVP

- Permitir registro de transações em menos de 10 segundos
- Automatizar a classificação de gastos
- Oferecer visão clara da situação financeira mensal
- Auxiliar na criação e acompanhamento de metas

---

## Próximos Passos

- Feedback inteligente do Agente Financeiro
- Edição rápida de transações pelo chat
- Entrada por voz
- Alertas automáticos de comportamento financeiro
- Evolução para integração com Open Finance

---

## Tecnologias e Conceitos

- Interface conversacional com IA
- Extração de entidades em linguagem natural
- Classificação automática de categorias
- Experiência centrada no usuário
- Design Universal
```

## Reflexão

### O que funcionou bem?
O refinamento do PRD previamente feito pelo ChatGpt ajudou muito, pois usei apenas duas interações no Lovable.

### O que não funcionou bem?
Esperava poder interagir mais com o Lovable gratuitamente, pois assim poderia refinar muito mais. Mas já foi de grande valia no aprendizado em Vibe Coding.

### O que aprendeu sobre conversar com IAs?
Aprendir que é basicamente como conversar com uma pessoa, quanto mais detalher e clareza eu der, mais respostas elaboradas e estruturadas receberei e a interação será cada vez mais eficaz.

