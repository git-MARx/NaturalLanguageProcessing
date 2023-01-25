# Text Preprocessing

> Text Preprocessing is the first step for any Natural Language Processing(NLP) problem. The text data extracted from internet is unstructured and noisy. Preprocessing is required to transform text to a proper format so that any Machine learning or deep learning model can perform properly. Text may be case-sensitive, or may contain contracted words, misspelled words which may reduce accuracy of the model. Preprocessing is task dependent too, 

## Must do Steps

#### Sentence segmentation

> Segmentation involves breaking down text into sentences. This sounds trivial task but it has a few challenges. For example, in English, the period is considered as the end of sentences but many abbreviations, including Mr., Inc. and all fractional numbers contain period. thus creating ambiguity untill end-of-sentence marker is used. 

#### Tokenization

> the process of breaking down the sentence into stream of words calledd 'tokens'. These words will be used further for text processing. There are many libraries which breaks based on whitespace or puctuations. Few cases are there when it should handle correctly. For example, don't, it's etc.

#### Change case

> In most NLP techniques, converting text to lowecase is good idea, it eliminates cases where two words have same meaning but different case like Ball and ball both represent ball.

#### Contraction removal


#### Punctuation, URL, email and digits handling

#### Normalisation (spell correction)

#### Stopwords removal

#### Stemming/ Lemmatization

#### White space removal

Task based approaches
