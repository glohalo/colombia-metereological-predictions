# Colombia Meteorological Predictions

The objective of this work is to predict solar radiation in the Colombian Caribbean region using artificial neural networks.

## Objective

The primary goal of this research is to develop predictive models for solar radiation in the Colombian Caribbean region. The models use various data analysis techniques and machine learning algorithms, including artificial neural networks.

Please, write me a DM to share the data!

## Repository Structure

The repository is organized into several files and scripts, each serving a specific purpose in the data analysis and modeling workflow. Below is a brief description of each file:

1. **caribbean_region_exploratory_data_analysis**: This notebook contains the exploratory data analysis (EDA) for the Caribbean region. It includes data visualization, summary statistics, and initial insights into the dataset.

2. **bivariate_analysis**: This notebook performs bivariate analysis to explore relationships between different weather variables and solar radiation.

3. **conv_fnn_model**: This script contains the implementation of a Convolutional Feedforward Neural Network (FNN) model for predicting solar radiation.

4. **conv_lstm_model**: This script implements a Convolutional Long Short-Term Memory (LSTM) model for time series prediction of solar radiation.

5. **data_ingestion_and_extraction_weather_variables**: This script handles the data ingestion and extraction process for various weather variables required for the analysis.

6. **data_ingestion_solar_radiation**: This script deals with the data ingestion process specifically for solar radiation data.

7. **fnn_model**: This script contains the implementation of a basic Feedforward Neural Network (FNN) model for solar radiation prediction.

8. **folium_caribe_map**: This notebook uses the Folium library to create an interactive map of the Caribbean region, highlighting key geographical features and data points.

9. **map_colombia_region**: This notebook generates maps of the Colombian region to visualize data distribution and other relevant geographic information.

10. **svr_and_random_forest_modeling**: This script includes the implementation of Support Vector Regression (SVR) and Random Forest models for predicting solar radiation.

## Getting Started

### Prerequisites

To run the scripts and notebooks in this repository, you need to have the following installed:

- Python 3.9 or higher
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- TensorFlow
- Keras
- Folium

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/colombia-meteorological-predictions.git
   cd colombia-meteorological-predictions
   ```

### Usage

1. Run the data ingestion scripts to load and preprocess the data.
2. Use the EDA notebooks to explore and understand the data.
3. Train and evaluate the models using the respective scripts and notebooks.
4. Visualize the results using the mapping notebooks.

## Authors

- [Gloria Carrascal](https://github.com/glohalo)

## License

This project is licensed under the APACHE 2.0 License - see the [LICENSE](https://github.com/glohalo/colombia-metereological-predictions/blob/main/LICENSE) file for details.

## Acknowledgments

Special thanks to my advisors, peers, and The Institute of Hydrology, Meteorology and Environmental Studies (IDEAM) for providing the necessary data and support for this research.
