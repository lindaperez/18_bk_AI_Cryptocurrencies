# _ Data Science: Cryptocurrency Grouping Project _

## The situation: 
This report includes information on which cryptocurrencies are currently available on the trading market and how they can be grouped to create a classification system for an investment portfolio based on its features and values using Machine Learning, Statistics and Data Analysis techniques like Unsupervised Learning, K-means algorithm and Principal Component Analysis.

### The Data

<b> CoinName:</b> refers to the name of the cryptocurrency. Each cryptocurrency is identified by a unique name that distinguishes it from other cryptocurrencies. <br/>
<b>Algorithm:</b> refers to the computational method used to secure the cryptocurrency network and validate transactions. Different cryptocurrencies use different algorithms, such as SHA-256, Scrypt, Ethash, X11, and others.<br/>
<b>IsTrading:</b> is a binary attribute that indicates whether the cryptocurrency is currently being traded on a cryptocurrency exchange or not. If the value is "true," it means the cryptocurrency is actively being traded, while if it is "false," it means the cryptocurrency is not being traded at the moment.<br/>
<b>ProofType:</b> refers to the consensus algorithm used to verify transactions on the blockchain. There are several types of consensus algorithms, such as Proof of Work (PoW), Proof of Stake (PoS), Proof of Capacity (PoC), and others.<br/>
<b>TotalCoinsMined:</b> refers to the total number of coins that have been mined or created for a particular cryptocurrency. It is a measure of the total supply of the cryptocurrency that has been generated since its inception.<br/>
<b>TotalCoinSupply:</b> refers to the maximum number of coins that will ever be created for a particular cryptocurrency. It is a measure of the maximum supply of the cryptocurrency that will be available in circulation. Some cryptocurrencies have a fixed total coin supply, while others have a variable supply that changes over time.

Steps to classify the cryptocurrencies:

- Preprocessing the Data for Principal Component Analysis (PCA)
 * Keep traded cryptocurrencies. 
 * Keep cryptocurrencies with particular features populated like Algorithm.
 * Keep rows where coins are mined, TotalCoinsMined. 
 
- Standarize the Data with StandardScaler
- Reducing Data Dimensions Using PCA
- Intepreting the explained_variance_ratio_ from the PCA 
- Clustering Cryptocurrencies Using K-means to group the data
- Finding the Best Value for K-means using the Elbow Curve
- Identify the shape of the clustered
- Visualizing Cryptocurrency Results
- Show total number of tradable cryptocurrencies.


The table shows the features used to generate the classification.
  
 <img width="869" alt="Screen Shot 2022-06-10 at 9 17 13 PM" src="https://user-images.githubusercontent.com/1729991/173172187-420d5cad-1b8a-49e5-83a2-d53cc9367f7d.png">

 The diagram shows how cryptocurrencies can be group in four groups. 

<img width="826" alt="Screen Shot 2022-06-10 at 9 02 51 PM" src="https://user-images.githubusercontent.com/1729991/173171796-7c762217-ad04-421b-b5de-82a1339752b7.png">



