# Natural_Language_Processing



# Positive & Negative Song Lyrics Using LSTM and GPT  

## Project Overview  
This project analyzes song lyrics to classify them into positive and negative sentiments using LSTM (Long Short-Term Memory) and GPT (Generative Pre-trained Transformer) models. It involves generating new song lyrics and evaluating their sentiment through advanced NLP (Natural Language Processing) techniques.  

## Features  
- Sentiment analysis of song lyrics (positive or negative) using LSTM.  
- Generation of song lyrics tailored to specific moods with GPT.  
- Cosine similarity analysis to measure closeness between real and generated lyrics.  
- Visualization of dataset statistics, generated content, and similarity results.  
- Use of LyricsGeniusAPI for real-time lyric scraping.  

## Dataset  
The dataset consists of real song lyrics categorized as either positive or negative. Additional generated datasets are created using GPT models, allowing for a comparative analysis of the results.  

## Tools & Libraries  
- **Frameworks**: Python, TensorFlow, PyTorch  
- **APIs**: LyricsGeniusAPI  
- **Libraries**:  
  - Sentiment Analysis: VADER  
  - Modeling: LSTM, GPT  
  - Visualization: Matplotlib, Seaborn  

## Key Visualizations  
1. **Song Lyrics Dataset Distribution**: Shows the count of positive and negative lyrics in the dataset.  
2. **Generated Song Dataset Comparison**: Highlights differences in sentiment distribution between real and generated songs.  
3. **Cosine Similarity**:  
   - Real vs Generated (LSTM)  
   - Real vs Generated (GPT)  

## Results  
- **Sentiment Analysis**: Successful classification of lyrics into positive and negative moods.  
- **Lyric Generation**: GPT effectively generated lyrics reflecting the desired sentiment.  
- **Cosine Similarity Analysis**: Evaluated the similarity between real lyrics and those generated by LSTM and GPT, demonstrating the capabilities of GPT in producing semantically close text.  

## Getting Started  
### Prerequisites  
Ensure you have the following installed:  
- Python 3.7+  
- TensorFlow, PyTorch  
- LyricsGeniusAPI (for scraping lyrics)  
- Required libraries: `numpy`, `matplotlib`, `seaborn`, `transformers`, `vaderSentiment`  

### Installation  
Clone this repository:  
```bash  
git clone https://github.com/sukumar2403/NLP_Positive-Negative-Song-Lyrics-Using-LSTM-And-GPT.git  
```  
Install dependencies:  
```bash  
pip install -r requirements.txt  
```  

### Usage  
1. **Dataset Preparation**:  
   Run the script to scrape and preprocess song lyrics using LyricsGeniusAPI.  

2. **Train Models**:  
   - Train the LSTM model for sentiment classification.  
   - Fine-tune GPT for sentiment-based lyric generation.  

3. **Run Analysis**:  
   Generate and evaluate song lyrics using the provided scripts.  

4. **Visualize Results**:  
   View the plots for sentiment distribution and cosine similarity.  

## Project Structure  
```
NLP_Positive-Negative-Song-Lyrics-Using-LSTM-And-GPT/  
│  
├── Complete.csv                      # Complete dataset of song lyrics  
├── negative.csv                      # Dataset containing negative song lyrics  
├── positive.csv                      # Dataset containing positive song lyrics  
├── Project-Data prep.ipynb           # Jupyter notebook for data preprocessing  
├── project_analysis_and_generation_gpt.py  
│                                      # Script for analyzing and generating lyrics with GPT  
├── DSCI6004-Project_final_presentation.pptx  
│                                      # Final project presentation  
├── Positive & Negative Song Lyrics Using LSTM And GPT.pdf  
│                                      # Project documentation and report  
├── README.md                          # Project overview and instructions  
  
```  

## Contributors  
- **[Sukumar](https://github.com/sukumar2403)**  
- Ayyappa Tata  
- Dr. Khaled Sayed (Project Advisor)  

## License  
This project is licensed under the MIT License.  

