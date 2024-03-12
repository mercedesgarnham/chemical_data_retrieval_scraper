# chemical_data_retrieval_scraper
This notebook aims to facilitate the retrieval and visualization of chemical data from PubChem. It provides functionalities to extract information about the commercial availability of compounds and generate visual representations of molecular structures.

## Functions Overview:
1. search_commercial_availability_pubchem(df):

- This function retrieves commercial availability information for compounds based on their SMILES representations using PubChem API.
- It takes a DataFrame df containing SMILES strings of compounds as input and adds a new column indicating commercial availability.

2. chemical_vendors_links_pubchem(df):

- This function retrieves links to chemical vendors for compounds using PubChem API.
- It takes a DataFrame df containing SMILES strings of compounds as input and adds a new column containing URLs to chemical vendors.

## Workflow:
1. Data Retrieval from PubChem:

- The notebook begins with the extraction of chemical data from PubChem using the search_commercial_availability_pubchem() and chemical_vendors_links_pubchem() functions.

2. DataFrame Generation:

- Once the data is retrieved, a DataFrame is created containing the chemical information, including SMILES representations of compounds.

3. Molecule Visualization:

- The notebook utilizes RDKit to convert the SMILES representations into molecular structures and generate visual representations (images) of the molecules.

4. Data Export:

- Finally, the notebook saves the DataFrame with additional information and molecule images into an Excel file for further analysis or sharing.


By following this notebook, users can efficiently retrieve chemical data from PubChem, visualize molecular structures, and organize the information for downstream analysis.
