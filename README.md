# Reinforcement Learning for Product Pricing Optimization

This project uses a **Reinforcement Learning (RL)** approach to predict the ideal price of a product based on historical data, maximizing sales, organic conversion rates, and ad conversion rates.

## Quick Setup Instructions

### Step 1: Clone the Repository
Clone this repository to your local machine:
```bash
git clone https://github.com/your-repo-name/rl-pricing-optimization.git
cd rl-pricing-optimization
```

### Step 2: Install Dependencies
Install the required Python libraries:
```bash
pip install stable-baselines3 gym pandas numpy scikit-learn
```
If you are using **shimmy**, make sure it is installed:
```bash
pip install shimmy
```

### Step 3: Prepare the Dataset
Replace the placeholder dataset (`pricing_data.csv`) with your actual dataset in the same directory as the script. Ensure the following columns are included:
- `Report Date`
- `Product Price`
- `Total Sales`
- `Predicted Sales`
- `Organic Conversion Percentage`
- `Ad Conversion Percentage`
- `Total Profit`

### Step 4: Run the Script
Run the Python script to train the RL agent and predict the ideal price:
```bash
python rl_pricing_optimization.py
```

### Step 5: Inspect Results
- The script will print the predicted ideal price for tomorrow.
- Evaluation metrics such as MAE, MSE, and RMSE will be displayed.

---

## Example Output
```bash
Ideal price for tomorrow: $16.50

Performance Metrics:
Mean Absolute Error (MAE): 0.05
Mean Squared Error (MSE): 0.01
Root Mean Squared Error (RMSE): 0.10
```

For any issues, ensure the dataset is correctly formatted and all dependencies are installed. Happy coding!

