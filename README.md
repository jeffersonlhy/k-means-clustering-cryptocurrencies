# Cryptocurrency Clusters

## Problem Statement

Unlike traditional finance, within the sea of cryptocurrencies, one may find it hard to understand and determine which tokens have similar properties or price movement. There are lots of crypto funds established in recent years that endeavored to create crypto analysis report regularly for their clients to offer better insights on their portfolio. Therefore, this project aims to try perform clustering on the major tokens in the market with PCA, K-Means Clustering along with some visualization tools. 

Obviously there are ample ways to group the tokens and this repository attempts this clustering problem with two approaches, 1) Market Movement and 2) Token Properties. 

## Data Collection

- The data is collected from CoinGecko API and transformed into `.csv`. 

## Findings

- In the token properties approach, `4` groups is the optimal value.
- In the market movement approach, `6` groups is the most optimal value.


## Recommenations 
- There are more attributes of a token that can be factor into the clustering model. For exmaple, the number of twitter followers, the reddit thread number and the years of launch. These could also be important market signals that reflects how the public respond to the tokens. 
