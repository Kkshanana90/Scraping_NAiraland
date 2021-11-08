# Scraping_Nairaland
This project scraped comments from the political section of popular Nigerian blog www.nairaland.com using the Python BeautifulSoup library, and saved the extracted comments and links in a CSV file.

# Create a new environment and install the requirements files
Create a new Anaconda environment with Python 3.8( Other Python versions could also be used), and pip install the required librairies using: 
pip install -r Requirements.txt

# Run the Nairaland_pol_section.py file using:
python Nairaland_pol_section.py

# Saved CSV File 
The generated CSV file would be saved as 'Nairaland_df.csv'

# Read file. 
To read the generated 'Nairaland_df.csv' file in Jupyter Notebook, Google Colab, etc; you may want to replace 'Nairaland_df.csv' with own path in:
full_data= pd.read_csv('Nairaland_df.csv',lineterminator='\n')

# Number of Comments
The script only extracts all comments in the first 10 pages as shown in "for i in range(0,10):" from Nairaland_pol_section.py. This could be modified.

# Possible Use
A sentiment analysis could be performed on the extracted comments.

