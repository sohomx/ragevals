#### why:
the purpose of this project is to evaluate the effectiveness of language models by providing a quantitative analysis of their generated output. it helps users understand the accuracy, readability, and bias of the text.

#### what:
the code loads pre-trained models like gpt2 and bert, and calculates evaluation metrics such as bleu, rouge, meteor, chrf, bertscore, perplexity, diversity, racial bias, and readability.

#### how:
- it tokenizes and compares the generated text with reference text using bleu, rouge, and meteor scores.
- bertscore is calculated for semantic similarity.
- perplexity is used to measure fluency.
- diversity is calculated based on unique bigrams.
- racial bias is evaluated using a hate speech detection model.
- readability is assessed using flesch reading ease and flesch-kincaid grade level.
- results are displayed in a streamlit dashboard with explanations.
