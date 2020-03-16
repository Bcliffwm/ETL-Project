The original data for this project were scraped from a dataset on homelessness in the U.S. from kaggle.com and from a dataset on
substance abuse by geographic region from the Substance Abuse and Mental Health Administration (SAMHSA) website. The format for both
datasets were in CSV. The SAMHSA datasets were broken down into their own separate files since the entire zip carried extraneous data
and the individual files needed to have UTF-8 encoding. 

The datasets were primarily cleaned using Microsoft Excel to remove extraneous headers. Once the data was read into a Jupyter
notebook using Pandas, extraneous columns were removed and column titles were renamed for ease of manipulation. 

The cleaned DataFrames were then loaded into a PostgreSQL database using Pandas and SQLAlchemy. Subsequent queries confirmed that the data
were successfully loaded into the database. This project was an attempt to utilize data to better understand homeless demographics in the
U.S. and the impact substances have on the welfare of the homeless. 
