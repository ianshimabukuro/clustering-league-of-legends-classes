# League of Legends Champion Stats Analysis

This project uses Python and Jupyter to scrape, clean, and analyze base statistics of League of Legends champions from the [LoL Wiki](https://leagueoflegends.fandom.com/wiki/List_of_champions/Base_statistics). It also applies basic machine learning and visualization techniques to explore the data.

---

## Workflow

1. **Scraping**  
   - Uses `requests` and `BeautifulSoup` to extract champion base stats from the wiki.  
   - Function: `extract_champion_stats()`  

2. **Data Formatting**  
   - Cleans numeric values (removes `+`, `%`, spaces).  
   - Extracts champion names and prepares numerical arrays.  
   - Function: `format_data(data)`.  

3. **Exploration & Visualization**  
   - Uses `matplotlib` and `seaborn` for plots.  
   - Computes similarity, distance metrics, and confusion matrices.  

4. **Machine Learning**  
   - Applies clustering/classification using `scikit-learn`.  
   - Example: synthetic datasets with `make_blobs`.  
   - Evaluates performance with confusion matrices.  

---

## Requirements

Install the necessary packages:

```bash
pip install requests beautifulsoup4 torch scikit-learn matplotlib seaborn
