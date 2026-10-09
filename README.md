# 📚 Mini Guia de Estudos: Fundamentos de NLP com Python

> Projeto desenvolvido como parte de um desafio da [DIO](https://www.dio.me/), utilizando o NotebookLM como ferramenta de aprendizagem ativa, organização do conhecimento e experimentação com prompts.

## 📌 Sobre o Projeto

Este projeto apresenta um mini guia de estudos sobre **Processamento de Linguagem Natural (Natural Language Processing — NLP)** com foco em conceitos fundamentais e aplicações utilizando Python.

A proposta foi utilizar o **NotebookLM** como ferramenta de apoio ao aprendizado, trabalhando com fontes selecionadas, elaborando prompts estratégicos, analisando as respostas geradas e refinando as perguntas para obter resultados mais relevantes e adequados ao objetivo de estudo.

O projeto documenta não apenas o conhecimento adquirido, mas também o processo de aprendizagem e as estratégias utilizadas para interagir criticamente com a Inteligência Artificial.

## 🎯 Objetivos de Estudo

Os principais objetivos deste estudo são:

- Compreender o que é Processamento de Linguagem Natural e suas principais aplicações;
- Entender as etapas fundamentais de preparação e processamento de textos;
- Estudar conceitos como tokenização, stemming e lematização;
- Compreender diferentes formas de representação de texto, incluindo Bag of Words, TF-IDF e embeddings;
- Conhecer o funcionamento básico de modelos de linguagem baseados em n-grams;
- Compreender os fundamentos da classificação supervisionada de textos;
- Conhecer ferramentas Python utilizadas em NLP, especialmente NLTK e scikit-learn;
- Entender conceitos básicos de avaliação de modelos de classificação;
- Comparar abordagens tradicionais e modernas de NLP;
- Desenvolver estratégias de utilização de IA para apoiar futuras revisões e aprofundamentos.

## 🧠 Metodologia

O estudo foi desenvolvido utilizando o **NotebookLM** como ambiente central de pesquisa e aprendizagem.

O processo foi dividido em etapas:

1. **Curadoria de fontes** — seleção de materiais abertos relacionados a NLP;
2. **Exploração inicial** — elaboração de um primeiro prompt para identificar os principais conceitos;
3. **Refinamento dos prompts** — análise das limitações das respostas e criação de prompts mais específicos;
4. **Aprofundamento** — investigação de conceitos específicos, como embeddings;
5. **Síntese do conhecimento** — consolidação dos conteúdos em um guia estruturado;
6. **Criação de um glossário** — organização dos principais conceitos estudados;
7. **Criação de prompts reutilizáveis** — desenvolvimento de prompts para futuras revisões e aprofundamentos.

## 📖 Estrutura do Projeto

Este repositório apresenta:

- 📚 Curadoria das fontes utilizadas;
- 🤖 Processo de utilização do NotebookLM;
- 🧩 Engenharia de prompts e registro das principais dificuldades encontradas;
- 📖 Miniguia estruturado de fundamentos de NLP;
- 📕 Glossário dos principais conceitos;
- 🔄 Prompts reutilizáveis para futuras revisões;
- 💡 Principais aprendizados obtidos durante o projeto.

---

🚀 **Objetivo final:** transformar a IA de uma ferramenta que apenas fornece respostas em uma ferramenta de apoio ao aprendizado ativo, permitindo pesquisar, questionar, comparar, revisar e organizar conhecimento de forma estruturada.

## 📚 Curadoria das Fontes

Para construir este caderno temático, foram selecionadas quatro fontes abertas, escolhidas por apresentarem diferentes perspectivas sobre o estudo de Processamento de Linguagem Natural: fundamentos teóricos, processamento de texto com Python, modelos de linguagem e aprendizado de máquina aplicado a textos.

### 1. Natural Language Processing with Python

**Autores:** Steven Bird, Ewan Klein e Edward Loper  
**Recurso:** NLTK Book  
**Capítulo utilizado:** Chapter 3 — *Processing Raw Text*

Fonte utilizada principalmente para estudar processamento de texto, tokenização, expressões regulares, stemming, lematização e ferramentas da biblioteca NLTK.

🔗 [Acessar a fonte](https://www.nltk.org/book/)

### 2. Speech and Language Processing — Chapter 2

**Autores:** Daniel Jurafsky e James H. Martin  
**Obra:** *Speech and Language Processing*  
**Seção utilizada:** Words and Tokens

Fonte utilizada para estudar fundamentos de NLP, Unicode, tokenização, subpalavras e conceitos relacionados ao processamento de palavras e tokens.

🔗 [Acessar a fonte](https://web.stanford.edu/~jurafsky/slp3/)

### 3. Speech and Language Processing — Chapter 3

**Autores:** Daniel Jurafsky e James H. Martin  
**Obra:** *Speech and Language Processing*  
**Seção utilizada:** N-gram Language Models

Fonte utilizada principalmente para estudar modelos de linguagem baseados em n-grams, hipótese de Markov, estimativa de probabilidades, suavização e perplexidade.

🔗 [Acessar a fonte](https://web.stanford.edu/~jurafsky/slp3/)

### 4. Working With Text Data

**Fonte:** scikit-learn Documentation

Material utilizado para estudar representação de textos, Bag of Words, TF-IDF, classificação de textos, pipelines, Grid Search e avaliação de modelos.

🔗 [Acessar a documentação](https://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.html)

### 📌 Critério de seleção

As fontes foram escolhidas para complementar diferentes etapas do aprendizado:

| Fonte | Principal contribuição |
|---|---|
| NLTK Book | Processamento e preparação de texto com Python |
| Jurafsky & Martin — Cap. 2 | Fundamentos, palavras, tokens e subpalavras |
| Jurafsky & Martin — Cap. 3 | Modelos de linguagem e n-grams |
| scikit-learn | Representação, classificação e avaliação de textos |

## 🤖 Utilização do NotebookLM

O NotebookLM foi utilizado como ferramenta central para organizar as fontes, explorar os conceitos de NLP e apoiar a construção do conhecimento ao longo do projeto.

Em vez de utilizar a IA apenas para obter uma resposta final, o processo foi desenvolvido de forma iterativa:

1. As fontes foram selecionadas e adicionadas ao notebook;
2. Foi elaborado um primeiro prompt para obter uma visão geral dos fundamentos de NLP;
3. A resposta foi analisada para identificar pontos fortes e limitações;
4. O prompt foi refinado para melhorar a organização e a utilidade pedagógica da resposta;
5. Um terceiro prompt foi utilizado para aprofundar especificamente o conceito de embeddings;
6. Os resultados foram posteriormente sintetizados em um miniguia estruturado;
7. O conhecimento foi consolidado em um glossário e em uma coleção de prompts reutilizáveis.

## 🧩 Engenharia de Prompts e "Cicatrizes"

Uma das etapas mais importantes do projeto foi perceber que a qualidade da resposta da IA depende não apenas das fontes disponíveis, mas também da forma como a pergunta é formulada.

Por isso, foram realizados três experimentos principais.

### 🔹 Experimento 1 — Prompt Inicial

**Objetivo:** obter uma visão geral dos principais conceitos fundamentais de NLP.

**Prompt utilizado:**

> Com base exclusivamente nas fontes selecionadas neste notebook, explique o que é Processamento de Linguagem Natural (NLP) e quais são os principais conceitos fundamentais que um iniciante deve compreender. Organize a resposta em uma sequência lógica de aprendizagem, do conceito mais básico ao mais avançado. Para cada conceito, apresente uma definição simples e explique por que ele é importante para o estudo de NLP. Cite as fontes utilizadas.

**Resultado observado:**

A resposta apresentou uma sequência lógica de conceitos, passando por preparação de texto, tokenização, stemming, lematização, Bag of Words, TF-IDF, n-grams e classificação.

**Cicatriz identificada:** o resultado ficou bastante abrangente e misturou técnicas tradicionais com abordagens mais modernas. Além disso, as explicações apresentavam poucos exemplos práticos em Python.

---

### 🔹 Experimento 2 — Prompt Refinado

**Objetivo:** tornar a resposta mais estruturada, progressiva e adequada para um estudante iniciante.

**Principais alterações realizadas:**

- divisão do conteúdo em três níveis de aprendizagem;
- diferenciação entre abordagens tradicionais e modernas;
- solicitação de exemplos concretos;
- relação dos conceitos com suas implementações em Python;
- redução de conceitos considerados desnecessários para uma primeira introdução;
- solicitação explícita de referências às fontes.

**Resultado observado:**

A resposta passou a organizar o conteúdo em:

1. Fundamentos e preparação de texto;
2. Representação e modelagem estatística;
3. Classificação e aplicações.

Além disso, conceitos como Bag of Words e TF-IDF passaram a ser relacionados diretamente a ferramentas como `CountVectorizer()` e `TfidfVectorizer()`.

**Cicatriz identificada:** mesmo com a melhoria, o conceito de embeddings continuava aparecendo de forma relativamente breve em comparação com outros conceitos.

---

### 🔹 Experimento 3 — Aprofundamento em Embeddings

**Objetivo:** testar uma abordagem de prompt mais contextualizada para aprofundar um conceito específico.

O prompt partiu do conhecimento previamente adquirido pelo estudante:

> o estudante já compreendia tokenização, Bag of Words e TF-IDF, mas ainda não conhecia embeddings.

A pergunta solicitou que o NotebookLM explicasse as limitações das representações clássicas antes de introduzir embeddings, além de comparar as três abordagens em uma tabela e relacionar embeddings com modelos neurais e Transformers.

**Resultado observado:**

A resposta construiu uma progressão conceitual:

```text
Bag of Words / TF-IDF
        ↓
Limitações das representações discretas
        ↓
Representações densas
        ↓
Embeddings
        ↓
Modelos neurais
        ↓
Transformers
```

## 📖 Miniguia de Estudos

### 1. O que é Processamento de Linguagem Natural?

O **Processamento de Linguagem Natural (Natural Language Processing — NLP)** é uma área da ciência da computação e da linguística computacional dedicada ao desenvolvimento de métodos para analisar, processar, compreender e gerar linguagem humana em formato textual ou falado.

O objetivo é permitir que sistemas computacionais trabalhem com dados linguísticos, possibilitando aplicações como classificação de documentos, tradução, previsão de palavras e análise de textos.

---

### 2. Preparação e Processamento do Texto

Antes que um texto possa ser analisado por algoritmos de NLP, geralmente é necessário transformá-lo e organizá-lo em uma representação adequada para processamento computacional.

#### 2.1 Unicode e UTF-8

**Unicode** é um padrão que atribui identificadores únicos aos caracteres de diferentes sistemas de escrita.

**UTF-8** é uma forma de codificação que representa esses caracteres como sequências de bytes.

Essa etapa é importante porque textos podem ser produzidos em diferentes idiomas e sistemas, e uma codificação incorreta pode causar problemas durante o processamento.

#### 2.2 Expressões Regulares

As **expressões regulares (Regex)** permitem identificar e manipular padrões específicos em sequências de caracteres.

Em NLP, podem ser utilizadas para localizar, substituir ou filtrar determinados padrões em textos.

#### 2.3 Tokenização

A **tokenização** consiste em dividir um texto em unidades menores chamadas **tokens**.

Dependendo da abordagem utilizada, os tokens podem representar palavras, sinais de pontuação ou subpalavras.

A tokenização é uma etapa fundamental porque transforma o texto contínuo em unidades que podem ser processadas por modelos computacionais.

#### 2.4 Stemming

O **stemming** reduz palavras a uma forma simplificada ou radical por meio de regras heurísticas.

Por exemplo, diferentes formas de uma palavra podem ser reduzidas a uma representação comum.

A principal vantagem é reduzir variações no vocabulário, embora o resultado nem sempre corresponda a uma palavra válida do idioma.

#### 2.5 Lematização

A **lematização** também busca reduzir diferentes formas de uma palavra, mas procura chegar ao seu **lema**, ou seja, à forma canônica da palavra.

Diferentemente do stemming, a lematização considera informações linguísticas para produzir uma forma válida.

---

### 3. Representação de Texto

Computadores precisam transformar o conteúdo textual em representações numéricas para que algoritmos de aprendizado de máquina possam trabalhar com os dados.

#### 3.1 Bag of Words

O modelo **Bag of Words (BoW)** representa documentos com base na ocorrência ou frequência das palavras presentes no vocabulário.

Cada palavra pode corresponder a uma dimensão do vetor.

**Vantagem:** é simples e direto.

**Limitação:** pode produzir vetores de alta dimensão e esparsos e não representa diretamente relações semânticas entre palavras.

#### 3.2 TF-IDF

O **TF-IDF (Term Frequency — Inverse Document Frequency)** atribui pesos aos termos considerando sua frequência no documento e sua frequência no conjunto de documentos.

A técnica reduz a importância de termos muito frequentes no corpus e pode destacar palavras mais relevantes para determinados documentos.

No scikit-learn, essa representação pode ser implementada com ferramentas como:

```python
from sklearn.feature_extraction.text import TfidfVectorizer

vectorizer = TfidfVectorizer()
X = vectorizer.fit_transform(documents)
```

## 📕 Glossário

| Conceito | Definição | Por que é importante? |
|---|---|---|
| **Bag of Words (BoW)** | Representação de texto baseada na ocorrência ou frequência das palavras presentes em um vocabulário. | Permite transformar textos em representações numéricas que podem ser utilizadas por algoritmos de aprendizado de máquina. |
| **BPE (Byte-Pair Encoding)** | Técnica de tokenização que representa palavras utilizando unidades que podem ser combinadas em subpalavras. | Ajuda a lidar com palavras desconhecidas e vocabulários de grande dimensão. |
| **Embeddings** | Representações vetoriais densas de palavras ou outros elementos linguísticos em um espaço contínuo. | Permitem representar relações entre elementos com base nos contextos em que aparecem. |
| **F1-score** | Métrica que combina precision e recall em uma única medida. | Permite avaliar simultaneamente essas duas dimensões do desempenho de um classificador. |
| **Grid Search** | Estratégia para testar diferentes combinações de parâmetros de um modelo. | Ajuda a encontrar configurações mais adequadas para um algoritmo. |
| **Lematização** | Processo de reduzir diferentes formas de uma palavra à sua forma canônica, ou lema. | Permite agrupar variações linguísticas preservando uma representação válida da palavra. |
| **Matriz de Confusão** | Tabela que organiza as previsões de um classificador de acordo com as classes reais e previstas. | Facilita a visualização dos acertos e erros de um modelo. |
| **Modelos de Linguagem** | Modelos que atribuem probabilidades a sequências linguísticas ou utilizam contexto para prever elementos de uma sequência. | São fundamentais para modelar e prever padrões em linguagem. |
| **Naïve Bayes** | Classificador probabilístico baseado no teorema de Bayes e em uma hipótese de independência condicional. | É uma abordagem tradicional utilizada na classificação de textos. |
| **N-gram** | Sequência de `n` elementos linguísticos utilizada para modelar relações entre palavras. | Permite construir modelos de linguagem e realizar previsões baseadas em contexto limitado. |
| **NLTK** | Biblioteca Python utilizada para tarefas de processamento de linguagem natural. | Disponibiliza ferramentas para trabalhar com textos, corpora, tokenização e outras tarefas de NLP. |
| **Perplexidade** | Métrica utilizada para avaliar modelos de linguagem. | Permite analisar o desempenho de um modelo em dados que não foram utilizados durante seu treinamento. |
| **Pipeline** | Estrutura que organiza várias etapas de processamento ou aprendizado de máquina em sequência. | Facilita a construção e aplicação consistente de fluxos de NLP. |
| **Precision** | Proporção de previsões positivas que estavam corretas. | Permite avaliar a precisão das previsões positivas de um classificador. |
| **Recall** | Proporção dos exemplos positivos reais que foram identificados pelo modelo. | Indica a capacidade do modelo de encontrar os exemplos positivos. |
| **Regex (Expressões Regulares)** | Linguagem utilizada para identificar e manipular padrões em sequências de caracteres. | É útil para localizar, substituir e filtrar padrões em textos. |
| **scikit-learn** | Biblioteca Python para aprendizado de máquina que oferece ferramentas para representação, classificação, avaliação e construção de pipelines. | Permite implementar de forma prática diversos fluxos de aprendizado de máquina aplicado a textos. |
| **SVM (Support Vector Machine)** | Algoritmo de aprendizado supervisionado que busca encontrar uma fronteira capaz de separar diferentes classes. | Pode ser utilizado para classificação de documentos e outros problemas de classificação textual. |
| **Stemming** | Processo heurístico que reduz palavras a uma forma simplificada ou radical. | Reduz variações no vocabulário e pode facilitar determinadas tarefas de processamento textual. |
| **TF-IDF** | Representação que pondera a frequência de um termo considerando também sua frequência no conjunto de documentos. | Ajuda a destacar termos relevantes e reduzir a importância de palavras muito frequentes no corpus. |
| **Tokenização** | Processo de dividir um texto em unidades menores chamadas tokens. | Transforma texto contínuo em unidades que podem ser processadas por modelos computacionais. |
| **Treinamento e Teste** | Separação dos dados para ajustar um modelo e posteriormente avaliar seu desempenho em dados não utilizados no treinamento. | Ajuda a verificar como o modelo se comporta diante de dados não utilizados para seu ajuste. |
| **Unicode** | Padrão que atribui identificadores únicos aos caracteres de diferentes sistemas de escrita. | Permite representar textos de diferentes idiomas de maneira consistente. |
| **UTF-8** | Forma de codificação que representa caracteres Unicode como sequências de bytes. | Permite armazenar e processar textos de diferentes idiomas de forma compatível entre sistemas. |

## 🔄 Prompts Reutilizáveis

Durante o projeto, foi possível perceber que prompts bem estruturados podem transformar a IA em uma ferramenta de apoio à aprendizagem ativa.

Os prompts abaixo foram organizados para serem reutilizados em futuras revisões de conteúdos relacionados a NLP.

> 💡 **Dica:** substitua os elementos entre `[colchetes]` pelo conceito, tema ou algoritmo que deseja estudar.

### 1. Explicação Didática para Iniciantes

```text
Com base exclusivamente nas fontes deste notebook, explique o conceito de [CONCEITO] em Processamento de Linguagem Natural como se estivesse ensinando um estudante iniciante. Apresente: (1) uma definição simples e direta, (2) o problema prático que ele resolve em NLP e (3) um exemplo concreto do seu uso. Cite especificamente as fontes que fundamentam a explicação.
```

### 2. Detalhamento Técnico

```text
Com base exclusivamente nas fontes do notebook, detalhe o funcionamento técnico de [CONCEITO/ALGORITMO]. Explique passo a passo como ele processa o texto ou os dados, quais são suas entradas e saídas e quais premissas ou hipóteses teóricas sustentam seu funcionamento. Cite as fontes para cada etapa explicada.
```

**Objetivo:** aprofundar o entendimento sobre o funcionamento de uma técnica ou algoritmo de NLP.

---

### 3. Comparação de Conceitos

```text
Com base exclusivamente nas fontes deste notebook, compare os conceitos de [CONCEITO A] e [CONCEITO B] em NLP. Apresente uma tabela comparativa abordando: (1) definição, (2) tipo de representação ou processamento, (3) principais vantagens, (4) limitações e (5) cenários de uso recomendados. Cite as fontes consultadas.
```

**Objetivo:** identificar rapidamente semelhanças, diferenças, vantagens e limitações entre conceitos relacionados.

---

### 4. NLP Tradicional vs. Moderno

```text
Com base exclusivamente nas fontes fornecidas neste notebook, analise a evolução da abordagem tradicional baseada em [CONCEITO TRADICIONAL] para a abordagem moderna baseada em [CONCEITO MODERNO]. Explique quais limitações do modelo tradicional motivaram essa transição e como a abordagem moderna resolve essas limitações. Indique as fontes que sustentam a análise.
```

**Objetivo:** compreender a evolução das abordagens utilizadas em NLP.

---

### 5. Implementação em Python

```text
Com base exclusivamente no suporte das fontes deste notebook, utilizando NLTK ou scikit-learn quando apropriado, escreva um exemplo de código funcional em Python para realizar a etapa de [ETAPA, EX.: TOKENIZAÇÃO, REGEX, STEMMING OU VETORIZAÇÃO] em um texto de exemplo. Comente o código explicando o papel de cada função e indique a fonte que embasa a implementação.
```

**Objetivo:** transformar um conceito teórico em uma implementação prática em Python.

---

### 6. Pipeline de Classificação

```text
Com base exclusivamente nas ferramentas do scikit-learn presentes nas fontes deste notebook, crie um script em Python que monte um Pipeline de classificação de texto para [TEMA/DATASET]. O código deve incluir vetorização, transformação TF-IDF, o classificador [ALGORITMO] e a avaliação de desempenho no conjunto de teste. Comente o código e cite as fontes de referência.
```

**Objetivo:** praticar a integração das diferentes etapas de um fluxo de classificação de textos.

---

### 7. Quiz de Revisão

```text
Com base exclusivamente nos conteúdos das fontes deste notebook, elabore um conjunto de 5 questões de revisão sobre [TEMA/CONCEITO]. Inclua questões de múltipla escolha e de verdadeiro/falso com possíveis confusões conceituais sobre o assunto. Disponibilize o gabarito comentado ao final, citando a fonte que justifica cada resposta correta.
```

**Objetivo:** testar a retenção do conteúdo e identificar possíveis lacunas de conhecimento.

---

### 8. Análise de Limitações e Trade-offs

```text
Com base exclusivamente nas fontes do notebook, faça uma análise crítica sobre o uso de [CONCEITO/ALGORITMO] em tarefas de NLP. Liste: (1) suas principais vantagens, (2) suas limitações técnicas ou computacionais e (3) em quais situações essa abordagem pode falhar ou não ser a ideal. Embase a resposta estritamente nas fontes e cite as referências.
```

**Objetivo:** desenvolver uma visão crítica sobre as vantagens, limitações e situações de uso de uma abordagem.

---

### 9. Diagnóstico de Confusões Conceituais

```text
Com base exclusivamente nas fontes deste notebook, identifique 3 erros de interpretação ou confusões conceituais que estudantes iniciantes podem cometer ao estudar [TEMA]. Para cada confusão, explique qual é o erro e qual é a interpretação correta segundo as fontes, citando as fontes que sustentam a correção.
```

**Objetivo:** reforçar distinções importantes e corrigir possíveis interpretações equivocadas.

---

### 10. Roteiro de Estudo Progressivo

```text
Com base exclusivamente no escopo das fontes fornecidas neste notebook, crie um roteiro de estudo progressivo para dominar o tema [TEMA]. Organize a resposta em 3 níveis subsequentes (Básico, Intermediário e Avançado), explicando em cada nível qual conceito deve ser estudado, por que ele vem nessa ordem e citando a fonte correspondente.
```

**Objetivo:** criar um caminho estruturado de aprendizagem para um tema de NLP.

## 💡 Principais Aprendizados

A realização deste projeto permitiu consolidar conhecimentos fundamentais de Processamento de Linguagem Natural e, ao mesmo tempo, desenvolver uma forma mais estruturada de utilizar Inteligência Artificial como ferramenta de aprendizagem.

Entre os principais aprendizados estão:

- A importância da preparação e normalização dos dados textuais antes da aplicação de modelos;
- As diferenças entre representações tradicionais, como Bag of Words e TF-IDF, e representações densas como embeddings;
- O papel dos modelos de linguagem na análise e previsão de sequências textuais;
- Os fundamentos da classificação supervisionada aplicada a textos;
- A importância de separar dados de treinamento e teste e utilizar métricas adequadas para avaliar modelos;
- A possibilidade de combinar diferentes etapas de NLP utilizando pipelines em Python;
- A importância de formular prompts claros, contextualizados e restritivos para obter respostas mais úteis de uma IA;
- A necessidade de analisar criticamente as respostas geradas pela IA, verificando suas fontes e limitações.

### 🧠 Aprendizado sobre o uso da IA

Um dos principais resultados deste projeto foi perceber que a IA pode ser utilizada não apenas como fonte de respostas, mas como uma ferramenta para **explorar, questionar, comparar, revisar e organizar conhecimento**.

A experimentação com diferentes prompts mostrou que pequenas mudanças na estrutura da pergunta podem alterar significativamente a utilidade da resposta. O processo iterativo foi, portanto, parte importante do próprio aprendizado.

## 🚀 Próximos Passos

Como continuidade deste estudo, os próximos passos podem incluir:

- Implementar pequenos projetos de NLP utilizando Python;
- Explorar diferentes técnicas de classificação de textos;
- Aprofundar o estudo de embeddings e modelos neurais;
- Experimentar bibliotecas e ferramentas adicionais para NLP;
- Aplicar os conhecimentos adquiridos em projetos práticos, como análise de sentimentos e classificação de documentos.

---

## 📌 Conclusão

Este projeto demonstra uma abordagem de aprendizagem baseada em **curadoria de fontes, experimentação com prompts, análise crítica e organização do conhecimento**.

O objetivo não foi apenas obter respostas utilizando Inteligência Artificial, mas compreender como utilizá-la de forma consciente e estruturada como parte do processo de aprendizagem.

---

⭐ **Projeto desenvolvido para o desafio da DIO — Mini Guia de Estudos com NotebookLM.**

