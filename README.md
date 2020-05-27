# Support Ticket NLP
Ticket Classification and Key Phrases Extraction

- Identify the main issues in the ticket description
- Extract the key phrases in the ticket description

<img  src="https://monkeylearn.com/blog/wp-content/uploads/2019/10/Screen-Shot-2019-10-03-at-12.29.23-PM.png" width="500px">

----------------
#### Data
<a href="https://www.kaggle.com/aniketg11/supportticketsclassification">Support Ticket Classification</a>

----------------
#### Tasks
<ol>
  <li>Topic Modeling with LDA model
    <ol>
      <li>
      Preprocessing
        <ol>
          <li>Divide text to tokens</li>
          <li>Remove stopwords, punctuations</li>
          <li>Lemmatization</li>
        </ol>
      </li>
      <li>Compute coherence values to find the optimal number of topics</li>
      <li>Build the LDA model</li>
      <li>Utilize pyLDAvis to visualize the topics</li>
    </ol>
  </li>
  <li>
  Key Phrases Extraction with <a href="https://github.com/DerwenAI/pytextrank">pytextrank</a> (combining spaCy and networkx)
  </li>
</ol>
  
----------------
#### Terminologies
<ul>
  <li>Topic Coherence</li>
  Scores a single topic by measuring the degree of semantic similarity between high scoring words in the topic
  <li>Latent Dirichlet Allocation (LDA)
    
  Given the # documents, # words, and # topics, output:
    <ul>
      <li>distribution of words for each topic K</li>
      <li>distribution of topics for each document i</li>
    </ul>
    <img src="https://miro.medium.com/max/638/0*Sj65xR38wDwuxhtr.jpg" height="300px">
  </li>
</ul>
