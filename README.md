# DM6190_Coursework



### Environment Set-up

```bash
git clone https://github.com/erichhhhho/DM6190_Courswork/
cd DM6190_Courswork
conda env create environment.yml
source activate dlproject
```

### Download dataset

1. Install [kaggle API](https://github.com/Kaggle/kaggle-api): `pip install kaggle`
3. Create API token from `https://www.kaggle.com/<username>/account` and save the file to `~/.kaggle/kaggle.json` 
4. Download the Carvana dataset: `kaggle competitions download -c carvana-image-masking-challenge`
5. Unzip the dataset into to `train.csv` `valid.csv` `test.csv`
  
### Running the crawler

```bash
cd crawler
scrapy crawl cars
```
