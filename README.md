<h1>Sentiment Analysis Project</h1>
<h2>RESTAURENT REVIEW PROJECT Overview</h2>
    <p>This project aims to analyze sentiments expressed in text reviews, categorizing them into positive or negative sentiments. It leverages Natural Language Processing (NLP) techniques, utilizing the NLTK library for preprocessing and applying a Naive Bayes classifier for the sentiment analysis. The goal is to accurately predict the sentiment based on the textual content of the reviews.</p>
 <h2>Features</h2>
    <ul>
        <li>Text preprocessing including:
            <ul>
                <li>Removing punctuation and non-alphabet characters</li>
                <li>Converting text to lowercase</li>
                <li>Tokenization</li>
                <li>Removal of stopwords (with the exception of "not")</li>
                <li>Stemming</li>
            </ul>
        </li>
        <li>Feature extraction using CountVectorizer</li>
        <li>Sentiment classification using the Gaussian Naive Bayes algorithm</li>
    </ul>
<h2>Dataset</h2>
    <p>The dataset used for this project consists of 1,000 text reviews. Each review is labeled with its corresponding sentiment (positive or negative). [Provide more details about the dataset here, such as source, if applicable.]</p>
<h2>Requirements</h2>
    <ul>
        <li>Python 3.x</li>
        <li>NLTK</li>
        <li>scikit-learn</li>
    </ul>
<h2>DETECT HATE SPEECH IN TWEET PROJECT Overview</h2>
    <p>This project aims to detect hate speech within tweets, identifying potentially harmful content and classifying it accordingly. It explores preprocessing techniques suitable for tweet data and employs logistic regression for classification.</p>
 <h2>Features</h2>
    <ul>
        <li>Text preprocessing including:
            <ul>
                <li>leaning tweets to remove URLs, user mentions, and hashtags.</li>
                <li>Removing special characters and numbers.</li>
                <li>Conversion to lowercase.</li>
                <li>Tokenization.</li>
                <li>Removal of stopwords.</li>
            </ul>
        </li>
        <li>Feature extraction</li>
        <li>Utilizing TfidfVectorizer for transforming text data into TF-IDF features.</li>
    </ul>
<h2>Dataset</h2>
    <p>kaggle datasets download -d arkhoshghalb/twitter-sentiment-analysis-hatred-speech</p>
<h2>Requirements</h2>
    <ul>
        <li>Python 3.x</li>
        <li>NLTK</li>
        <li>scikit-learn</li>
    </ul>

    
