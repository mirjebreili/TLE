# High-order information analysis of epileptogenesis in the pilocarpine rat model of temporal lobe epilepsy

This repository contains the code and data associated with the upcoming publication on High-order information analysis of epileptogenesis in the pilocarpine rat model of temporal lobe epilepsy.

## Repository Structure

The repository comprises the following Jupyter Notebooks:

1. **Mutual_Information_final.ipynb**: This notebook calculates mutual information between different neural signals to assess the dependencies among them.

2. **Analysis_and_stats_final.ipynb**: This notebook performs statistical analyses on the computed information measures, including significance testing and visualization of results.

3. **main_figures_and_tables_final.ipynb**: This notebook generates the primary figures and tables for the publication, summarizing the key findings of the study.

## Dependencies

To run the notebooks, ensure you have the following Python packages installed:

- NumPy
- SciPy
- scikit-learn
- Matplotlib
- Seaborn
- Pandas

You can install these packages using `pip`:

```bash
pip install numpy scipy scikit-learn matplotlib seaborn pandas
```

## Usage

1. **Data Preparation**: Ensure that your dataset is formatted correctly and accessible to the notebooks. Update the data paths in the notebooks as necessary.

2. **Mutual Information Calculation**: Run the `Mutual_Information_final.ipynb` notebook to compute the mutual information between neural signals.

3. **Statistical Analysis**: Execute the `Analysis_and_stats_final.ipynb` notebook to perform statistical tests and generate intermediate plots.

4. **Generate Figures and Tables**: Use the `main_figures_and_tables_final.ipynb` notebook to create the final figures and tables for the publication.
