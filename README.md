# WiseWallet
A self-hosted bill and money tracking application designed to give you full control over your spending history—down to individual items on every receipt.

This app allows you to store, organize, and analyze years of receipts and financial data in one locally hosted web interface. Upload paper receipts, bank statements, or manually enter purchases to build a detailed, searchable record of your spending habits.

Key Features:

Receipt Management

- Upload photos of paper receipts with automatic text recognition
- Manually enter receipts and itemized purchases
- Store and view receipts from any year in one place

Price & Store Analysis

- Track how prices of individual items change over time
- Compare prices across different stores to find cheaper or more expensive options
- Identify long-term trends in spending and inflation

Spending Insights

- Categorize purchases and see spending by category
- Visualize monthly, yearly, and custom time-range summaries
- Discover where your money goes with clear metrics and breakdowns

Data Import

- Upload CSV files from bank or credit card statement
- Automatically match transactions to existing receipts when possible

Privacy-First & Self-Hosted

- Runs on your own local server
- No cloud dependency, subscriptions, or data sharing
- Full ownership of your financial data

Who It’s For:

- People who want detailed insight into their spending
- Privacy-conscious users who prefer self-hosting
- Anyone who wants long-term tracking of prices, receipts, and budgets

Take control of your financial history, understand how your spending changes over time, and make smarter decisions—powered by your own data.

## Deployment Instructions

### Local Deployment

1. **Clone or download the repository**
   ```bash
   git clone https://github.com/sennatitcomb/WiseWallet.git
   cd WiseWallet
   ```

2. **Serve the application**
   You can use any local web server. Here are a few options:

   **Using Python 3:**
   ```bash
   python3 -m http.server 8000
   ```

   **Using Node.js (with http-server):**
   ```bash
   npm install -g http-server
   http-server
   ```

   **Using PHP:**
   ```bash
   php -S localhost:8000
   ```

3. **Access the application**
   Open your web browser and navigate to:
   ```
   http://localhost:8000/wisewallet.html
   ```

### Remote Deployment

For self-hosting on a remote server:

1. **Upload files to your server** using FTP, SFTP, or Git
2. **Configure your web server** (Apache, Nginx, etc.) to serve the files
3. **Access the application** at your server's domain/IP address

### Data Storage

- All data is stored locally in your browser's local storage or in files on your server
- No cloud sync is configured by default
- For persistent data across devices, consider setting up a backend database
