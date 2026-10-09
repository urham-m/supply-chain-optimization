# Supply Chain Optimization

This project cuts logistics costs for a retail supply chain using Python. It cleans and analyzes the sales and inventory data, uses linear programming (PuLP) to find the cheapest way to ship stock from warehouses to stores, and uses the EOQ model to set better order sizes. It then checks the savings and shows the results in an interactive Plotly Dash dashboard. Shipping costs, distances and delivery times are not in the dataset, so they are assumptions set in the notebook.

## How to run

1. Clone the repo and go into the folder:
```
   git clone https://github.com/urham-m/supply-chain-optimization.git
   cd supply-chain-optimization
```

2. Create a virtual environment and install the requirements:
```
   python -m venv .venv
   .venv\Scripts\activate
   pip install -r requirements.txt
```
   (On Mac/Linux use `source .venv/bin/activate` instead.)

3. Open `supply_chain_optimization.ipynb` in Jupyter or VS Code. Select the **`.venv` (Python)** kernel, then run the cells from top to bottom.

4. The dashboard opens inside the notebook, or at `http://localhost:8050`.

5. Results are saved in the `outputs/` folder.

## Dataset source

https://www.kaggle.com/datasets/atomicd/retail-store-inventory-and-demand-forecasting
