<h1>Sentiment Analysis with spaCy and NLTK</h1>

<p>This project demonstrates sentiment analysis on restaurant reviews leveraging the powerful NLP libraries spaCy and NLTK. The goal is to extract meaningful insights from the reviews, such as frequently mentioned nouns, adjectives, verbs, and named entities in both positive and negative reviews.</p>

<h2>Getting Started</h2>

<h3>Prerequisites</h3>

<ul>
  <li>Python</li>
  <li>spaCy</li>
  <li>NLTK</li>
</ul>

<h3>Dataset</h3>

<p>The dataset consists of restaurant reviews. It includes various columns, but the primary focus is on the 'text' and 'stars' columns for sentiment analysis.</p>

<h2>Implementation Details</h2>

<h3>Data Preprocessing</h3>

<p>Reviews are classified based on their star rating: 1 star for negative and 5 stars for positive sentiment. Neutral reviews (3 stars) are excluded from the analysis.</p>

<h3>Feature Extraction with NLTK</h3>

<ul>
  <li>Tokenization, stopword removal, and lemmatization are applied to clean the review texts.</li>
  <li>Nouns, adjectives, and verbs are extracted to understand the content of the reviews better.</li>
  <li>Named Entity Recognition (NER) is performed to identify important entities mentioned in the reviews.</li>
</ul>

<h3>Analysis</h3>

<p>The analysis involves identifying the top 20 most frequently mentioned nouns, adjectives, verbs, and named entities in both positive and negative reviews, providing insights into customer preferences and areas of improvement.</p>

<h2>Results</h2>

<p>The analysis reveals distinct patterns in language use between positive and negative reviews, with specific terms and entities being more prevalent in one sentiment category over the other.</p>
