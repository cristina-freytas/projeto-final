# Como uma vida saudável e hábitos saudáveis podem impactar no desempenho escolar?

**Autora:** Cristina Freitas  
**Professora de Banco de Dados**

---

## 🔒 Aviso de Privacidade e Utilização de Dados — LGPD

Este estudo utiliza dados anônimos coletados de estudantes com o objetivo de compreender como aspectos biopsicossociais influenciam o desempenho escolar. Todas as informações respeitam a Lei Geral de Proteção de Dados (LGPD) e são utilizadas exclusivamente para fins acadêmicos e educativos.

---

## 🎯 Objetivo

Investigar se e como hábitos saudáveis, aspectos psicológicos, sociais e biológicos se correlacionam com o desempenho escolar dos estudantes. Tivemos em nossa pesquisa 72 pessoas que responderam o questionário que foi feito via Google Forms respeitando a lesgislaçao da Lei de Acesso à Informação. A ideia era aferir quais variáveis impactavam positivamente para o desempenho escolar - variável "AG05". Separamos as questões em 4 grandes grupos:
- **Aspectos Gerais**
- **Aspectos Biológicos**
- **Aspectos Psicológicos**
- **Aspectos Sociais**

---

## 🧾 Descrição das Variáveis

### 🔹 Aspectos Gerais
- **AG01** – Curso do estudante  
  `1: Administração`, `2: Desenvolvimento de Sistemas`, `3: Marketing`, `4: Recursos Humanos`, `5: Segurança do Trabalho`

- **AG02** – Período de estudo  
  `1: Manhã`, `2: Tarde`, `3: Noite`

- **AG03** – Sexo biológico  
  `1: Feminino`, `2: Masculino`

- **AG04** – Identificação étnica  
  `0: Não responde`, `1: Asiático`, `2: Branco`, `3: Indígena`, `4: Pardo`, `5: Preto`

- **AG05** – Menção no último Integradão (variável-alvo)  
  `1: MB`, `2: B`, `3: R`, `4: I`, `5: N/A`

  > **Explicação:** Esta variável representa o desempenho final do(a) estudante na avaliação integrada da escola.  
  > - `MB` – **Muito Bom**: excelente desempenho acadêmico  
  > - `B` – **Bom**: desempenho satisfatório  
  > - `R` – **Regular**: desempenho mediano, com pontos de atenção  
  > - `I` – **Insuficiente**: desempenho abaixo do esperado  
  > - `N/A` – **Não tem Menção**: o(a) estudante não recebeu avaliação (ex.: ausência, matrícula recente)

---

### 🔹 Aspectos Biológicos
- **AB01** – Horas de sono por noite  
  `1: Até 5h`, `2: 7h`, `3: 8h`, `4: 9h`, `5: Mais de 10h`

- **AB02** – Refeições por dia  
  `1 a 5+: Uma até mais de cinco`

- **AB03** – Porções de frutas ou legumes/dia  
  `0 a 5+: Nenhuma até mais de cinco`

- **AB04** – Frequência semanal de fast food  
  `0 a 5+: Nenhuma até mais de cinco`

- **AB05** – Frequência semanal de refrigerantes  
  `0 a 5+: Nenhuma até mais de cinco`

- **AB06** – Frequência semanal de exercícios físicos  
  `0 a 5+: Nenhuma até mais de cinco`

- **AB07** – Condições de saúde pré-existentes  
  `0: Nenhuma`, `1: Sim, mas não afeta`, `2: Sim e afeta a rotina escolar`

- **AB08** – Hábitos prejudiciais à saúde  
  `0: Nenhum`, `1: Fumar`, `2: Álcool`, `3: Substâncias ilícitas`, `4: Mais de um`

---

### 🔹 Aspectos Psicológicos
- **AP01** – Tempo de uso de telas para lazer (diário)  
  `0 a 5+: Nenhum até mais de cinco horas`

- **AP02** – Organização para tarefas  
  `0: Nenhuma`, `1: Mental`, `2: Agenda`

- **AP03** – Estudo em casa (horas/dia)  
  `0 a 5+: Nenhuma até mais de cinco`

- **AP04** – Nível de motivação para estudar  
  `0: Nenhuma`, `1: Pouca`, `2: Muita`

- **AP05** – Equilíbrio vida escolar/pessoal  
  `0: Nenhum`, `1: Tem equilíbrio sem desafios`, `2 a 4: Tem equilíbrio e desafio maior em escola, relações ou lazer`

- **AP06** – Busca por ajuda em dificuldades  
  `0: Ninguém`, `1: Familiares`, `2: Amigos`, `3: Professores`, `4: Outros`

- **AP07** – Apoio à saúde mental oferecido pela escola  
  `0: Nenhum`, `1: Insuficiente`, `2: Suficiente`

---

### 🔹 Aspectos Sociais
- **AS01** – Supervisão em casa  
  `0: Sozinho`, `1: Parcialmente supervisionado`, `2: Totalmente supervisionado`

- **AS02** – Tempo com tarefas domésticas (horas/dia)  
  `0 a 5+: Nenhuma até mais de cinco`

- **AS03** – Com quem o estudante mora  
  `0: Sozinho`, `1: Pai e mãe`, `2: Com padrasto/madrasta`, `3: Só pai`, `4: Só mãe`, `5: Outros`

- **AS04** – Total de pessoas na casa  
  `1 a 5+: Uma até cinco ou mais`

- **AS05** – Renda familiar total  
  `1 a 5+: Um até cinco salários mínimos`

- **AS06** – Distância da escola  
  `1: Perto e vai a pé`, `2 a 5: 5km até +20km, com transporte`

- **AS07** – Apoio social e motivação  
  `1: Sem apoio, impacto negativo`, `2: Sem apoio, impacto positivo`, `3 a 5: Apoio da família, amigos ou escola com impacto positivo`

- **AS08** – Impacto financeiro no acesso a recursos  
  `1: Não afeta`, `2: Afeta`

---

## 📊 Etapas da Análise

1. **Importação e exploração dos dados**
2. **Limpeza e tratamento**
3. **Visualização de padrões**
4. **Modelagem preditiva do desempenho escolar (AG05)**
5. **Análise dos resultados**
6. **Conclusões e recomendações pedagógicas**

---

> **Nota:** Os dados devem ser interpretados com cuidado e ética, considerando o contexto dos estudantes e suas realidades diversas. A análise visa apoiar práticas educacionais mais humanizadas e eficazes.
