# 14th Gen Intel Sentiment Analysis

## Project Overview
This project analyzes customer sentiment for Intel’s 14th generation processors based on customer reviews from various sources. The objective is to extract actionable insights that can help guide product development and marketing strategies.

## Problem Statement
The computing technology has advanced significantly with the introduction of Intel’s 14th generation processors, promising better performance and efficiency. Understanding customer sentiment is key to improving these products and maintaining a competitive edge in the market. This project performs sentiment analysis on customer reviews to identify strengths, weaknesses, and areas for improvement.

## Datasets
The project uses customer reviews of various Intel 14th Gen processors. The datasets include reviews for:
- Intel® Core™ i9-14900K
- Intel® Core™ i9-14900KS
- Intel® Core™ i7-14700K
- Intel® Core™ i5-14500
- Intel® Core™ i3-14100
- And more...

The datasets are located in the `datasets/` directory in CSV format.

## Project Components
1. **Data Preprocessing**: The data was cleaned, translated (if necessary), and prepared for analysis.
2. **Sentiment Analysis**: Using VADER and TextBlob libraries, the reviews were analyzed to extract sentiment scores.
3. **Visualization**: Graphs and word clouds were generated to understand the distribution of sentiment across time and product variants.
4. **Topic Modeling**: Latent Dirichlet Allocation (LDA) was applied to uncover key topics discussed in the reviews.

## Files
- **14th_Gen_Intel_sentiment_analysis.ipynb**: The main Jupyter notebook containing all the code for data processing, sentiment analysis, and visualizations.
- **14th_Gen_Intel_sentiment_analysis.pdf**: The report summarizing the findings and conclusions of the sentiment analysis.
- **datasets/**: The folder containing CSV files for each product's customer reviews.
  
## How to Run the Project
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/14th-gen-intel-sentiment-analysis.git
    ```
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter notebook:
    ```bash
    jupyter notebook 14th_Gen_Intel_sentiment_analysis.ipynb
    ```

## Requirements
Ensure that you have the following libraries installed. You can install them via the `requirements.txt` file.

## Visualizations
This project includes several visualizations to understand the sentiment distribution, including:
- Word clouds for positive, neutral, and negative reviews
- Time series of sentiment scores over time
- Distribution of sentiment by language and country

## Conclusion
This analysis provides a nuanced understanding of customer sentiment around Intel’s 14th generation processors, highlighting areas of strength and potential improvement. By focusing on performance, power consumption, and price, Intel can continue to improve its offerings and increase customer satisfaction.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For more information or questions, feel free to reach out to `alencheryalex@gmail.com`.
