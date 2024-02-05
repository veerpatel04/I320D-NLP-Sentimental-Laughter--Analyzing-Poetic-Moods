# I320D NLP-Sentimental Laughter - Analyzing Poetic Moods

The "Poetic Sentiment Analysis" project focuses on understanding the emotions in poems using the Gutenberg Poem Dataset from Project Gutenberg. This dataset contains a variety of English poems, and we'll use computer techniques to explore the feelings expressed in these verses. The project involves several steps, starting with looking closely at the dataset to understand its structure and important parts. After that, we'll clean up the text in the poems, making it easier for the computer to understand.

Next, we'll dig into the words used in the poems to see which ones come up the most. We're especially interested in two-word combinations. With this information, we'll create visual representations called word clouds to highlight the important words for positive, negative, and mixed feelings in the poems. By comparing these word clouds, we can find out what words are common and what makes each type of sentiment unique.

The last part of the project is about discussing what we've learned and thinking about ways to make our analysis even better. We might suggest using more advanced techniques or adjusting the list of unnecessary words based on the kind of language used in poetry. The goal is to gain insights into the emotional side of poems and contribute to the ongoing exploration of sentiment analysis in this creative domain. The final result will be a clear and organized notebook showing our code, explanations, and visuals.

## Frequency Analysis Insights
The frequency analysis of all the different sentiments provide a very helpful insight inside the nature of the poems. The poems which caused negative sentiment had words usually associated with negative emotions while poems with positive sentiment impacts had words usually associated with positive emotions. Likewise, poems which had no impact contains neutral words while poems which had mixed impact contained text with both positive and negative vocabulary. Examples in negative sentiment containing poems are words like heavy, no, and torture. Likewise, positive sentiment containing poems contain words like sweet, calm, love, brave, honour, and perfect. No sentiment change contains words like shall, three, little, and down, while mixed emotion poems contain words like death, bright, heaven, love, rich, and sigurd.

## Word Cloud Comparison
There were some commanlites and some differences in the word clouds for the differnt categories. The main commonalities between the word clouds is that their top words used are single words and not phrases and the majority of elements feature single words. The main difference between these word clouds are the number of phrases that appear in them, with Category 1 having the highest number of phrases, Category 2 coming in after that, and Category 3 and Category 0 tied at the lowest with no phrases in the word clouds.

## Insights
Insights from the analysis reveal patterns in sentiment-specific word usage and notable differences in bigram frequencies among positive, negative, and mixed sentiment categories. Common words like "love" and "beauty" emerge in positive sentiments, while negative sentiments often feature words like "pain" and "darkness." Mixed sentiments exhibit a blend of both positive and negative terms.

One other thing that could be used to make the coding part easier and the results more accurate is 'nltk' library. This contains functions which would let us make the process more efficient and reduce the amount of coding to be done. To further improve results, one could explore more advanced techniques such as lemmatization to reduce words to their base forms, potentially capturing nuanced sentiment variations. Additionally, exploring n-grams beyond bigrams and considering the context of phrases could enhance the understanding of sentiment expression. Fine-tuning the list of redundant words and stop words based on the specific characteristics of poetry could also refine the analysis. Lastly, incorporating sentiment lexicons or training a sentiment classifier on poetry data could provide more nuanced sentiment scores for each verse.
