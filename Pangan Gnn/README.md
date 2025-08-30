
# Food Price Prediction with Graph Neural Network (GNN)

This project aims to predict food prices in Indonesia using a Graph Neural Network (GNN) approach. The data includes premium rice prices and other related information. The GNN model is built and evaluated using several Jupyter notebooks available in this repository.

## Project Structure

- `harga_beras_premium.csv` — Premium rice price dataset.
- `requirements.txt` — List of required Python dependencies.
- `*.ipynb` — Jupyter notebooks for data exploration, model training, and evaluation.
- `final_gnn_model.pth` — Trained GNN model file.
- `best_gnn_params.json` — Best parameters from model tuning.

## How to Run

1. **Clone this repository** to your computer.

2. **Install dependencies** by running:

   ```bash
   pip install -r requirements.txt
   ```

3. **Open the desired Jupyter notebook** (e.g., `gnn_model_harga_pangan.ipynb`) and run the cells sequentially.

## Main Notebooks

- `gnn_model_harga_pangan.ipynb` — Main notebook for GNN model training and evaluation.
- `gnn_model_by_paper.ipynb` — Model implementation based on the referenced paper.
- `harga_pangan.ipynb` — Data exploration and initial analysis.
- `prediksi_harga_pangan_improved.ipynb` — Experiments and improvements for price prediction.

## Reference

- Paper: `s41598-025-97724-7.pdf`

## License

This project is for educational and research purposes only.
