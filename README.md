**Web3 Trading Team - Trader Behavior vs Market Sentiment Analysis**

**Project Overview**

This project analyzes the relationship between trader behavior and market sentiment using historical trading data from Hyperliquid and Bitcoin Fear & Greed Index. The goal is to identify patterns and insights that could inform smarter trading strategies in the Web3 space.

**Key Achievement**: Identified that contrarian trading strategies outperform momentum strategies by 133.6% in average returns, with extreme market sentiment periods presenting unique trading opportunities.


**Quick Start**

**Prerequisites**
- Python 3.8+
- Google Colab account 
- Git installed (for cloning)

**Setup Instructions**

1. **Clone Repository**
   -git clone https://github.com/<your-username>/ds_<candidate_name>.git
   -cd ds_<candidate_name>
2. **Download Required Data** 
   -Historical Trading Data 
   -Fear & Greed Index Data 
         
-Place both CSV files in the root directory of the project.  

3. **Open in Google Colab** 
   -Upload notebook_1.ipynb and notebook_2.ipynb to Google Colab
   -Upload the downloaded CSV files to Colab session storage
   -Run cells sequentially
**Running Locally** 

    **Install Dependencies** 
      -pip install pandas numpy matplotlib seaborn scipy scikit-learn plotly
    **Create Required Directories**
      -mkdir -p csv_files outputs
    **Launch Jupyter**
      -Jupyter notebook
**Key Findings**

**Trading Strategy Insights** 

     -1.Contrarian strategies outperform momentum: $71.59 vs $30.64 average PnL per trade
     -2.Extreme Greed periods show the highest returns ($67.89/trade) and win rates (89.17%)
     -3.Elite traders (87.5% of total) maintain consistent profitability with high win rates
     

**Market Sentiment Impact** 

     -Best performing sentiment: Extreme Greed (Avg PnL: $67.89)
     -Highest volume periods: Fear ($483.3M total volume)
     -Lowest volume periods: Extreme Fear ($98.4M total volume)
     

**Strategic Recommendations** 

    -Implement contrarian approaches during extreme sentiment periods 
    -Scale position sizes based on sentiment phases 
    -Use sentiment shifts as entry/exit signals 
    -Adjust leverage dynamically during sentiment transitions 

**File Descriptions**
**Notebooks**
    -[notebook_1.ipynb](https://colab.research.google.com/drive/1R3_83BPxzTn-g4_HT49t9z6pJkZJ1bqY?usp=sharing): 
      -Complete analysis pipeline including: 
      -Data loading and preprocessing
      -Exploratory data analysis
      -Trader performance segmentation
      -Sentiment integration and correlation analysis
      -Pattern discovery and strategy recommendations
    -[notebook_2.ipynb](https://colab.research.google.com/drive/1tWLw961rpg9X-MpEt1qjjNMq6L3ARNpL?usp=sharing): 
      -Focused Fear & Greed Index analysis: 
      -Sentiment distribution analysis
      -Trader behavior by sentiment periods
      -Advanced pattern recognition
      -Visualization generation
**Data Files**
     -[historical_data.csv](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing): Raw trading data (211,224 records)
        -Columns: Account, Coin, Execution Price, Size, Side, PnL, etc.
      -[fear_greed_index.csv](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing): Sentiment data (2,644 records)
        -Columns: timestamp, value, classification, date
**Output Files** 

     -csv_files/: Processed analysis results
     -outputs/: 8 visualization files (PNG format)
     -ds_report.pdf: Comprehensive analysis summary
**Technical Stack** 

     -Data Processing: pandas, numpy
     -Visualization: matplotlib, seaborn, plotly
     -Statistical Analysis: scipy, scikit-learn
     -Environment: Google Colab / Jupyter Notebook
     
**Analysis Pipeline** 

    **Data Loading & Cleaning**
         -Parse timestamps and handle missing values
         -Standardize data formats across datasets
          

    **Feature Engineering**
         -Create trade size categories
         -Calculate trader performance metrics
         -Classify trading styles (Contrarian vs Momentum)
          

    **sentiment Integration**
         -Merge trading data with Fear & Greed Index
         -Analyze behavior patterns by sentiment periods
          

    **Pattern Discovery** 
         -Identify profitable trading strategies
         -Segment traders by performance
         -Generate actionable insights
          

**Project Highlights** 

     -Analyzed: 211,224 trades across 480 trading days
     -Identified: 32 unique traders trading 246 different cryptocurrencies
     -Total Volume: $1.19 billion in trading activity
     -Net Profitability: $10.3 million in combined PnL
     -Win Rate: 83.2% overall trading success rate
     

**Contact & Support** 

-For questions about this analysis or to discuss findings: 

     -Email:jayasreeselvam37@gmail.com
     -[GitHub](https://github.com/Jayashree1743)
     -[LinkedIn]:(www.linkedin.com/in/jayasree-selvam-36b24a258)
**License**

    -This project is submitted as part of the Web3 Trading Team data science application. All analysis is for demonstration purposes only.

**Note**: This analysis was completed as part of a job application for the Web3 Trading Team. The findings demonstrate advanced data science capabilities in cryptocurrency trading analysis and sentiment-based strategy development.
     
     

         
              
     
