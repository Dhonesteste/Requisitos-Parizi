# Relatório de Elicitação de Requisitos: Sistema Retenção-Grad

## 1. Introdução

Este relatório apresenta a análise realizada a partir da atividade prática de elicitação de requisitos para o sistema **Retenção-Grad**, uma plataforma voltada ao acompanhamento acadêmico e prevenção da evasão estudantil no **Instituto Federal Farroupilha (IFFar)**.

A pesquisa foi desenvolvida com base em entrevistas com stakeholders e questionários aplicados aos estudantes, buscando identificar fatores relacionados à permanência acadêmica e possíveis estratégias institucionais de intervenção.

O objetivo principal da atividade foi compreender os fatores que influenciam a evasão estudantil e levantar requisitos funcionais e não funcionais para um sistema capaz de auxiliar a instituição na identificação precoce de estudantes em situação de risco.

---

# 2. Stakeholder Escolhido

O stakeholder escolhido foi o **Dr. Professor Rafael B. Parizi**, coordenador do curso de Bacharelado em Sistemas de Informação do Instituto Federal Farroupilha – Campus São Borja.

## 2.1 Entrevista com Stakeholder

### Pergunta 1

#### Como funciona atualmente o acompanhamento de possíveis casos de evasão estudantil?

**Resposta:**
Atualmente o acompanhamento é dificultado pela ausência de sistemas integrados. As informações ficam distribuídas em planilhas e relatórios separados no SIG, tornando o monitoramento lento e pouco eficiente.

---

### Pergunta 2

#### Quais sinais indicam que um estudante está em risco de evasão?

**Resposta:**
Os principais sinais identificados são faltas consecutivas, ausência em avaliações e reprovações em disciplinas básicas.

---

### Pergunta 3

#### Quais informações acadêmicas seriam importantes para um sistema de monitoramento?

**Resposta:**
Frequência, notas, diários de classe, reprovações e participação em avaliações foram apontados como dados fundamentais.

---

### Pergunta 4

#### Como poderiam funcionar os alertas automáticos?

**Resposta:**
Os professores poderiam enviar os diários de classe quinzenalmente para que o sistema identificasse automaticamente estudantes com frequência irregular.

---

### Pergunta 5

#### Existem fatores externos que influenciam a evasão?

**Resposta:**
Foi destacado que estudantes que trabalham ou moram fora da cidade possuem maior risco de abandono ou trancamento.

---

### Pergunta 6

#### Quais funcionalidades seriam essenciais após a identificação dos estudantes em risco?

**Resposta:**
O sistema deveria permitir acompanhamento contínuo dos estudantes identificados em risco, mostrando evolução da frequência e resultados das intervenções realizadas pela coordenação.

---

# 3. Questionário Aplicado aos Estudantes

A pesquisa teve como objetivo compreender os principais fatores que influenciam a evasão estudantil e identificar possíveis medidas institucionais de apoio.

## 3.1 Escala de Avaliação

* **1** — Nenhum impacto / Discordo totalmente
* **2** — Baixo impacto / Discordo parcialmente
* **3** — Impacto moderado / Neutro
* **4** — Alto impacto / Concordo parcialmente
* **5** — Impacto extremamente alto / Concordo totalmente

---

## 3.2 Perguntas Aplicadas

### Pergunta 1

**O quanto fatores socioeconômicos (transporte, moradia e alimentação) impactam a permanência no curso?**

* (1) Nenhum impacto
* (2) Baixo impacto
* (3) Impacto moderado
* (4) Alto impacto
* (5) Impacto extremamente alto

---

### Pergunta 2

**O quanto a dificuldade pedagógica com disciplinas básicas ou exatas faz pensar em trancar o curso?**

* (1) Nenhum impacto
* (2) Baixo impacto
* (3) Impacto moderado
* (4) Alto impacto
* (5) Impacto extremamente alto

---

### Pergunta 3

**Qual tipo de suporte institucional seria mais decisivo para não abandonar os estudos?**

* Auxílio financeiro
* Mentoria pedagógica e monitoria
* Apoio psicológico
* Orientação profissional e vocacional

---

### Pergunta 4

**Como o estudante avalia seu sentimento de pertencimento à instituição?**

* (1) Muito negativo
* (2) Negativo
* (3) Neutro
* (4) Positivo
* (5) Muito positivo

---

### Pergunta 5

**Qual plataforma o estudante prefere para receber alertas de apoio acadêmico?**

* E-mail institucional
* SIGAA / Aplicativo institucional
* WhatsApp
* Contato direto da coordenação

---

## 3.3 Pergunta Aberta Complementar

**O que o IFFar poderia fazer para melhorar a experiência acadêmica dos estudantes?**

---

# 4. Análise dos Resultados

## 4.1 Impacto de fatores socioeconômicos

Os resultados demonstraram que fatores socioeconômicos possuem influência significativa na permanência acadêmica. Aproximadamente **66,6%** dos participantes apontaram impacto moderado ou alto relacionado a transporte, moradia e alimentação.

## 4.2 Dificuldades pedagógicas

Cerca de **55,6%** dos estudantes classificaram as dificuldades pedagógicas em disciplinas básicas e exatas como impacto moderado, evidenciando necessidade de monitorias e apoio pedagógico.

## 4.3 Suportes institucionais mais importantes

O auxílio financeiro foi apontado como uma das principais medidas institucionais para evitar a evasão.

## 4.4 Plataformas preferidas para alertas

O WhatsApp foi a plataforma mais escolhida pelos estudantes para receber alertas acadêmicos.

## 4.5 Sugestões dos estudantes

Entre as sugestões apresentadas pelos estudantes estão melhorias no RU, reorganização da carga horária e ampliação de auxílios financeiros.

---

# 5. Requisitos Funcionais (RF)

| Código | Requisito Funcional                                                                          |
| ------ | -------------------------------------------------------------------------------------------- |
| RF-01  | Emitir alertas automáticos ao atingir 15% de faltas acumuladas ou frequência inferior a 75%. |
| RF-02  | Identificar estudantes com média inferior a 6,0 em disciplinas básicas.                      |
| RF-03  | Permitir upload quinzenal de diários de classe em PDF com processamento automático.          |
| RF-04  | Detectar ausência em avaliações acadêmicas.                                                  |
| RF-05  | Enviar notificações via WhatsApp, e-mail e plataformas institucionais.                       |
| RF-06  | Gerar dashboards e relatórios de risco para coordenação.                                     |
| RF-07  | Registrar e permitir acompanhamento pedagógico individualizado.                              |
| RF-08  | Permitir análise de fatores socioeconômicos.                                                 |
| RF-09  | Criar e gerenciar planos de intervenção.                                                     |
| RF-10  | Manter histórico evolutivo do estudante pós-intervenção.                                     |
| RF-11  | Disponibilizar filtros específicos para alunos sob acompanhamento.                           |

---

# 6. Requisitos Não Funcionais (RNF)

| Código | Requisito Não Funcional                                                                                      |
| ------ | ------------------------------------------------------------------------------------------------------------ |
| RNF-01 | O sistema deve criptografar dados sensíveis e possuir controle de acesso baseado em funções (RBAC).          |
| RNF-02 | O sistema deve possuir disponibilidade mínima de 99% e interoperabilidade com o sistema SIG.                 |
| RNF-03 | O sistema deve processar dados e gerar alertas em até 30 segundos, suportando múltiplos acessos simultâneos. |

---

# 7. Conclusão

Com base nas entrevistas realizadas e nos questionários aplicados aos estudantes, foi possível identificar fatores relevantes relacionados à evasão estudantil, principalmente dificuldades financeiras, problemas pedagógicos e necessidade de suporte institucional.

Os requisitos levantados para o sistema **Retenção-Grad** buscam permitir identificação precoce de estudantes em risco, contribuindo para ações preventivas, acompanhamento contínuo e melhoria da permanência acadêmica no Instituto Federal Farroupilha.

Além disso, a atividade permitiu compreender a importância da elicitação de requisitos no desenvolvimento de sistemas voltados à gestão acadêmica, evidenciando como entrevistas e questionários auxiliam na identificação de necessidades reais dos usuários e stakeholders.

---

# Integrantes

* João Zuge
* Victor Sauer
* Laezzer Freitas

---

# Tecnologias e Ferramentas

* GitHub
* Google Forms
* Microsoft Word

---

# Instituição

Instituto Federal Farroupilha – Campus São Borja
