✨ MeeshoTax-Calc ✨

A simple Python tool to process Meesho TCS sales data by removing returned sales and generating a state-wise summary of taxable sales. Built with Pandas for efficient Excel data handling. 📊🐍

------------------------------------------------------------------------------------------
✨ Features

📥 Loads sales and sales return Excel files  
❌ Removes returned sales from the sales data  
📊 Groups and sums taxable sales by state  
📄 Saves filtered and summary data to new Excel files  
------------------------------------------------------------------------------------------
🛠️ Installation

✅ Step 1: Clone or download the repository

```

git clone https://github.com/yourusername/meeshotax-calc.git
cd meeshotax-calc

```
✅ Step 2: Install dependencies (make sure Python 3.x is installed)
 `pip install pandas openpyxl`
------------------------------------------------------------------------------------------
▶️ Usage

1. Put your tcs_sales.xlsx and tcs_sales_return.xlsx files in the project folder.

2. Run the script:
`python main.py`

3. The script will create two files:
```
filtered_tcs.xlsx (sales data excluding returns)
statewise_taxable_summary.xlsx (state-wise summary of taxable sales)
```
------------------------------------------------------------------------------------------
👨‍💻 Author Vivek Sankath 🔥 Python Developer | 🛡️ Cybersecurity Enthusiast | 🧠 Automation Lover
📬 LinkedIn ( www.linkedin.com/in/vivek-sankath )
------------------------------------------------------------------------------------------
🪪 License MIT License – Free to use, modify, and share with credit! 🙌
