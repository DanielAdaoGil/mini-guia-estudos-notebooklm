# mini-guia-estudos-notebooklm

## 1. Contexto e Objetivos

* **Assunto de Interesse:** O projeto consiste no desenvolvimento de um caderno temático digital focado em saúde mental, inteligência emocional, autoconhecimento e a teoria dos quatro temperamentos primários (colérico, sanguíneo, fleumático e melancólico).
* **Objetivos de Estudo:**
* Estruturar uma base de conhecimento sólida e cientificamente validada para alimentar uma IA consultiva (via NotebookLM).
* Criar um assistente virtual capaz de atuar como um diário terapêutico inteligente e um porto seguro para usuários que precisam desabafar ou organizar seus conflitos internos, mas encontram barreiras ou não sabem por onde começar.
* Mapear frameworks de comunicação e regulação emocional que permitam à IA dar respostas empáticas, personalizadas e livres de julgamentos.



---

2. Curadoria de Fontes e Caderno Digital
Para cumprir a exigência de 3 a 5 fontes de alto nível técnico, selecionamos os pilares mundiais do setor e realizamos o upload direto na ferramenta de IA.

Link de Acesso ao Caderno: Acesse o NotebookLM - Refúgio da Mente

1. **"Inteligência Emocional" – Daniel Goleman**
* *Foco técnico:* Fornece a base de neurociência e os 5 pilares do desenvolvimento emocional para a IA contextualizar os impulsos do usuário.


2. **"Permissão para Sentir" – Dr. Marc Brackett (Diretor de Yale)**
* *Foco técnico:* Introduz o **Método RULER** (*Reconhecer, Compreender, Nomear, Expressar e Regular*), servindo de algoritmo lógico para a IA guiar quem tem dificuldades em dar nome ao que sente.


3. **"Comunicação Não-Violenta" (CNV) – Marshall Rosenberg**
* *Foco técnico:* Framework de linguagem indispensável para garantir que as respostas do modelo sejam pautadas em escuta ativa, empatia e sem tons punitivos ou de julgamento.


4. **Estudos Clássicos dos Quatro Temperamentos Humanos (Abordagem Prática)**
* *Foco técnico:* Fornece padrões comportamentais (sanguíneo, colérico, melancólico e fleumático) para que o assistente reconheça os traços de personalidade predominantes na escrita do usuário.



---

## 3. Engenharia de Prompts e "Cicatrizes"

*Aqui registramos o raciocínio por trás dos testes e as dificuldades superadas no troubleshooting:*

* **Prompt Estratégico de Sistema (Testado):**
> *"Você é o 'Refúgio da Mente', um assistente de apoio emocional focado em autoconhecimento. Sua abordagem utiliza a CNV de Rosenberg e o Método RULER de Marc Brackett. Quando o usuário estiver confuso, investigue os sinais físicos e ajude-o a nomear a emoção antes de propor reflexões. Nunca emita diagnósticos clínicos."*


* **Cicatrizes & Troubleshooting (Dificuldades Encontradas):**
* *Problema:* Nos primeiros testes, a IA tentava agir de forma clínica ou sugerir o nome "Meu Psicólogo", o que cruzava linhas éticas e legais de uma profissão regulamentada.
* *Solução (Ajuste de Prompt):* Foi adicionada uma trava explícita no prompt de sistema delimitando a atuação do robô estritamente como um *diário consultivo e de apoio ao autoconhecimento*, incluindo uma diretriz mandatória para recomendar auxílio profissional humanizado em caso de crises severas.



---

## 4. Miniguia de Estudo (Entrega Final)

### A. Resumos Estruturados do Assunto

* **Inteligência Emocional:** Capacidade de identificar, avaliar e gerenciar as próprias emoções e as dos outros para mitigar o estresse e melhorar a comunicação.
* **Método RULER:** Divisão estruturada em 5 passos para a alfabetização emocional, crucial para converter sentimentos abstratos em termos exatos (ex: discernir ansiedade de mera frustração).
* **Os Quatro Temperamentos:** Estruturas fixas de personalidade que ditam como reagimos ao mundo. O modelo cruza a energia verbal do usuário com essas características para calibrar o acolhimento.

### B. Glossário com os Principais Conceitos

* **Sequestro da Amígdala:** Resposta emocional imediata e desproporcional que sobrepõe a mente racional.
* **Alfabetização Emocional:** O ato de dar nome preciso às emoções experimentadas.
* **Escuta Empática:** Processo de ouvir o outro focando em suas necessidades profundas, sem tentar consertar o problema imediatamente ou julgar o relato.
* **Temperamento Fleumático/Melancólico/Colérico/Sanguíneo:** Padrões constitucionais que definem ritmos de reação, sensibilidade e retenção de estímulos externos.

### C. Conjunto de Prompts Reutilizáveis para Revisões Futuras

* **Prompt para Análise de Caso:**
> *"Com base no Método RULER e no material anexado, analise o seguinte desabafo: '[Inserir Texto]'. Identifique em qual das fases o usuário se encontra travado e qual a melhor pergunta reflexiva para ajudá-lo a avançar."*


* **Prompt para Calibração de Tom:**
> *"Revise a resposta anterior da IA avaliando se ela cumpre estritamente as regras da Comunicação Não-Violenta (CNV). Corrija se houver qualquer tom imperativo ou de julgamento."*
