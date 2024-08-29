# PTM Site Prediction Preprocessing

This repository contains detailed preprocessing steps for datasets on post-translational modification (PTM) sites in proteins, making them ready for deep learning applications and other analytical uses. The goal is to enhance the prediction accuracy of PTM sites through meticulous data preparation and integration of genomic and proteomic data.

## Project Overview

The project focuses on the critical preprocessing of datasets related to PTM sites, ensuring the data is clean, integrated, and formatted correctly for use in predictive modeling. It includes extraction of unique chemical names, mapping of gene names to UniProt IDs, and serialization of processed data for easy access and use in machine learning workflows.

### Source Data

Detailed data sources will be provided [here](https://doi.org/10.1126/science.ade3925).

## Repository Structure

- `assets/`: Contains resources such as the gene name to UniProt ID conversion dictionary used in the code.
- `scripts/`: Contains the Jupyter notebook `decrypt_processing.ipynb` detailing all preprocessing steps.
- `README.md`: Provides an overview of the project, its objectives, and how to use the resources.

## Key Features

- **Data Cleaning and Standardization**: Ensures the cleanliness and uniformity of the data.
- **Chemical and Gene Name Processing**: Extracts and utilizes unique chemical and gene names for further analysis.
- **Data Serialization**: Converts processed data into a format suitable for machine learning models.

## How to Use

1. Clone this repository to your local machine.
2. Ensure all dependencies are installed as specified in the notebook.
3. Run the `decrypt_processing.ipynb` notebook to reproduce the preprocessing steps.
4. Use the serialized data for your specific applications, especially in predictive modeling of PTM sites.

## Dependencies

- Python 3
- Pandas
- NumPy
- Pickle
- Other necessary libraries as specified within the notebook.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE_LINK) file for details.

## Contact

For questions, contributions, or further information, please contact the repository maintainer.
