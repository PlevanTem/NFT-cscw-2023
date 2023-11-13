# Centralized or Decentralized?: Concerns and Value Judgments of Stakeholders in the Non-Fungible Tokens (NFTs) Market

## Supplementary Resources, Data, and Code

### Description
This repository contains supplementary resources, data, and code related to the research project "Centralized or Decentralized?: Concerns and Value Judgments of Stakeholders in the Non-Fungible Tokens (NFTs) Market." The project explores various aspects of the NFT market, including social media data, data analysis, and data visualization. It is authored by Yunpeng Xiao, Bufan Deng, Siqi Chen, Kyrie Zhixuan Zhou, RAY LC, Luyao Zhang*, and Xin Tong*, with corresponding authors marked with an asterisk. 


> Our datasets, metadata information, and data dictionary are open access on Harvard Dataverse.
> 
> *Xiao, Yunpeng; Deng, Bufan; Chen, Siqi; Zhou, Kyrie Zhixuan; LC, RAY; Zhang, Luyao; Tong, Xin, 2023, "Replication Data for: "Centralized or Decentralized?": Concerns and Value Judgments of Stakeholders in the Non-Fungible Tokens (NFTs) Market." [https://doi.org/10.7910/DVN/GLFUPA](https://doi.org/10.7910/DVN/GLFUPA). Harvard Dataverse, V1.*


### Table of Contents
- [Data](#data)
  - [Collected Data (tweets)](https://github.com/PlevanTem/NFT-cscw-2023/tree/main/data)
    - [File Name](#file-name) | [Data Category](#data-category) | [Description](#description)
  - [Analyzed Data](https://github.com/PlevanTem/NFT-cscw-2023/tree/main/tweets)
    - [File Name](#file-name) | [Description](#description) | [Section of Paper](#section-of-paper)
- [Code](https://github.com/PlevanTem/NFT-cscw-2023/tree/main/code)
  - [File Name](#file-name) | [Section of Paper](#section-of-paper) | [URL](#url)
- [Data Visualization](#data-visualization)

### Data

#### Collected Data (tweets)
- [Collected Data (tweets)](https://github.com/PlevanTem/NFT-cscw-2023/tree/main/data)

| **File Name** | **Data Category** | **Description** |
|---------------|-------------------|-----------------|
| NFT trust.csv, NFT transparent.csv, NFT transparency.csv, NFT racism.csv, NFT morality.csv, NFT moral.csv, NFT inclusivity.csv, NFT inclusive.csv, NFT fairness.csv, NFT ethics.csv, NFT ethical.csv, NFT equity.csv, NFT equality.csv, NFT diversity.csv, NFT diverse.csv, NFT discrimination.csv, NFT bias.csv | Social Media Data | All NFT-related tweets searched by keyword |
| df_kol.csv | Social Media Data | Dataset of NFT-related tweets collected from detected Key Opinion Leaders (KOLs) |

#### Analyzed Data
- [Analyzed Data](https://github.com/PlevanTem/NFT-cscw-2023/tree/main/tweets)

| **File Name** | **Description** | **Section of Paper** |
|---------------|-----------------|----------------------|
| df_all_tweets.txt | Preprocessed Dataset of all tweets collected by keyword | 3.1 Data collection |
| words.txt | Preprocessed tokens of tweets collected | 4.1.1 Top Words and bigrams |
| df_kol_clean.csv | Dataset of preprocessed NFT-related tweets from detected KOLs | 3.1.2 Data Analysis |
| nftnx.gephi | Network of collected NFT-related Twitter accounts | 4.1.2 NFT Opinion Leaders on Twitter |
| df_top20_kol.csv | The tweets and Twitter-related statistics of top 20 KOLs by centrality score measured in Gephi | 4.1.2 NFT Opinion Leaders on Twitter |
| thematic analysis of NFT KOL and public tweets.xlsx | Codebook of thematic analysis | 4.2 Qualitative Findings from Twitter Analysis |

### Code
- [Code](https://github.com/PlevanTem/NFT-cscw-2023/tree/main/code)

| **File Name** | **Section of Paper** | **URL** |
|---------------|----------------------|---------|
| scrape.ipynb | 3.1.1 Data Collection | [Code Link](https://github.com/PlevanTem/NFT-cscw-2023/blob/main/code/scrape.ipynb) |
| analyze.ipynb | 3.1.2 Data Analysis | [Code Link](https://github.com/PlevanTem/NFT-cscw-2023/blob/main/code/analyze.ipynb) |

### Data Visualization
- Fig. 1. A: The most frequent 50 words in NFT ethics-related tweets; B: Top keyword network of NFT Trust group.
![The most frequent 50 words in NFT ethics related tweets; B: Top keyword network of NFT Trust-group.](https://github.com/PlevanTem/NFT-cscw-2023/blob/main/graphs%20%26%20figures/frequencyofWords.png)

- Fig. 2. Network Visualization: Opinion Leaders in NFT Marketplace. Label size reflects eigenvector centrality. Node size reflects follower count. Node colors represent detected communities.
![Network Visualization: Opinion Leaders in NFT Marketplace.](https://github.com/PlevanTem/NFT-cscw-2023/blob/main/graphs%20%26%20figures/NFTnetwork_generatedByGephi_ForceAtlas_labelbyPhotoShop.png)

- Fig. S1. Top 20 topics of thematic analysis from KOLs (visualized based on [thematic codebook](https://github.com/PlevanTem/NFT-cscw-2023/blob/main/randomized/thematic%20analysis%20of%20NFT%20KOL%20and%20%20public%20tweets.xlsx)).
![Top 20 topics of thematic analysis from KOLs.](https://github.com/PlevanTem/NFT-cscw-2023/blob/main/graphs%20%26%20figures/Top%2020%20topics%20of%20themetic%20analysis%20from%20KOLs.png)

- Fig. S2. Top 20 topics of thematic analysis from ordinary users (visualized based on [thematic codebook](https://github.com/PlevanTem/NFT-cscw-2023/blob/main/randomized/thematic%20analysis%20of%20NFT%20KOL%20and%20%20public%20tweets.xlsx)).
![Top 20 topics of thematic analysis from ordinary users.](https://github.com/PlevanTem/NFT-cscw-2023/blob/main/graphs%20%26%20figures/Top%2020%20topics%20of%20themetic%20analysis%20from%20ordinary%20users.png)
