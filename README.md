# Scraping NFT data via Python

The Jupyter Notebook file Scraping NFT.ipynb allows to realize the scraping of NFT data from Cryptoslam.io. The scraping was realized through the library Beautiful Soup. In the code there are three blocks: the first one identifies the top 250 NFT (the selection can be expanded to more NFT), the second one downloads the data of the ETH/USD exchange rate, the third one downloads a number of NFT datasets according to the specified range. The downloaded ETH/USD column is added to the datasets.

The Union Datasets.xml file is related to the XML code implemented in RapidMiner useful for merging all NFT datasets into one Excel file with the only common variables.

The built dataset can be displayed in Dataset NFT.xlsx. Data from NFTs were included from the day they were placed on the market until 22 August 2022.
