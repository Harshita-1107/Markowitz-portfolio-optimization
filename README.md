# **Markowitz Portfolio Optimization**

This project implements a portfolio optimization model to analyze and optimize stock allocations using historical financial data. The model computes risk-return metrics, simulates portfolios, and visualizes the Efficient Frontier, providing actionable insights for portfolio management.

---

## **Features**

### **Implemented**
1. **Data Retrieval**  
   - Dynamically fetches historical stock data for 10 large-cap stocks using `yfinance`.  
   - Saves processed data to CSV for reproducibility.

2. **Portfolio Simulation**  
   - Simulates 50,000 portfolios to compute:  
     - **Expected Returns**  
     - **Annualized Volatility**  
     - **Sharpe Ratio**

3. **Portfolio Optimization**  
   - Identifies optimal allocations for:  
     - **Maximum Sharpe Ratio Portfolio** (highest risk-adjusted return).  
     - **Minimum Volatility Portfolio** (lowest risk exposure).

4. **Visualization**  
   - Interactive **Efficient Frontier** visualization using Plotly, with optimal portfolios highlighted.

---

### **Future Enhancements**
1. **Risk Metrics Enhancements**  
   - Add **Value at Risk (VaR)** and **Expected Shortfall (ES)** for robust risk assessment.  
   - Introduce **Sortino Ratio** to evaluate downside risk effectively.  

2. **Real-World Portfolio Feasibility**  
   - Include transaction cost considerations and portfolio constraints.  

3. **Scalability and Testing**  
   - Enable analysis for portfolios with varying stock numbers.  
   - Implement stress-testing scenarios to assess performance under adverse market conditions.  

4. **Improved Reliability**  
   - Enhance error handling for missing data and API failures.

---

## **Tools & Technologies**  
- **Programming Languages:** Python  
- **Libraries:** Pandas, NumPy, Scipy, Matplotlib, Plotly  
- **Data Source:** yfinance  

---

## **How to Run**

1. Clone the repository.  
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Install dependencies.  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the script.  
   ```bash
   python Markowitz_portfolio_optimization.py
   ```

4. Outputs:  
   - Efficient Frontier plot (interactive, generated in browser).  
   - CSV file with processed financial data stored in the root directory.  
   - Portfolio allocation and metrics printed in the console.

---

Contributions to enhance the project are welcome. Please raise an issue or submit a pull request!
