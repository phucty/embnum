Evaluation Datasets for Numerical Semantic Labeling
======================

The datasets are used in the paper “EmbNum: Semantic labeling for numerical values using deep metric learning.” This paper aims to provide a neural numerical embedding model to learn a similarity metric for numerical attributes. 

### Contact
Phuc Nguyen -  phucnt@nii.ac.jp

There are four datasets: City Data [1], Open Data, DBpedia Numerical Knowledge Base (NKB), and Wikidata NKB.

### City Data [1]: 
City Data contain n source files; each source has m numerical attributes. The first line of a source file is a number of numerical attributes. The next two lines are the semantic label and m number of values of the first numerical attributes. The next m lines are values the numerical attributes where the first value of the line is number character of the numerical values.  The next lines are the information of the next numerical attributes.

City Data has 30 numerical properties extracted from the city class in DBpedia. The dataset contains ten source files; each source has 30 numerical attributes associated with 30 data properties. 

### Open-Data:
Open Data have the same structure as the City Data. 
In the Open-Data, file “data.csv” contains the information of each numerical attributes with:
- source data id: Where the numerical attributes were assigned
- semantic labels: The semantic labels of numerical attributes
- table id: The id of tables in Open Data Portals (The table data can be assessed by Portal API through table id)
- column index: The numerical column index in the table id

The dataset has 50 numerical properties extracted from the tables in five Open Data Portals i.e., Ireland data.gov.ie), the UK (data.gov.uk), the EU (data.europa.eu), Canada (open.canada.ca), and Australia (data.gov.au). 

### DBpedia NKB
DBpedia NKB contains 206 files where each file contained the numerical values of a correspoding semantic labels. These semantic labels are extracted from the most frequently used numerical properties of DBpedia. 


### Wikidata NKB:
Wikidata NKB contains 169 files where each file contained the numerical values of a correspoding semantic labels. These semantic labels are extracted from the most frequently used numerical properties of Wikidata. 

### Reference
[1] Ramnandan, S.K., Mittal, A., Knoblock, C.A., Szekely, P.: Assigning semantic labels to data sources. In: European Semantic Web Conference. pp. 403–417. Springer (2015)
