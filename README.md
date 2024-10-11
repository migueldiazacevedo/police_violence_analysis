# Police Violence in the United States

## Project Overview

Police brutality is a significant issue in the United States, with numerous incidents documented annually. This exploratory data analysis focuses on fatal police shootings using data collected by [The Washington Post](https://github.com/washingtonpost/data-police-shootings). The analysis aims to uncover trends, explore the racial dynamics of police violence, and investigate the geographical and temporal aspects of these incidents.

## Project File

- __police_violence.ipynb:__ The main Jupyter notebook that contains the exploratory data analysis (EDA). This notebook contains a step-by-step examination of the dataset, data preprocessing, and the application of various data analysis and plotting techniques. <br><br>
note:<br>several of the plots in this notebook are interactive so in order to explore those plots, I recommend running the notebook on your own computer with using the requirements defined in requirements.txt

### Questions Explored

1. Is there a racial bias in police violence?
2. What conditions contribute to racial disparities in police shootings?
3. Where in the USA does police violence occur?
4. How has police violence changed from 2015 to 2023?

## Conclusions and Open Questions

The analysis highlights trends in racial disparities, geographical hotspots, and temporal changes in police violence. Open questions include the increase in 'Unknown' race categories, reporting discrepancies, and the absence of specific cases.

### Future Directions

- Compare datasets with [Mapping Police Violence](https://mappingpoliceviolence.org/).
- Normalize race statistics based on population representation.
- Conduct deeper analyses using advanced tools like Plotly, Geopandas, and Folium.
- Address technical issues, such as the Folium map bug for 2023 and potential optimizations for Seaborn's FacetGrid.

## Dependencies

- python>=3.10.13
- folium==0.15.1
- geopandas==0.14.1
- ipywidgets>=8.0.4
- matplotlib>=3.8.0
- nbformat>=4.2.0
- numpy>=1.26.2
- pandas>=2.1.4
- plotly>=5.18.0
- scipy>=1.11.4
- seaborn>=0.13.0
- ipython>=8.28.0

### Getting Started

Create a virtual environment using the requirements.txt file provided<br>
For example:

```bash
python3 -m venv police_violence/
# activate the venv and install all requirements provided 
source police_violence/bin/activate
pip install -r requirements.txt
```

### Acknowledgments

- The Washington Post for providing the [Fatal Force Database](https://github.com/washingtonpost/data-police-shootings).
- [Mapping Police Violence](https://mappingpoliceviolence.org/) for dataset comparison.

### Author

- Miguel A. Diaz-Acevedo
<migueldiazacevedo@gmail.com>

### License

[MIT](https://opensource.org/license/mit)
