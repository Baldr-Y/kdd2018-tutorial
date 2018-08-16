# Sources, descriptions, and citations for data sets

For your convenience, in this repository we provide preprocessed (excerpts) from temporal network data. All data files have been created based on publicly and freely available data sets. In the following, we give detailed source and citation information for these data sets:

| Datafile | Description | Citation | Weblink |
|----------|-------------|----------|---------|
| US_flights.ngram | Contains flight itineraries of American Airlines passengers between US airports. This is an excerpt from the [Airline Origin and Destination Survey (DB1B)](https://www.transtats.bts.gov/Tables.asp?DB_ID=125&DB_Name=Airline%20Origin%20and%20Destination%20Survey%20%28DB1B%29&DB_Short_Name=Origin%20and%20Destination%20Survey). | N/A | [link](https://www.transtats.bts.gov/Fields.asp) |
| tube.edges | Contains direct links between stations in the London Tube Metro Network. This data file was generated based on publicly available Wikipedia data. | N/A | [link]() |
| tube_od.csv | Contains the volume of passengers between origin and destination stations in the London Tube Metro Network. This data set is an excerpt from the Rolling Origin Destination Survey available from the [OpenData page of Transport for London](https://tfl.gov.uk/info-for/open-data-users/our-open-data#on-this-page-9) | N/A | [link](https://tfl.gov.uk/cdn/static/cms/documents/rods-access-mode-2010-sample.csv) |
| temporal_clusters.tedges | Synthetically generated data set | N/A | N/A | 
| toy_paths.ngram | Toy example generated in unit 1.2  | N/A | N/A


In addition to these datafiles, the SQLite database file `temporal_networks.db` contains dynamic social networks stored in the following tables:


| Table name | Description | Citation | Weblink |
|------------|-------------|----------|---------|
| eu_email_dept3 | E-Mail exchanges in one department of a European institution | A Paranjape, AR Benson, J Leskovec: **Motifs in Temporal Networks**, In Proceedings of the Tenth ACM International Conference on Web Search and Data Mining, 2017. | [link](https://snap.stanford.edu/data/email-Eu-core-temporal.html)
| manufacturing_email |  E-Mail exchanges in Polish manufacturing company, prepared and published by [Radoslaw Michalski](https://www.ii.pwr.edu.pl/~michalski/) | R Michalski, S Palus, P Kazienko: **Matching Organizational Structure and Social Network Extracted from Email Communication**, Lecture Notes in Business Information Processing LNBIP, vol. 87, pp. 197-206, Springer, Berlin Heidelberg (2011)  |[link](https://www.ii.pwr.edu.pl/~michalski/index.php?content=datasets) |
| sociopatterns_ho |  Temporal network of contacts between patients and health-care workers in a hospital, collected via the [SocioPatterns project](http://www.sociopatterns.org) |  P Vanhems et al.: **Estimating Potential Infection Transmission Routes in Hospital Wards Using Wearable Proximity Sensors**, PLoS ONE 8(9): e73970 (2013) |[link](http://www.sociopatterns.org/datasets/hospital-ward-dynamic-contact-network/) |
| lotr |  Character co-occurrence within same sentence in the text of the Lord of the Rings Trilogy  | N/A | N/A |

# Accesssing data files

Assuming that you have started Visual Studio Code in the root of the tutorial directory, files in this folder can be referenced from python code via the relative path `data/FILENAME`. If you start a `jupyter` notebook within the `code` folder, you will have to use the relative path `../data/FILENAME`.