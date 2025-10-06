# Similar Sessions Forecasting Repository

This repository contains the code for the paper titled "**Forecasting flexibility of charging of electric vehicles: Tree and cluster-based methods**," which can be found [here](https://authors.elsevier.com/sd/article/S0306-2619(23)01333-8).

## Overview

The code in this repository is organized into Jupyter notebooks that cover various aspects of the research, including data acquisition, preprocessing, training, and evaluation. Each notebook is numbered and named to indicate its purpose:

1. **01-download_data.ipynb**: This notebook covers the data acquisition process.
2. **02-data_analyze.ipynb**: Use this notebook to explore and analyze the dataset.
3. **03a-lightgb_energy.ipynb**: This notebook contains code related to training and evaluating LightGBM models for energy-related predictions.
4. **03b-lightgb_energy_nologs.ipynb**: Similar to the previous notebook, but without logs.
5. **03c-lightgb_duration.ipynb**: Contains code for training and evaluating LightGBM models for duration-related predictions.
6. **03d-lightgb_duration_nologs.ipynb**: Similar to the previous notebook, but without logs.
7. **04b-similarity_scores_duration.ipynb**: This notebook focuses on calculating similarity scores for duration-related predictions.
8. **04b-similarity_scores_energy.ipynb**: Similar to the previous notebook, but for energy-related predictions.
9. **05-user_input.ipynb**: This notebook allows users to input data for predictions.
10. **06-analyze_methods.ipynb**: Analyze the methods and results of the research.

## Installation

To run the code in these notebooks, you will need to install the required Python packages. You can do this by running the following command:

```bash
pip install -r requirements.txt
```

Make sure you have Python installed on your system before running this command.

## Usage

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/EVERGi/similar_sessions/
   ```

2. Navigate to the project directory:

```bash
cd paper-code-repository
```

3. Install the required Python packages as mentioned above.

4. Open and run the Jupyter notebooks using your preferred environment (e.g., Jupyter Notebook, JupyterLab).

5. Follow the instructions within each notebook to execute the code and reproduce the results.

## Citation
If you find this code or the associated paper useful for your research, please consider citing it using the following BibTeX entry:

```
@article{genov_similar_sessions,
  title={Forecasting flexibility of charging of electric vehicles: Tree and cluster-based methods},
  author={Genov et al.},
  journal={Applied Energy},
  year={2023},
  volume={353},
  number={121969},
  doi={10.1016/121969}
}
```

## License
This code is provided under the MIT License.

Please feel free to reach out to the authors for any questions or clarifications related to the code or the paper.