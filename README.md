# "Centralized or Decentralized?": Concerns and Value Judgents of Stakeholders in the Non-Fungible Tokens (NFTs) Market

## *Supplementary resources, data, and code*
by **Author names**

(* *corresponding authors*)

# Table of Contents
## Data
### [Collected Data(tweets)](https://github.com/PlevanTem/NFT-cscw-2023/tree/main/data)
| **File Name** | **Data Category** | **Discription** |
|--|--|--|
|NFT trust.csv, NFT transparent.csv, NFT transparency.csv, NFT racism.csv, NFT morality.csv, NFT moral.csv, NFT inclusivity.csv, NFT inclusive.csv, NFT fairness.csv, NFT ethics.csv, NFT ethical.csv, NFT equity.csv, NFT equality.csv, NFT diversity.csv, NFT diverse.csv, NFT discrimination.csv, NFT bias.csv|Social Media Data|All NFT-related tweets searched by keyword|
|df_kol.csv|Social Media Data|Dataset of NFT-related tweets collected from detected Key Opinion Leaders(KOLs)|

### [Analyzed Data](https://github.com/PlevanTem/NFT-cscw-2023/tree/main/tweets)
| **File Name** | **Discription** | **Section of Paper** |
|--|--|--|
|df_all_tweets.txt|Preprocessed Dataset of all tweets collected by keyword|3.1 Data collection|
|words.txt|Preprocessed tokens of tweets collected|4.1.1 Top Words and bigrams|
|df_kol_clean.csv|Dataset of preprocessed NFT-related tweets from detected KOLs|3.1.2 Data Analysis|
|nftnx.gephi|Network of collected NFT-related Twitter accounts|4.1.2 NFT Opinion Leaders on Twitter|
|df_top20_kol.csv|The tweets and Twitter-related statitics of top 20 KOLs by centrality score measured in Gephi|4.1.2 NFT Opinion Leaders on Twitter|
|thematic analysis of NFT KOL and  public tweets.xlsx|Codebook of thematic analysis|4.2 Qualitative Findings from Twitter Analysis|

## [Code](https://github.com/PlevanTem/NFT-cscw-2023/tree/main/code)
| **File Name** | **Section of Paper** | **Url** |
|--|--|--|
|scrape.ipynb|3.1.1 Data Collection |https://github.com/PlevanTem/NFT-cscw-2023/blob/main/code/scrape.ipynb|
|analyze.ipynb|3.1.2 Data Analysis |https://github.com/PlevanTem/NFT-cscw-2023/blob/main/code/analyze.ipynb|

## Data Visualization
Fig. 1. A: The most frequent 50 words in NFT ethics related tweets; B: Top keyword network of NFT Trust-group.
![The most frequent 50 words in NFT ethics related tweets; B: Top keyword network of NFT Trust-group.](https://github.com/PlevanTem/NFT-cscw-2023/blob/main/graphs%20%26%20figures/frequencyofWords.png)

Fig. 2. Network Visualization: Opinion Leaders in NFT Marketplace. Label size reflects eigenvector centrality. Node size reflects
follower count. Node colors represent detected communities
![Network Visualization: Opinion Leaders in NFT Marketplace.](https://github.com/PlevanTem/NFT-cscw-2023/blob/main/graphs%20%26%20figures/NFTnetwork_generatedByGephi_ForceAtlas_labelbyPhotoShop.png)
