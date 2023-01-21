# Roadmap de aprendizado em Ciência de Dados

Olá, se você está por aqui é porque é interessado no assunto. Vou colocar alguns pontos que acho essencial de aprendizado e algumas dicas, no geral. **Não se baseie somente por esse roadmap, existem outros em que pessoas mais experientes escreveram**.

## 1. Principal "lema" da área

- O seu papel como cientista/analista de dados é traduzir/intepretar o que nossas análises significam para uma pessoa que não é desse mundo, com o objetivo de munir essa pessoa de informação para que ela possa tomar a decisão

- O software que você faz a análise é um **meio** para chegar no **fim** que é o resultado.
3451
- A habilidade de se comunicar é essencial também

## 2. Habilidades - O que aprender

### 2.1. Gerais

- **Seja focado e tente o máximo ter um aprendizado constante:** assim como em qualquer outra coisa que você quer aprender, isso é essencial para nossa área também. Existem muitas vertentes e assuntos a serem estudados dentro da área, então cuidado para não se desfocar.

- **Mantenha a calma e, se você tem alguma religião, a fé:** É um processo de aprendizado. Assim como você vai aprender a tocar violão, por exemplo, não é do nada que você vai aprender a soltar alguns acordes. Logo, não será do nada que você vai começar a gerar alguns modelos de Deep Learning no nível do pessoal da NVIDIA.

### 2.2. Técnicas

- **Estatística**: 
  - Análise Exploratória: medidas descritivas, como média, mediana, desvio padrão e etc (recomendo olhar o livro "Estatística Básica - Bussab e Morettin")
  - Correlação: positiva e negativa, o que influencia duas variáveis serem correlacionadas e a questão da causalidade
  - Teste de hipóteses: distribuições de probabilidade mais comuns; como a Normal, Binomial e Exponencial; p-valor e intervalo de confiança (recomendo o mesmo livro anterior)
  - Regressão: entenda a lógica por trás. Um pouco de multiplicação de matrizes. Faça um exemplo na mão da regressão **linear** e da **logística**. Estude um pouco sobre como funcionam a **ridge e lasso**. Existem outras que são interessantes conhecer, como a **quantílica** e a **elasticnet**
  - Séries temporais: estacionariedade, tendência, sazonalidade, autocorrelação, média móvel, testes de raiz unitária, modelos (ARIMA, HoltWinters e etc.) e métodos de avaliação do modelo (Erro Quadrático Médio, Erro Absoluto Médio e etc.)  
  - Outros tópicos não tão úteis nesse primeiro momento, mas que são interessantes:
    - Amostragem
    - Inferência bayesiana
    
- **Machine Learning**: Existem determinados assuntos nesse campo que são uma evolução ou releitura de algum conceito estatístico ou computacional
  
  - Modelos: 
    - Saiba a diferença entre um modelo **supervisionado** (de classificação ou regressão), **não supervisionado** e de **reforço**.     
    - Supervisionados:
      - Naive Bayes
      - KNN
      - Baseados em árvore: Árvore de decisão e Random Forest (o nome em inglês é mais legal de se falar). Entenda os hiperparâmetros e como esse modelo gera a decisão
      - Gradient Boosting Machine: é um método de aprendizado diferente em modelos. É muito utilizado atualmente, em modelos como **XGBoost**, **LGBM** e **Catboost**.      
    - Não supervisionados:
      - K-means (o mais utilizado)
      - Se você se interessar muito pelo tema: Hierárquico, mas pode pular tranquilamente
  - Métricas de avaliação:
    - Classificação: Matriz de Confusão, Acurácia, Recall, Precision, F1 
    - Regressão: R², MSE, RMSE, MAE e muitas outras siglas que existem    
  - O básico do básico do básico em NLP (Natural Language Process)  
  - Outros tópicos não tão úteis nesse primeiro momento, mas que são interessantes
    - Deep Learning
    - Visão Computacional

- **Softwares**:

  - **Python**: Sim, Python você utiliza em tudo que é canto: análise de dados, machine learning, automação e etc. Tem mais tutoriais, tanto em inglês quanto em português. 
  - **SQL**: Obrigatório, após conhecer algumas coisas de programação em Python, passe para essa linguagem para aprender a parte de DQL (Data Query Language), que é a parte de consulta aos dados.
  - **Excel**: Aprenda um pouco, até o PROCV. Talvez seja o software mais utilizado no ambiente profissional. Tem bastante solução gambiarra que você não consegue fazer em Python mas consegue em Excel.
  - **Git**: Usando esse "sisteminha", você consegue "voltar no tempo" para pegar uma modificação sua do passado, fora que você consegue *trackear* todas as modificações que você fez no seu código.
  - **Depois de tudo isso, caso você tenha tempo: Software de visualização**: PowerBI, Tableau e etc. Não tenho preferência, pois eu particularmente odeio fazer dashboard.
    
## 3. Como aprender

- **Um pouco de teoria e muito de prática**. Estude mas logo após documente tudo e publique em algum local público. 

- **Basei-se em projetos**: "Ah, quero aprender aquele modelo de Random Forest". Já cria um notebook/arquivo em Python, abre as 500 abas de teoria relacionado ao modelo, faz um resumo do que você entendeu e já aplica em um banco de dados. "Quais projetos posso fazer?" Se baseie nesse [tutorial](https://www.analyticsvidhya.com/blog/2018/05/24-ultimate-data-science-projects-to-boost-your-knowledge-and-skills/). 

- **Crie um portfólio:** É algo que escuto desde que eu estagiava na SEFA (2017 ou 18) e acompanhava o [slack do Datahackers](https://www.datahackers.com.br/slack/). Se você quer entrar na área e não tiver nenhum conhecido que pegue sua mão e te encaminhe para uma vaga, esse é o melhor jeito. 
  - **Por quê**: Basicamente, a ideia é ter um local onde as pessoas irão ver e acompanhar os seus trabalhos, projetos e aprendizado. 
  - **Onde**: Qualquer local, onde você consiga colocar seus códigos. Minha recomendação, por facilidade, é aqui no próprio Github. Mas você pode criar um blog pessoal também.

- **Divulgue seu aprendizado e projetos:** Sim, divulgue. Não adianta ter progresso e não mostrar para todos que você está aprendendo algo. Para isso, o [LinkedIn](www.linkedin.com) ainda é o melhor local. Lá é uma rede de profissionais no mercado de trabalho, onde tem recrutadores, coordenadores(a) das áreas de dados e outros estudantes também. Existem outros locais também, como as comunidades de dados/estatística, mas eu recomendaria focar no LinkedIn.
  - Seja constante nas suas postagens também. Tenta postar o que você aprendeu.
  - Faça conexões: envie convite para todo mundo que você ver no perfil algo relacionado com dados/data science/ciência de dados e etc... É o famoso *networking*
  - Tenha um perfil bem detalhado e alinhado com seus objetivos futuros: algumas dicas de como organizar seu LinkedIn você pode ver [aqui](https://twitter.com/camelouu/status/1409886433515606027), [aqui](https://twitter.com/camelouu/status/1522237678921601025) e esse [tutorial](https://twitter.com/pygineering/status/1539682926551523328) que é um pouco mais específico para nossa área.

### Como funcionou pra mim esse processo de aprendizado:

1. Decidi que queria aprender sobre Árvore de Decisão 
2. Separei uns links que achei de fácil leitura e entendimento (teoria), junto com alguns outros links que haviam códigos (prática)
3. Abri um jupyter notebook. Na 1ª parte, comecei fazendo um resumo da teoria que aprendi
4. Na 2º parte, coloquei em prática a parte do código. Treinando algoritmos e diferentes bilbiotecas
5. [Documentei legal](https://nbviewer.org/github/barbosarafael/Projetos/blob/master/Arvore_de_decisao_CART/arvore_de_decisao.ipynb) (eu acho) 
6. E comecei a [postar algumas atualizações do projeto no LinkedIn](https://www.linkedin.com/posts/rafael-barbosa0_datascience-activity-6684090468579479552-aaNt?utm_source=share&utm_medium=member_desktop)

## 4. Cursos

- [Introdução à Ciência de Dados 3.0](https://www.datascienceacademy.com.br/cursosgratuitos): **Gratuito**. Para pegar uma visão sobre a área, objetivos e futuros. 
- [Fundamentos de Linguagem Python Para Análise de Dados e Data Science](https://www.datascienceacademy.com.br/cursosgratuitos): **Gratuito**. Focado em prática com Python, então você vai aprender tanto Python quanto a parte de análise de dados. 
- [Formação Cientista de Dados: O Curso Completo [2023]](https://www.udemy.com/course/cientista-de-dados/): **Pago**, mas é um curso bem completo, onde o pessoal fala muito bem do professor e também dos assuntos abordados. Ele é focado em prática, o ideal para o nosso aprendizado. 
- Nanodegrees da Udacity: Recomendaria para pessoas que já são da área.
- Existem outros diversos sites gratuitos que ensinam tutoriais também: Medium, StackOverflow, Towards DataScience e etc.

## 5. Livros recomendados



### 5.1. Aqueles que vão te fazer pensar:

- Uma senhora toma chá
- O andar do bebado
- Como mentir com estatística
- A lógica do cisne negro
- Thinking with data

### 5.2. Técnicos:

- Storytelling com dados
- Data Science para negócios
- Introduction to Statistical Learning 
- Practical statistics for data science
- Estatística Básica (Bussab e Morettin)
- R para data science
- Hands on machine learning with sklearn
- Fundamentals of data visualization

## 6. Dicas gerais

- A Análise Exploratória dos Dados (parte em que você explora os seus dados) é uma parte muito subestimada. Se você não explorar seus dados bem, é capaz que os seus modelos/sistemas posteriores estejam viesados ou simplesmente com informações incosistentes.

- Não se apegue a aprender os modelos mais difíceis, como Deep Learning, Gradient Boosting e todos esses nomes de modelos complicados. Aprenda a base de como um modelo aprende, métricas, por exemplo. Muitas das vezes um simples modelo é o suficiente para responder um problema simples, até mesmo um modelo nem é necessário (grande parte das vezes)

- Se possível, tenha um profissional da área como mentor. Se não conseguir, jogue suas dúvidas conceitual ou de código em alguma comunidade, que pessoas irão te ajudar. A comunidade de dados no Brasil é bem legal, em sua grande maioria.

- Não pare de estudar, mesmo empregado. Claro, respeite seu tempo.

- Desenvolva o pensamento crítico. Comece a se perguntar coisas do tipo: "de onde saiu esse dado?" ou "se a gente utilizar variável X, não vamos estar impactando a variável Y?"

- Não foque somente em vagas de "Cientista de Dados": existem outras vagas que fazem exatamente a mesma coisa, só que com outro nome. Por isso, leia bastante atentamente a descrição da vaga

- É bastante normal iniciar a área de ciência de dados e se desvirtuar para outras áreas. Engenharia de Dados, Engenharia de Machine Learning, Pesquisador acadêmico e etc.

<p align="center">
  <img src="https://media.giphy.com/media/12XDYvMJNcmLgQ/giphy.gif" alt="animated" />
</p>
