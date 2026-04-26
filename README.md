# Accenture - DIO - Python para Análise e Automação de Dados

<br/>

## 🛠️ O Desafio

Explorar o uso da Inteligência Artificial como uma verdadeira ferramenta de aprendizagem ativa. Neste projeto prático, aliar pensamento crítico, curadoria de fontes e organização do conhecimento para criar um Caderno Temático no NotebookLM.

<br/>

## 🎯 Contexto e Objetivo

Estou concluindo meu treinamento no módulo de introdução à Engenharia de Prompt na empresa DIO e com patrocínio da empresa Accenture. Gostaria de me aprofundar para obter uma forte melhoria nesta disciplina.
Para isso, disponibilizei 4 fontes de texto disponíveis na web ao NotebookLM, para explorar esta ferramenta de aprendizagem.

<br/>

## 📚 Curadoria de Fontes

**Fontes de Texto (WEB)**
  * [Ramos da Informática - Guia de Engenharia de Prompt: O Papel da Engenharia de Prompt](https://ramosdainformatica.com.br/engenharia-prompt-guia/)
  * [IBM - Técnicas de Engenharia de Prompts](https://www.ibm.com/br-pt/think/topics/prompt-engineering-techniques#7281536)
  * [Microsoft - Técnicas de engenharia de prompt](https://learn.microsoft.com/pt-br/azure/foundry/openai/concepts/prompt-engineering)
  * [AWS - O que é engenharia de prompt?](https://aws.amazon.com/pt/what-is/prompt-engineering/)

**Resumo apresentado após carga das fontes adicionadas**
* As fontes apresentadas constituem um guia abrangente sobre a Engenharia de Prompt, explorando sua importância estratégica para otimizar a interação com modelos de linguagem (LLMs). O conteúdo detalha frameworks estruturais, como PASSEF e COSTAR, e descreve técnicas avançadas de raciocínio, incluindo Cadeia de Pensamento (CoT) e Árvore de Pensamentos. Além de oferecer definições conceituais, os textos fornecem orientações práticas para desenvolvedores e gestores sobre como evitar alucinações da IA e aumentar a precisão das respostas. As informações são complementadas por visões técnicas de grandes empresas como AWS, Microsoft e IBM, que discutem a integração de ferramentas externas e a automação de processos. Em suma, o material serve como um manual para transformar comandos em linguagem natural em resultados eficientes e personalizados no cenário da inteligência artificial generativa.

  
<br/>

## 🤖 Engenharia de Prompts e "Cicatrizes"

**Prompt Apresentado ao NotebookLM**

Estou concluindo meu treinamento no módulo de introdução à Engenharia de Prompt na empresa DIO e com patrocínio da empresa Accenture. Gostaria de me aprofundar para obter uma forte melhoria nesta disciplina. 
Para isso, disponibilizei 4 fontes de dados e espero que com seu conhecimento profundo a respeito do tema, compile, extraia e organize o material.
Com o conhecimento de um professor especialista no assunto, prepare um curso deste material para que eu possa estudar e conseguir o nível intermediário em Engenharia de Prompts. 
Ao final, favor gerar:
- Um Resumo Estruturado
- Um Glossário com os princípais conceitos
- Um conjunto de prompts reutilizáveis que possam apoiar sobre futuras revisões sobre este tema

⚠️ **Cicatriz**
No grossário, ao me deparar com a definição sobre RAG, voltei ao NotebookLM e informei que eu havia ficado em dúvida, principalmente a parte que continha o texto "base de dados externa". O NotebookLM fez uma explicação detalhada sobre RAG. Então, solicitei que refizesse a explicação para que eu fizesse a substituição no Glossário, pois desta forma, para mim havia ficado mais clara a definição.
No Glossário, apresento as duas definições. A primeira apresentada e a segunda que foi a revisada.

**Resultado Obtido**

Parabéns pela conclusão da introdução ao seu treinamento. Com base nos materiais fornecidos pela AWS, Microsoft, IBM e no Guia de Engenharia de Prompt, preparei um currículo de nível intermediário focado na otimização de resultados e na criação de sistemas complexos de IA.

________________________________________

<br/>

## **Miniguia de Estudo (Entrega Final)**

### **Curso: Engenharia de Prompt de Nível Intermediário**

#### **Módulo 1: Frameworks Estruturais Avançados**

Neste módulo, você aprenderá a deixar de lado prompts simples para adotar estruturas que garantem precisão técnica e engajamento.

  *	PASSEF (Papel, Ação, Contexto, Exemplo, Formato): Ideal para automação de tarefas técnicas e criação de agentes de IA.

  *	COSTAR (Contexto, Objetivo, Estilo, Tom, Audiência, Resposta): Focado em comunicação estratégica e adaptação de conteúdo para públicos específicos.

#### **Módulo 2: Técnicas de Raciocínio e Decomposição de Problemas**

Para lidar com problemas complexos que a IA não resolve de "primeira", utilizamos métodos que mimetizam o pensamento humano.

  * **Cadeia de Pensamento (CoT):** Instruir o modelo a resolver problemas passo a passo.

  * **Árvore de Pensamentos (ToT):** O modelo gera várias possibilidades e explora ramos de raciocínio antes de decidir a melhor saída.

  * **Do Menor para o Maior (Least-to-Most):** Dividir um problema em subproblemas sequenciais onde a solução de um ajuda no próximo.
 
#### **Módulo 3: Controle de Saída e Otimização de Contexto**

Aprenda a manipular os parâmetros e a sintaxe para obter respostas previsíveis e úteis para sistemas.

  * **Aprendizado com Poucas Tentativas (Few-Shot):** Fornecer exemplos reais de entrada e saída para "preparar" o modelo.

  * **Parâmetros de Temperatura e Top_p:** Ajustar a aleatoriedade e criatividade do modelo (valores baixos para precisão, altos para criatividade).

  * **Contexto de Fundamentação (Grounding):** Fornecer dados externos (como documentos ou APIs) para que a IA baseie suas respostas em fatos, evitando invenções.

#### **Módulo 4: Refinamento Iterativo e Segurança**

A engenharia de prompt é um processo contínuo de tentativa e erro.

  * **Reflexão e Autoajuste:** Pedir à IA para criticar e melhorar a própria solução.

  * **Mitigação de Alucinações:** Técnicas para garantir que o modelo admita quando não sabe uma resposta.

________________________________________

### **Resumo Estruturado do Material**

1.	**Fundamentos do Prompt:** Um prompt é o texto de entrada em linguagem natural que orienta um modelo (LLM) a executar uma tarefa. Ele serve para preencher a lacuna entre o usuário final e a IA.

2.	**Componentes Essenciais:** Um prompt eficaz geralmente contém instruções claras, conteúdo principal (dados a serem processados), exemplos (few-shot) e indicações (o "pontapé inicial" da resposta).

3.	**Técnicas de Precisão:**

     3.1 **Sintaxe Clara:** Uso de separadores (como --- ou ###), Markdown ou XML para diferenciar seções do prompt.

     3.2 **Repetição de Instruções:** Colocar as ordens mais importantes no início e repeti-las no final para combater o "desvio de relevância".

4.	**Agentes de IA:** São sistemas que combinam modelos de linguagem com memória, ferramentas externas e bases de conhecimento (RAG) para executar tarefas complexas de forma autônoma.

5.	**Boas Práticas:** Ser específico, usar analogias, limitar o espaço operacional da IA e dar uma "saída" ao modelo (ex: "se não encontrar a resposta, diga 'não encontrado'").

________________________________________

### **Glossário de Conceitos Principais**

  * **Agentes de IA:** Sistemas que usam LLMs integrados a APIs e memórias para agir no mundo real.
    
  * **Alucinação:** Quando a IA gera informações imprecisas ou totalmente fabricadas de forma convincente.
  
  * **Few-shot Learning:** Técnica de fornecer de 1 a 3 exemplos de entrada/saída no prompt para guiar o modelo.
  
  * **LLM (Large Language Model):** Modelos de linguagem de grande escala treinados em vastos volumes de dados para prever a próxima palavra mais provável.
  
  * **Prompting Maiêutico:** Método onde se pede à IA uma explicação e, em seguida, explicações para as partes dessa explicação para verificar consistência.
  
  * **RAG (Retrieval-Augmented Generation):** Técnica que recupera informações de uma base de dados externa para que a IA gere respostas fundamentadas em fatos reais.
  
  * **Tokens:** Unidades básicas de texto processadas pela IA (podem ser palavras inteiras ou sílabas).
  
  * **Zero-shot:** Pedir uma tarefa sem fornecer nenhum exemplo prévio, confiando apenas no conhecimento base do modelo.

________________________________________

### **Conjunto de Prompts Reutilizáveis para Revisão**

Estes prompts foram desenhados para que você possa usá-los com qualquer ferramenta de IA para revisar os temas deste material:

1. **Prompt para Prática de Framework PASSEF:**

"Você é um especialista em pedagogia de IA. Ação: Resuma os principais conceitos do framework PASSEF. Contexto: Estou estudando para o nível intermediário em Engenharia de Prompt. Exemplo: Explique o 'P' de Papel como a definição da persona do agente. Formato: Crie um mapa mental em formato de lista hierárquica."

2. **Prompt para Revisão de Técnicas de Raciocínio (CoT):**

"Contexto: Engenharia de Prompt Avançada. Objetivo: Explicar a diferença entre Cadeia de Pensamento (CoT) e Árvore de Pensamentos (ToT). Estilo: Didático e comparativo. Tom: Profissional. Audiência: Alunos da DIO/Accenture. Resposta: Uma tabela comparativa com definição, caso de uso e um exemplo de comando para cada técnica."

3. **Prompt para Identificação de Componentes (Metaprompt):**

"Atue como um Engenheiro de Prompt Automático. Analise o seguinte prompt [INSERIR SEU PROMPT AQUI] e identifique onde estão as Instruções, o Conteúdo Principal e as Indicações de Saída. Sugira uma melhoria usando a técnica de Sintaxe Clara (Markdown)."

4. **Prompt para Teste de Parâmetros (Simulação):**

"Explique o conceito de 'Temperatura' em LLMs. Primeiro, dê uma resposta com 'Temperatura 0.1' (focada e técnica). Depois, dê uma resposta com 'Temperatura 0.9' (criativa e com analogias). Conclua explicando qual delas é melhor para gerar um código Python."

