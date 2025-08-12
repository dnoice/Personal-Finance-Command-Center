# 🚀 Personal Finance Command Center

> A powerful, cyberpunk-themed financial management dashboard with advanced analytics, machine learning categorization, and comprehensive financial planning tools - all running securely in your browser.

[![Version](https://img.shields.io/badge/version-2.0.0-cyan.svg)](https://github.com/dnoice/Personal-Finance-Command-Center/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/dnoice/Personal-Finance-Command-Center/blob/main/LICENSE)
[![Browser](https://img.shields.io/badge/browser-Chrome%20%7C%20Firefox%20%7C%20Safari%20%7C%20Edge-blue.svg)](https://github.com/dnoice/Personal-Finance-Command-Center#system-requirements)
[![Dependencies](https://img.shields.io/badge/dependencies-0-brightgreen.svg)](https://github.com/dnoice/Personal-Finance-Command-Center)
[![GitHub Stars](https://img.shields.io/github/stars/dnoice/Personal-Finance-Command-Center?style=social)](https://github.com/dnoice/Personal-Finance-Command-Center)

**Repository**: [https://github.com/dnoice/Personal-Finance-Command-Center](https://github.com/dnoice/Personal-Finance-Command-Center)

## 🌟 Overview

The Personal Finance Command Center is a standalone HTML application that provides institutional-grade financial analytics and management capabilities without requiring any server, installation, or external dependencies. All processing happens locally in your browser, ensuring complete privacy and security for your financial data.

### ✨ Key Features

- **🤖 AI-Powered Transaction Categorization** - Naive Bayes classifier with confidence scoring
- **📊 10+ Financial Modules** - Budget, investments, debt, retirement, taxes, and more
- **🎲 Monte Carlo Simulations** - 5,000 runs for retirement planning accuracy
- **💎 Cyberpunk UI** - Modern dark theme with neon accents and glassmorphic design
- **📈 Advanced Analytics** - NPV, IRR, amortization, anomaly detection
- **🔒 100% Private** - All data processing happens locally
- **📱 Fully Responsive** - Works on desktop, tablet, and mobile
- **⚡ Zero Dependencies** - Single HTML file, no installation required

## 🚀 Quick Start

### Installation

#### Option 1: Direct Download (Easiest)
1. **Download**: Get the latest release from [GitHub](https://github.com/dnoice/Personal-Finance-Command-Center/releases)
2. **Save**: Save `finance-command-center.html` to your computer
3. **Open**: Double-click the file or open with Chrome/Firefox/Safari/Edge
4. **Start using**: No installation, no server, no configuration needed!

#### Option 2: Clone Repository
```bash
git clone https://github.com/dnoice/Personal-Finance-Command-Center.git
cd Personal-Finance-Command-Center
# Open finance-command-center.html in your browser
```

#### Option 3: Direct Link
Access the live version at: [https://dnoice.github.io/Personal-Finance-Command-Center/](https://dnoice.github.io/Personal-Finance-Command-Center/) *(if GitHub Pages is enabled)*

### System Requirements

- **Browser**: Any modern browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- **RAM**: 2GB minimum (4GB recommended for large datasets)
- **JavaScript**: Must be enabled
- **Screen**: 1280x720 minimum resolution

## 📖 User Guide

### Getting Started

1. **Import Your Data**
   - Click the **"Import CSV"** button in the header
   - Select your bank statement CSV file
   - The AI will automatically categorize all transactions
   - Supports multiple CSV formats (most banks compatible)

2. **Navigate Modules**
   - Use the tab bar to switch between different financial modules
   - Each module provides specific tools and insights
   - All data syncs across modules automatically

3. **Export Reports**
   - Click **"Export Report"** to download comprehensive Excel workbook
   - Includes all data across multiple sheets
   - Timestamped filename for organization

### CSV Format Guidelines

The app intelligently parses various CSV formats. Common column names supported:

| Column Type | Accepted Names |
|------------|---------------|
| Date | Date, date, Transaction Date, Posted Date |
| Amount | Amount, amount, Debit, Credit, Value |
| Description | Description, description, Merchant, merchant, Details |
| Account | Account, account, Account Name |

**Sample CSV Format:**
```csv
Date,Description,Amount
2024-01-15,Walmart Grocery,-125.43
2024-01-16,Salary Deposit,3500.00
2024-01-17,Netflix Subscription,-15.99
```

## 🎯 Features in Detail

### 1. Dashboard
- **Financial Health Score**: 0-100 score with letter grade (A-F)
- **Net Worth Tracking**: Assets minus liabilities with trend analysis
- **Key Metrics**: Savings rate, total assets, total debt
- **Interactive Charts**: Budget vs spending, portfolio allocation
- **Anomaly Alerts**: Automatic detection of unusual transactions
- **Quick Actions**: Fast access to common tasks

### 2. Accounts Management
- Track multiple account types (checking, savings, investment)
- Account balance monitoring
- Recent activity feed
- Performance tracking with monthly changes

### 3. Transaction Analysis
- **AI Categorization**: Machine learning with confidence scores
- **Recurring Detection**: Identifies subscription and regular payments
- **Advanced Filtering**: By date, category, amount, confidence
- **Bulk Editing**: Tag and categorize multiple transactions
- **Search**: Find transactions by description or amount

### 4. Budget Management
- **Envelope Budgeting**: Visual budget allocation system
- **Progress Tracking**: Real-time spending vs budget
- **Overspending Alerts**: Automatic warnings
- **Category Icons**: Visual category identification
- **Budget Summary**: Total budget, spent, and remaining

### 5. Investment Portfolio
- **Asset Allocation**: Current vs target percentages
- **Rebalancing Suggestions**: Buy/sell recommendations with tax impact
- **Performance Tracking**: Daily and YTD returns
- **Risk Assessment**: Portfolio risk level analysis
- **Tax Optimization**: Capital gains considerations

### 6. Debt Management
- **Three Strategies**:
  - **Avalanche**: Highest interest rate first (mathematically optimal)
  - **Snowball**: Smallest balance first (psychological wins)
  - **Hybrid**: Balanced approach
- **Payoff Timeline**: Month-by-month projection
- **Interest Calculations**: Total interest by strategy
- **Payment Tracking**: Minimum vs actual payments

### 7. Goals Tracking
- **Priority Levels**: High, medium, low importance
- **Progress Visualization**: Percentage complete with progress bars
- **Timeline Management**: Days remaining countdown
- **Required Contributions**: Monthly amount needed to reach goal
- **Multiple Goal Types**: Emergency fund, vacation, major purchases

### 8. Retirement Planning
- **Monte Carlo Simulation**: 5,000 scenarios for accuracy
- **Success Rate**: Probability of not running out of money
- **Customizable Parameters**:
  - Current/retirement age
  - Current savings
  - Monthly contributions
  - Expected returns
  - Inflation rate
  - Life expectancy
  - Annual spending in retirement
- **Percentile Outcomes**: 25th, 50th, 75th, 95th percentiles
- **Visual Projections**: Growth charts over time

### 9. Tax Planning
- **Federal Tax Calculation**: Based on current tax brackets
- **State Tax Support**: Customizable state tax rates
- **FICA Taxes**: Social Security and Medicare
- **Deductions**: Standard and itemized
- **Child Tax Credits**: Dependent calculations
- **Effective vs Marginal Rates**: Complete tax analysis
- **Monthly Take-Home**: After-tax income calculations

### 10. Cryptocurrency Portfolio
- **Holdings Tracking**: Multiple crypto assets
- **24-Hour Changes**: Real-time performance
- **Portfolio Percentage**: Crypto allocation in total portfolio
- **Risk Assessment**: Volatility analysis

## 🔧 Technical Details

### Technologies Used

- **React 18**: Component-based UI framework
- **Chart.js 4.4**: Interactive data visualizations
- **PapaParse 5.4**: Robust CSV parsing
- **Math.js 11.11**: Financial calculations (NPV, IRR, statistics)
- **XLSX 0.18**: Excel file generation
- **Tailwind CSS**: Utility-first styling
- **Lucide Icons**: Modern icon library

### Algorithms Implemented

1. **Naive Bayes Classifier**: Transaction categorization with training data
2. **Z-Score Anomaly Detection**: Statistical outlier identification
3. **Monte Carlo Simulation**: Probabilistic retirement modeling
4. **NPV/IRR Calculations**: Investment analysis
5. **Amortization Schedule**: Loan payment calculations
6. **Modified Z-Score**: Robust anomaly detection using MAD
7. **IQR Method**: Additional outlier detection

### Data Privacy & Security

- **100% Client-Side**: No data leaves your browser
- **No External API Calls**: All processing happens locally
- **No Cookies/Storage**: Data exists only in memory during session
- **No Tracking**: Zero analytics or telemetry
- **Secure Processing**: All calculations in isolated browser context

## 🏗️ Technical Architecture

### Code Structure

The application is built as a single React component with embedded styles and scripts:

```
finance-command-center.html
├── HTML Structure
│   ├── Head (Meta, CDN Links, Styles)
│   ├── Body
│   │   └── Root DIV
│   └── Babel Script (JSX Compilation)
├── CSS Styles (Embedded)
│   ├── Base Styles
│   ├── Glassmorphism Effects
│   ├── Animations
│   └── Component Styles
└── React Application
    ├── State Management
    ├── Components
    ├── Calculations
    └── Event Handlers
```

### Component Architecture

```javascript
FinanceCommandCenter (Main Component)
├── State Hooks (15+ useState declarations)
├── Memoized Calculations (useMemo)
├── Effect Hooks (useEffect)
├── Event Handlers
├── Calculation Functions
└── Render Method
    ├── Header
    ├── Financial Health Score
    ├── Tab Navigation
    ├── Content Router (10 tabs)
    └── Footer
```

### State Management

The app uses React hooks for state management. Key state variables:

```javascript
// Core Data States
const [transactions, setTransactions] = useState([]);        // Transaction history
const [accounts, setAccounts] = useState([...]);            // Bank accounts
const [budgetEnvelopes, setBudgetEnvelopes] = useState([...]); // Budget categories
const [investmentPortfolio, setInvestmentPortfolio] = useState([...]); // Investments
const [debts, setDebts] = useState([...]);                  // Debt accounts
const [goals, setGoals] = useState([...]);                  // Financial goals
const [cryptoPortfolio, setCryptoPortfolio] = useState([...]); // Crypto holdings

// Configuration States
const [retirementParams, setRetirementParams] = useState({...}); // Retirement settings
const [taxParams, setTaxParams] = useState({...});          // Tax configuration

// UI States
const [activeTab, setActiveTab] = useState('dashboard');    // Current view
const [loading, setLoading] = useState(false);              // Loading indicator
const [notifications, setNotifications] = useState([]);     // Toast messages
const [darkMode, setDarkMode] = useState(false);           // Theme toggle
```

### Data Flow Diagram

```
User Input (CSV) → Papa.parse() → Processing Pipeline
                                  ├── Transaction Categorization (ML)
                                  ├── Anomaly Detection
                                  ├── Recurring Detection
                                  └── State Updates
                                      ├── Update Transactions
                                      ├── Update Budgets
                                      ├── Trigger Calculations
                                      └── Re-render UI
```

## 🛠️ Developer Guide

### Adding a New Financial Module

1. **Create the Tab Entry**:
```javascript
const tabs = [
    // ... existing tabs
    { id: 'newmodule', label: 'New Module', icon: 'icon-name' }
];
```

2. **Add State for Module Data**:
```javascript
const [moduleData, setModuleData] = useState({
    field1: '',
    field2: 0,
    // ... module specific data
});
```

3. **Create the Module Component**:
```javascript
{activeTab === 'newmodule' && (
    <div className="space-y-6">
        <h3 className="text-cyan-400 font-semibold text-lg">New Module</h3>
        {/* Module content here */}
    </div>
)}
```

4. **Add Calculations (if needed)**:
```javascript
const calculateModuleMetrics = () => {
    // Module-specific calculations
    return {
        metric1: value1,
        metric2: value2
    };
};
```

### Extending the ML Classifier

The Naive Bayes classifier can be enhanced for better accuracy:

```javascript
// Add more training data
const trainingData = [
    { text: 'walmart grocery store food kroger', category: 'Food' },
    { text: 'rent mortgage property', category: 'Housing' },
    // Add domain-specific terms
    { text: 'aws azure cloud hosting', category: 'Technology' },
    { text: 'coursera udemy education', category: 'Education' }
];

// Adjust classification threshold
const categorizeTransaction = (description) => {
    // ... existing code
    
    // Add confidence threshold
    const CONFIDENCE_THRESHOLD = 0.6; // 60% minimum confidence
    if (confidence < CONFIDENCE_THRESHOLD) {
        return { category: 'Uncategorized', confidence };
    }
    
    return { category: bestCategory, confidence: confidence * 100 };
};
```

### Creating Custom Calculations

Add new financial algorithms:

```javascript
// Example: Calculate CAGR (Compound Annual Growth Rate)
const calculateCAGR = (beginValue, endValue, years) => {
    return (Math.pow(endValue / beginValue, 1 / years) - 1) * 100;
};

// Example: Calculate Sharpe Ratio
const calculateSharpeRatio = (returns, riskFreeRate = 0.02) => {
    const excessReturns = returns.map(r => r - riskFreeRate);
    const avgExcessReturn = math.mean(excessReturns);
    const stdDev = math.std(excessReturns);
    return avgExcessReturn / stdDev;
};

// Example: Kelly Criterion for position sizing
const kellyCriterion = (winProb, winAmount, lossAmount) => {
    const b = winAmount / lossAmount;
    const p = winProb;
    const q = 1 - p;
    return (b * p - q) / b;
};
```

### Modifying Chart Configurations

Customize Chart.js visualizations:

```javascript
// Custom chart options
const customChartOptions = {
    responsive: true,
    maintainAspectRatio: false,
    plugins: {
        legend: {
            labels: {
                color: '#00ffff',
                font: {
                    family: 'Inter',
                    size: 12,
                    weight: '500'
                }
            }
        },
        tooltip: {
            backgroundColor: 'rgba(0, 0, 0, 0.9)',
            borderColor: '#00ffff',
            borderWidth: 1,
            titleColor: '#00ffff',
            bodyColor: '#78ffd6',
            callbacks: {
                label: function(context) {
                    return `${context.dataset.label}: ${context.parsed.y.toFixed(2)}`;
                }
            }
        }
    },
    scales: {
        x: {
            ticks: { color: '#78ffd6' },
            grid: { 
                color: 'rgba(0, 255, 255, 0.1)',
                lineWidth: 0.5
            }
        },
        y: {
            ticks: { 
                color: '#78ffd6',
                callback: function(value) {
                    return '

## 🔍 Debugging & Development Tools

### Browser DevTools Integration

```javascript
// Enable debug mode
const DEBUG = true; // Set to false in production

const log = (...args) => {
    if (DEBUG) console.log('[Finance]', ...args);
};

const logError = (...args) => {
    if (DEBUG) console.error('[Finance Error]', ...args);
};

const logPerformance = (label, fn) => {
    if (!DEBUG) return fn();
    console.time(label);
    const result = fn();
    console.timeEnd(label);
    return result;
};

// Usage
logPerformance('Monte Carlo Simulation', () => {
    return runMonteCarloSimulation(5000);
});
```

### Performance Monitoring

```javascript
// Performance observer
const performanceObserver = new PerformanceObserver((list) => {
    list.getEntries().forEach((entry) => {
        if (entry.duration > 100) { // Log slow operations
            console.warn(`Slow operation: ${entry.name} took ${entry.duration}ms`);
        }
    });
});

performanceObserver.observe({ entryTypes: ['measure'] });

// Measure critical operations
performance.mark('csv-parse-start');
// ... parsing code
performance.mark('csv-parse-end');
performance.measure('CSV Parsing', 'csv-parse-start', 'csv-parse-end');
```

### Memory Management

```javascript
// Memory leak prevention
useEffect(() => {
    // Cleanup function
    return () => {
        // Clear timers
        clearTimeout(saveTimer);
        clearInterval(updateInterval);
        
        // Remove event listeners
        window.removeEventListener('resize', handleResize);
        
        // Clear large data structures
        setTransactions([]);
        setChartData(null);
        
        // Destroy chart instances
        if (chartRef.current) {
            chartRef.current.destroy();
        }
    };
}, []);

// Memory usage monitoring
const checkMemoryUsage = () => {
    if (performance.memory) {
        const used = performance.memory.usedJSHeapSize / 1048576;
        const limit = performance.memory.jsHeapSizeLimit / 1048576;
        console.log(`Memory: ${used.toFixed(2)}MB / ${limit.toFixed(2)}MB`);
        
        if (used / limit > 0.9) {
            console.warn('High memory usage detected');
            // Trigger cleanup
            cleanupOldData();
        }
    }
};
```

## 📦 Deployment Options

### 1. Static Hosting (Recommended)

**GitHub Pages**:
```bash
# Clone the repository
git clone https://github.com/dnoice/Personal-Finance-Command-Center.git
cd Personal-Finance-Command-Center

# Make your changes
git add .
git commit -m "Your commit message"
git push origin main

# Enable GitHub Pages in repository settings
# Access at: https://dnoice.github.io/Personal-Finance-Command-Center/
```

**Direct Download**:
```bash
# Download directly
wget https://raw.githubusercontent.com/dnoice/Personal-Finance-Command-Center/main/finance-command-center.html

# Or using curl
curl -O https://raw.githubusercontent.com/dnoice/Personal-Finance-Command-Center/main/finance-command-center.html
```

**Netlify Drop**:
1. Visit https://app.netlify.com/drop
2. Drag and drop your HTML file
3. Get instant URL

**Vercel**:
```bash
npm i -g vercel
vercel --prod
```

### 2. Desktop Application

**Electron Wrapper**:
```javascript
// main.js
const { app, BrowserWindow } = require('electron');
const path = require('path');

function createWindow() {
    const win = new BrowserWindow({
        width: 1400,
        height: 900,
        webPreferences: {
            nodeIntegration: false,
            contextIsolation: true
        },
        icon: path.join(__dirname, 'icon.png')
    });
    
    win.loadFile('finance-command-center.html');
}

app.whenReady().then(createWindow);
```

```json
// package.json
{
    "name": "finance-command-center",
    "version": "2.0.0",
    "main": "main.js",
    "scripts": {
        "start": "electron .",
        "build": "electron-builder"
    },
    "devDependencies": {
        "electron": "^27.0.0",
        "electron-builder": "^24.0.0"
    }
}
```

### 3. Progressive Web App (PWA)

**manifest.json**:
```json
{
    "name": "Personal Finance Command Center",
    "short_name": "Finance Center",
    "start_url": "/finance-command-center.html",
    "display": "standalone",
    "theme_color": "#00ffff",
    "background_color": "#0a0a0a",
    "icons": [
        {
            "src": "icon-192.png",
            "sizes": "192x192",
            "type": "image/png"
        },
        {
            "src": "icon-512.png",
            "sizes": "512x512",
            "type": "image/png"
        }
    ]
}
```

**Service Worker**:
```javascript
// sw.js
const CACHE_NAME = 'finance-center-v2';
const urlsToCache = [
    '/finance-command-center.html',
    'https://unpkg.com/react@18/umd/react.production.min.js',
    'https://unpkg.com/react-dom@18/umd/react-dom.production.min.js',
    // ... other CDN resources
];

self.addEventListener('install', event => {
    event.waitUntil(
        caches.open(CACHE_NAME)
            .then(cache => cache.addAll(urlsToCache))
    );
});

self.addEventListener('fetch', event => {
    event.respondWith(
        caches.match(event.request)
            .then(response => response || fetch(event.request))
    );
});
```

## 🧩 Code Organization Best Practices

### File Structure (for multi-file setup)

```
finance-command-center/
├── index.html
├── src/
│   ├── components/
│   │   ├── Dashboard.js
│   │   ├── Transactions.js
│   │   ├── Budget.js
│   │   └── ...
│   ├── hooks/
│   │   ├── useTransactions.js
│   │   ├── useCalculations.js
│   │   └── useNotifications.js
│   ├── utils/
│   │   ├── calculations.js
│   │   ├── categorizer.js
│   │   └── formatters.js
│   ├── styles/
│   │   ├── theme.css
│   │   └── animations.css
│   └── constants/
│       ├── categories.js
│       └── config.js
├── tests/
│   ├── calculations.test.js
│   └── categorizer.test.js
└── package.json
```

### Extracting Components

```javascript
// components/TransactionTable.js
const TransactionTable = ({ transactions, onEdit, onDelete }) => {
    const [sortBy, setSortBy] = useState('date');
    const [filterBy, setFilterBy] = useState('all');
    
    const sortedTransactions = useMemo(() => {
        return [...transactions].sort((a, b) => {
            switch(sortBy) {
                case 'date':
                    return new Date(b.date) - new Date(a.date);
                case 'amount':
                    return b.amount - a.amount;
                case 'category':
                    return a.category.localeCompare(b.category);
                default:
                    return 0;
            }
        });
    }, [transactions, sortBy]);
    
    return (
        <div className="transaction-table">
            <TableHeader onSort={setSortBy} />
            <TableBody 
                transactions={sortedTransactions}
                onEdit={onEdit}
                onDelete={onDelete}
            />
            <TablePagination />
        </div>
    );
};
```

### Custom Hooks

```javascript
// hooks/useFinancialData.js
const useFinancialData = () => {
    const [data, setData] = useState(null);
    const [loading, setLoading] = useState(false);
    const [error, setError] = useState(null);
    
    const loadData = useCallback(async (source) => {
        setLoading(true);
        setError(null);
        
        try {
            const result = await processDataSource(source);
            setData(result);
        } catch (err) {
            setError(err.message);
        } finally {
            setLoading(false);
        }
    }, []);
    
    return { data, loading, error, loadData };
};

// hooks/useLocalStorage.js
const useLocalStorage = (key, initialValue) => {
    const [storedValue, setStoredValue] = useState(() => {
        try {
            const item = window.localStorage.getItem(key);
            return item ? JSON.parse(item) : initialValue;
        } catch (error) {
            console.error(`Error loading ${key} from localStorage:`, error);
            return initialValue;
        }
    });
    
    const setValue = useCallback((value) => {
        try {
            setStoredValue(value);
            window.localStorage.setItem(key, JSON.stringify(value));
        } catch (error) {
            console.error(`Error saving ${key} to localStorage:`, error);
        }
    }, [key]);
    
    return [storedValue, setValue];
};
```

### Utility Functions

```javascript
// utils/formatters.js
export const formatCurrency = (amount, currency = 'USD') => {
    return new Intl.NumberFormat('en-US', {
        style: 'currency',
        currency: currency,
        minimumFractionDigits: 0,
        maximumFractionDigits: 2
    }).format(amount);
};

export const formatPercentage = (value, decimals = 1) => {
    return `${(value * 100).toFixed(decimals)}%`;
};

export const formatDate = (date, format = 'short') => {
    const options = format === 'short' 
        ? { month: 'short', day: 'numeric', year: 'numeric' }
        : { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' };
    
    return new Date(date).toLocaleDateString('en-US', options);
};

// utils/validators.js
export const validateTransaction = (transaction) => {
    const errors = {};
    
    if (!transaction.date) {
        errors.date = 'Date is required';
    }
    
    if (!transaction.amount || transaction.amount <= 0) {
        errors.amount = 'Amount must be positive';
    }
    
    if (!transaction.description || transaction.description.length < 3) {
        errors.description = 'Description must be at least 3 characters';
    }
    
    return {
        isValid: Object.keys(errors).length === 0,
        errors
    };
};
```

## 🔧 Build Tools Setup (Optional)

### Webpack Configuration

```javascript
// webpack.config.js
const HtmlWebpackPlugin = require('html-webpack-plugin');
const MiniCssExtractPlugin = require('mini-css-extract-plugin');
const TerserPlugin = require('terser-webpack-plugin');

module.exports = {
    entry: './src/index.js',
    output: {
        path: path.resolve(__dirname, 'dist'),
        filename: 'bundle.[contenthash].js'
    },
    module: {
        rules: [
            {
                test: /\.jsx?$/,
                exclude: /node_modules/,
                use: {
                    loader: 'babel-loader',
                    options: {
                        presets: ['@babel/preset-react']
                    }
                }
            },
            {
                test: /\.css$/,
                use: [MiniCssExtractPlugin.loader, 'css-loader', 'postcss-loader']
            }
        ]
    },
    plugins: [
        new HtmlWebpackPlugin({
            template: './src/index.html',
            minify: true
        }),
        new MiniCssExtractPlugin({
            filename: 'styles.[contenthash].css'
        })
    ],
    optimization: {
        minimizer: [new TerserPlugin()],
        splitChunks: {
            chunks: 'all'
        }
    }
};
```

### Package Scripts

```json
{
    "scripts": {
        "dev": "webpack serve --mode development --open",
        "build": "webpack --mode production",
        "test": "jest",
        "lint": "eslint src/**/*.js",
        "format": "prettier --write src/**/*.js",
        "analyze": "webpack-bundle-analyzer dist/stats.json"
    }
}
```

## 📚 Additional Resources

### Learning Materials
- [React Documentation](https://react.dev)
- [Chart.js Documentation](https://www.chartjs.org/docs/)
- [PapaParse Documentation](https://www.papaparse.com/docs)
- [Math.js Documentation](https://mathjs.org/docs/)

### Financial Algorithms
- [Investopedia - NPV](https://www.investopedia.com/terms/n/npv.asp)
- [Monte Carlo Simulation](https://en.wikipedia.org/wiki/Monte_Carlo_method)
- [Naive Bayes Classifier](https://en.wikipedia.org/wiki/Naive_Bayes_classifier)

### Design Resources
- [Cyberpunk UI Design](https://www.behance.net/search/projects/?search=cyberpunk%20ui)
- [Glassmorphism CSS](https://css.glass)
- [Neon Color Palettes](https://coolors.co)

## 📊 Sample Data

### Test CSV Generator

Create a test CSV with this format:
```csv
Date,Description,Amount,Type
2024-01-01,Salary,5000,Credit
2024-01-05,Rent Payment,-1500,Debit
2024-01-10,Grocery Store,-200,Debit
2024-01-15,Gas Station,-50,Debit
```

## 🤝 Contributing

### Reporting Issues

Report issues at: [https://github.com/dnoice/Personal-Finance-Command-Center/issues](https://github.com/dnoice/Personal-Finance-Command-Center/issues)

1. Check [existing issues](https://github.com/dnoice/Personal-Finance-Command-Center/issues) first
2. Include browser version and OS
3. Provide sample data (anonymized)
4. Include console error messages
5. Describe expected vs actual behavior

### Feature Requests

Submit feature requests via [GitHub Issues](https://github.com/dnoice/Personal-Finance-Command-Center/issues/new):
- Use the "enhancement" label
- Explain use case clearly
- Provide examples if possible
- Consider privacy implications
- Check if feature already exists

### Pull Requests

1. Fork the repository: [https://github.com/dnoice/Personal-Finance-Command-Center](https://github.com/dnoice/Personal-Finance-Command-Center)
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

### Community

- **Star the repo**: If you find this helpful, please star [the repository](https://github.com/dnoice/Personal-Finance-Command-Center)
- **Share**: Tell others about the project
- **Contribute**: Code, documentation, or bug reports are welcome!

## 📈 Performance Tips

1. **Large Datasets**: Import in batches of 1000 transactions
2. **Memory Usage**: Close unused browser tabs
3. **Speed**: Use Chrome/Edge for best performance
4. **Mobile**: Use landscape orientation for tables

## 🔄 Updates & Versions

### Version 2.0.0 (Current)
- Cyberpunk UI redesign
- Enhanced error handling
- 5,000 Monte Carlo simulations
- Cryptocurrency portfolio
- Tax planning module
- Financial health scoring

### Version 1.0.0
- Initial release
- Core functionality
- Basic UI

## 📚 API Reference

### Core Functions

#### `categorizeTransaction(description: string): {category: string, confidence: number}`
Classifies a transaction using Naive Bayes algorithm.
```javascript
const result = categorizeTransaction("Walmart grocery shopping");
// Returns: { category: "Food", confidence: 85.5 }
```

#### `runMonteCarloSimulation(runs: number): SimulationResult`
Runs retirement planning simulations with market volatility.
```javascript
const results = runMonteCarloSimulation(5000);
// Returns: { median, percentile25, percentile75, percentile95, average, successRate }
```

#### `detectAnomalies(): Transaction[]`
Identifies unusual transactions using statistical methods.
```javascript
const anomalies = detectAnomalies();
// Returns: Array of transactions with z-score > 2.5
```

#### `calculateNPV(cashFlows: number[], rate: number): number`
Calculates Net Present Value of cash flows.
```javascript
const npv = calculateNPV([-1000, 300, 300, 300, 300], 0.1);
// Returns: 137.24
```

#### `calculateIRR(cashFlows: number[]): number`
Calculates Internal Rate of Return using Newton's method.
```javascript
const irr = calculateIRR([-1000, 300, 300, 300, 300]);
// Returns: 15.24 (as percentage)
```

#### `calculateDebtStrategies(): StrategyResults`
Compares avalanche, snowball, and hybrid debt payoff methods.
```javascript
const strategies = calculateDebtStrategies();
// Returns: { avalanche: {...}, snowball: {...}, hybrid: {...} }
```

#### `estimateTaxes(): TaxCalculation`
Calculates federal, state, and FICA taxes.
```javascript
const taxes = estimateTaxes();
// Returns: { federalTax, stateTax, totalTax, effectiveRate, afterTaxIncome }
```

#### `calculateFinancialHealth(): HealthScore`
Generates comprehensive financial health assessment.
```javascript
const health = calculateFinancialHealth();
// Returns: { score: 85, factors: [...], grade: 'B' }
```

### State Management API

#### Transaction State
```javascript
// Get all transactions
const allTransactions = transactions;

// Add transaction
setTransactions(prev => [...prev, newTransaction]);

// Update transaction
setTransactions(prev => prev.map(t => 
    t.id === targetId ? { ...t, ...updates } : t
));

// Delete transaction
setTransactions(prev => prev.filter(t => t.id !== targetId));

// Bulk operations
setTransactions(prev => {
    // Complex transformations
    return processedTransactions;
});
```

#### Notification System
```javascript
// Add notification
addNotification(message: string, type: 'success' | 'error' | 'warning' | 'info')

// Auto-dismiss after 5 seconds
// Manual dismiss not required
```

### Data Structures

#### Transaction Object
```typescript
interface Transaction {
    id: string;              // Unique identifier
    date: string;            // YYYY-MM-DD format
    description: string;     // Merchant/description
    amount: number;          // Positive number
    category: string;        // AI-assigned category
    confidence: number;      // 0-100 confidence score
    type: 'income' | 'expense';
    account: string;         // Source account
    tags: string[];          // User tags
    notes: string;           // User notes
    recurring: boolean;      // Recurring flag
}
```

#### Budget Envelope
```typescript
interface BudgetEnvelope {
    category: string;        // Category name
    budget: number;          // Allocated amount
    spent: number;           // Current spending
    color: string;           // Hex color code
    icon: string;            // Lucide icon name
}
```

#### Investment Asset
```typescript
interface Asset {
    asset: string;           // Asset name
    value: number;           // Current value
    target: number;          // Target percentage
    actual: number;          // Actual percentage
    change: number;          // Daily change %
}
```

#### Debt Account
```typescript
interface Debt {
    name: string;            // Account name
    balance: number;         // Current balance
    rate: number;            // Interest rate %
    minimum: number;         // Minimum payment
    paid: number;            // Actual payment
}
```

#### Financial Goal
```typescript
interface Goal {
    name: string;            // Goal name
    target: number;          // Target amount
    current: number;         // Current progress
    deadline: string;        // YYYY-MM-DD format
    priority: 'high' | 'medium' | 'low';
}
```

### Event Handlers

#### File Upload
```javascript
const handleFileUpload = (event: ChangeEvent<HTMLInputElement>) => {
    const file = event.target.files[0];
    // Validates: file exists, is CSV, under 10MB
    // Parses with PapaParse
    // Categorizes transactions
    // Updates state
    // Shows notifications
}
```

#### Input Handlers
```javascript
// Generic number input
onChange={(e) => setState({ ...state, field: +e.target.value })}

// Validated input
onChange={(e) => {
    const value = parseFloat(e.target.value);
    if (value >= min && value <= max) {
        setState(value);
    }
}}

// Debounced input
onChange={debounce((e) => {
    performExpensiveOperation(e.target.value);
}, 300)}
```

### Chart Configuration

#### Chart.js Options
```javascript
const chartOptions = {
    responsive: true,
    maintainAspectRatio: false,
    plugins: {
        legend: {
            labels: { color: '#00ffff' }
        },
        tooltip: {
            backgroundColor: 'rgba(0, 0, 0, 0.9)',
            callbacks: {
                label: (context) => `${context.parsed.y.toFixed(2)}`
            }
        }
    },
    scales: {
        x: {
            ticks: { color: '#78ffd6' },
            grid: { color: 'rgba(0,255,255,0.1)' }
        },
        y: {
            ticks: { 
                color: '#78ffd6',
                callback: (value) => `${value.toLocaleString()}`
            }
        }
    }
};
```

### Utility Functions

#### Number Formatting
```javascript
// Currency
formatCurrency(1234.56)  // "$1,235"

// Percentage
formatPercentage(0.125)  // "12.5%"

// Compact
formatCompact(1500000)   // "1.5M"
```

#### Date Utilities
```javascript
// Format date
formatDate('2024-01-15')  // "Jan 15, 2024"

// Days between
daysBetween(date1, date2)  // 30

// Add months
addMonths(date, 3)  // Date + 3 months
```

#### Validation
```javascript
// Validate email
isValidEmail('user@example.com')  // true

// Validate amount
isValidAmount('123.45')  // true

// Validate date
isValidDate('2024-01-15')  // true
```

## 💻 Development Workflow

### Local Development Setup

1. **Clone and Setup**:
```bash
git clone https://github.com/dnoice/Personal-Finance-Command-Center.git
cd Personal-Finance-Command-Center
```

2. **Install Development Tools** (optional):
```bash
npm init -y
npm install --save-dev prettier eslint live-server
```

3. **Development Server**:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx live-server --port=8000

# Using PHP
php -S localhost:8000
```

4. **Code Formatting**:
```json
// .prettierrc
{
    "semi": true,
    "singleQuote": true,
    "tabWidth": 4,
    "trailingComma": "es5",
    "bracketSpacing": true
}
```

5. **Linting Rules**:
```json
// .eslintrc
{
    "extends": ["eslint:recommended"],
    "parserOptions": {
        "ecmaVersion": 2022,
        "sourceType": "module",
        "ecmaFeatures": {
            "jsx": true
        }
    },
    "rules": {
        "no-unused-vars": "warn",
        "no-console": "off"
    }
}
```

### Git Workflow

```bash
# Feature branch
git checkout -b feature/new-module

# Make changes
git add .
git commit -m "feat: add retirement calculator module"

# Push and create PR
git push origin feature/new-module
```

### Commit Convention
- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation
- `style:` Formatting
- `refactor:` Code restructuring
- `test:` Tests
- `chore:` Maintenance

## 🔐 Security Considerations

### Input Sanitization
```javascript
const sanitizeInput = (input) => {
    return input
        .replace(/[<>]/g, '')  // Remove HTML tags
        .trim()                 // Remove whitespace
        .slice(0, 1000);       // Limit length
};
```

### XSS Prevention
```javascript
// Never use innerHTML with user data
element.textContent = userInput;  // Safe
// element.innerHTML = userInput;  // Dangerous!

// React automatically escapes
<div>{userInput}</div>  // Safe
```

### Content Security Policy
```html
<meta http-equiv="Content-Security-Policy" 
      content="default-src 'self'; 
               script-src 'self' 'unsafe-inline' https://unpkg.com https://cdn.jsdelivr.net;
               style-src 'self' 'unsafe-inline';">
```

## 🎯 Future Enhancements

### Planned Features
- [ ] Bank API integration (Plaid)
- [ ] Real-time stock/crypto prices
- [ ] Multi-currency support
- [ ] Bill reminders and automation
- [ ] Receipt scanning with OCR
- [ ] Family/shared accounts
- [ ] Mobile app (React Native)
- [ ] Voice commands
- [ ] AI financial advisor
- [ ] Blockchain integration

### Community Contributions
We welcome contributions! Please:
1. Fork [the repository](https://github.com/dnoice/Personal-Finance-Command-Center)
2. Create a feature branch
3. Add tests for new features
4. Update documentation
5. Submit a pull request

Track progress and discuss features in [GitHub Issues](https://github.com/dnoice/Personal-Finance-Command-Center/issues).

## 📜 License

MIT License - Free for personal and commercial use. See [LICENSE](https://github.com/dnoice/Personal-Finance-Command-Center/blob/main/LICENSE) for details.

## 🙏 Acknowledgments

- React team for the framework
- Chart.js for visualizations
- PapaParse for CSV handling
- Math.js for calculations
- The open-source community
- All [contributors](https://github.com/dnoice/Personal-Finance-Command-Center/graphs/contributors) to this project + value.toLocaleString();
                }
            },
            grid: { 
                color: 'rgba(0, 255, 255, 0.1)',
                lineWidth: 0.5
            }
        }
    },
    animation: {
        duration: 1000,
        easing: 'easeInOutQuart'
    }
};
```

### Custom Styling System

The app uses a combination of Tailwind utilities and custom CSS:

```css
/* Adding new neon colors */
.neon-purple {
    color: #bf00ff;
    text-shadow: 0 0 10px rgba(191, 0, 255, 0.8), 
                 0 0 20px rgba(191, 0, 255, 0.5);
}

/* Custom glassmorphism variants */
.glass-ultra {
    background: linear-gradient(135deg, 
        rgba(0, 255, 255, 0.1) 0%, 
        rgba(255, 0, 128, 0.1) 100%);
    backdrop-filter: blur(40px) saturate(200%);
    border: 1px solid rgba(255, 255, 255, 0.15);
}

/* Animation variants */
@keyframes neonPulse {
    0%, 100% {
        filter: brightness(1) drop-shadow(0 0 10px currentColor);
    }
    50% {
        filter: brightness(1.2) drop-shadow(0 0 20px currentColor);
    }
}

.animate-neon-pulse {
    animation: neonPulse 2s ease-in-out infinite;
}
```

### Event Handler Patterns

Standard patterns for handling user interactions:

```javascript
// File upload with validation
const handleFileUpload = (event) => {
    const file = event.target.files[0];
    
    // Validation
    if (!file) return;
    if (!file.name.endsWith('.csv')) {
        addNotification('Please upload a CSV file', 'error');
        return;
    }
    if (file.size > 10485760) { // 10MB
        addNotification('File too large (max 10MB)', 'error');
        return;
    }
    
    // Processing
    setLoading(true);
    Papa.parse(file, {
        header: true,
        dynamicTyping: true,
        skipEmptyLines: true,
        beforeFirstChunk: (chunk) => {
            // Pre-process chunk if needed
            return chunk;
        },
        complete: (results) => {
            processResults(results);
            setLoading(false);
        },
        error: (error) => {
            handleError(error);
            setLoading(false);
        }
    });
};

// Input validation pattern
const handleNumericInput = (setter, min = 0, max = Infinity) => (e) => {
    const value = parseFloat(e.target.value);
    if (isNaN(value)) return;
    if (value < min || value > max) {
        addNotification(`Value must be between ${min} and ${max}`, 'warning');
        return;
    }
    setter(value);
};
```

### Performance Optimization Techniques

```javascript
// Memoize expensive calculations
const expensiveCalculation = useMemo(() => {
    return runMonteCarloSimulation(5000);
}, [retirementParams]); // Only recalculate when params change

// Debounce search/filter operations
const debounce = (func, wait) => {
    let timeout;
    return (...args) => {
        clearTimeout(timeout);
        timeout = setTimeout(() => func.apply(this, args), wait);
    };
};

const debouncedSearch = useMemo(
    () => debounce((searchTerm) => {
        const filtered = transactions.filter(t => 
            t.description.toLowerCase().includes(searchTerm.toLowerCase())
        );
        setFilteredTransactions(filtered);
    }, 300),
    [transactions]
);

// Virtualization for large lists (pseudo-code)
const VirtualizedList = ({ items, itemHeight, containerHeight }) => {
    const [scrollTop, setScrollTop] = useState(0);
    const startIndex = Math.floor(scrollTop / itemHeight);
    const endIndex = Math.ceil((scrollTop + containerHeight) / itemHeight);
    const visibleItems = items.slice(startIndex, endIndex);
    
    return (
        <div onScroll={(e) => setScrollTop(e.target.scrollTop)}>
            {visibleItems.map(item => <ItemComponent key={item.id} {...item} />)}
        </div>
    );
};
```

### Adding Data Persistence

While the app doesn't use localStorage by default, you can add it:

```javascript
// Save state to localStorage
const saveToLocalStorage = (key, data) => {
    try {
        localStorage.setItem(key, JSON.stringify(data));
        return true;
    } catch (e) {
        console.error('Failed to save to localStorage:', e);
        return false;
    }
};

// Load state from localStorage
const loadFromLocalStorage = (key, defaultValue) => {
    try {
        const item = localStorage.getItem(key);
        return item ? JSON.parse(item) : defaultValue;
    } catch (e) {
        console.error('Failed to load from localStorage:', e);
        return defaultValue;
    }
};

// Auto-save hook
useEffect(() => {
    const saveTimer = setTimeout(() => {
        saveToLocalStorage('transactions', transactions);
        saveToLocalStorage('budgets', budgetEnvelopes);
        // Save other state...
    }, 1000); // Save 1 second after changes stop
    
    return () => clearTimeout(saveTimer);
}, [transactions, budgetEnvelopes]);
```

### API Integration Template

For connecting to external services:

```javascript
// Generic API client
class FinanceAPI {
    constructor(apiKey) {
        this.apiKey = apiKey;
        this.baseURL = 'https://api.example.com/v1';
    }
    
    async fetchData(endpoint, options = {}) {
        try {
            const response = await fetch(`${this.baseURL}${endpoint}`, {
                ...options,
                headers: {
                    'Authorization': `Bearer ${this.apiKey}`,
                    'Content-Type': 'application/json',
                    ...options.headers
                }
            });
            
            if (!response.ok) {
                throw new Error(`API Error: ${response.status}`);
            }
            
            return await response.json();
        } catch (error) {
            console.error('API Request Failed:', error);
            throw error;
        }
    }
    
    // Specific methods
    async getStockPrice(symbol) {
        return this.fetchData(`/stocks/${symbol}`);
    }
    
    async getCryptoPrice(symbol) {
        return this.fetchData(`/crypto/${symbol}`);
    }
}

// Usage in component
const [apiClient] = useState(() => new FinanceAPI(process.env.API_KEY));

useEffect(() => {
    apiClient.getStockPrice('AAPL').then(data => {
        // Update portfolio with real-time data
    });
}, []);
```

### Testing Strategies

```javascript
// Unit test example (Jest-like syntax)
describe('Financial Calculations', () => {
    test('NPV calculation', () => {
        const cashFlows = [-1000, 300, 300, 300, 300, 300];
        const rate = 0.1;
        const npv = calculateNPV(cashFlows, rate);
        expect(npv).toBeCloseTo(137.24, 2);
    });
    
    test('Transaction categorization', () => {
        const result = categorizeTransaction('Walmart grocery shopping');
        expect(result.category).toBe('Food');
        expect(result.confidence).toBeGreaterThan(70);
    });
});

// Integration test example
describe('CSV Import', () => {
    test('Processes valid CSV correctly', async () => {
        const csvContent = `Date,Description,Amount
2024-01-01,Test Transaction,100.00`;
        const file = new File([csvContent], 'test.csv', { type: 'text/csv' });
        
        const result = await processCSV(file);
        expect(result.transactions).toHaveLength(1);
        expect(result.transactions[0].amount).toBe(100);
    });
});
```

## 🎨 Advanced Customization

### Creating a Custom Theme

```javascript
// Theme configuration object
const themes = {
    cyberpunk: {
        primary: '#00ffff',
        secondary: '#ff0080',
        success: '#78ffd6',
        warning: '#ffd700',
        danger: '#ff4060',
        background: '#0a0a0a',
        surface: 'rgba(18, 18, 18, 0.8)',
        text: {
            primary: '#ffffff',
            secondary: '#78ffd6',
            muted: '#666666'
        }
    },
    synthwave: {
        primary: '#ff6b9d',
        secondary: '#c66fbc',
        success: '#00ff88',
        warning: '#feca57',
        danger: '#ee5a24',
        background: '#0f0e17',
        surface: 'rgba(46, 41, 78, 0.8)',
        text: {
            primary: '#fffffe',
            secondary: '#ff8906',
            muted: '#a7a9be'
        }
    }
};

// Theme provider component
const ThemeProvider = ({ theme, children }) => {
    useEffect(() => {
        const root = document.documentElement;
        Object.entries(themes[theme]).forEach(([key, value]) => {
            if (typeof value === 'object') {
                Object.entries(value).forEach(([subKey, subValue]) => {
                    root.style.setProperty(`--${key}-${subKey}`, subValue);
                });
            } else {
                root.style.setProperty(`--${key}`, value);
            }
        });
    }, [theme]);
    
    return children;
};
```

### Building a Plugin System

```javascript
// Plugin interface
class FinancePlugin {
    constructor(name, version) {
        this.name = name;
        this.version = version;
        this.hooks = {};
    }
    
    // Register hook callbacks
    on(hook, callback) {
        if (!this.hooks[hook]) {
            this.hooks[hook] = [];
        }
        this.hooks[hook].push(callback);
    }
    
    // Execute hook
    execute(hook, data) {
        if (this.hooks[hook]) {
            return this.hooks[hook].reduce((result, callback) => {
                return callback(result);
            }, data);
        }
        return data;
    }
}

// Example plugin: Tax optimizer
const taxOptimizerPlugin = new FinancePlugin('TaxOptimizer', '1.0.0');

taxOptimizerPlugin.on('beforeTransactionSave', (transaction) => {
    // Add tax implications
    transaction.taxDeductible = isDeductible(transaction.category);
    return transaction;
});

taxOptimizerPlugin.on('afterPortfolioRebalance', (suggestions) => {
    // Add tax-loss harvesting suggestions
    return addTaxLossHarvesting(suggestions);
});
```

## 🐛 Troubleshooting

### Common Issues

| Issue | Solution |
|-------|----------|
| CSV not importing | Check file size (<10MB), ensure CSV format, verify column names |
| Charts not displaying | Enable JavaScript, update browser, check console for errors |
| Calculations incorrect | Verify input data, check for negative amounts, ensure date formats |
| Performance issues | Reduce transaction count, close other tabs, increase browser memory |
| Export not working | Check popup blocker, ensure sufficient disk space |

### Browser Console

Press `F12` to open developer tools and check for error messages.

## 📊 Sample Data

### Test CSV Generator

Create a test CSV with this format:
```csv
Date,Description,Amount,Type
2024-01-01,Salary,5000,Credit
2024-01-05,Rent Payment,-1500,Debit
2024-01-10,Grocery Store,-200,Debit
2024-01-15,Gas Station,-50,Debit
```

## 🤝 Contributing

### Reporting Issues

1. Check existing issues first
2. Include browser version and OS
3. Provide sample data (anonymized)
4. Include console error messages
5. Describe expected vs actual behavior

### Feature Requests

- Explain use case clearly
- Provide examples if possible
- Consider privacy implications
- Check if feature already exists

## 📈 Performance Tips

1. **Large Datasets**: Import in batches of 1000 transactions
2. **Memory Usage**: Close unused browser tabs
3. **Speed**: Use Chrome/Edge for best performance
4. **Mobile**: Use landscape orientation for tables

## 🔄 Updates & Versions

### Version 2.0.0 (Current)
- Cyberpunk UI redesign
- Enhanced error handling
- 5,000 Monte Carlo simulations
- Cryptocurrency portfolio
- Tax planning module
- Financial health scoring

### Version 1.0.0
- Initial release
- Core functionality
- Basic UI

## 📜 License

MIT License - Free for personal and commercial use.

## 🙏 Acknowledgments

- React team for the framework
- Chart.js for visualizations
- PapaParse for CSV handling
- Math.js for calculations
- The open-source community

## 💡 Tips & Best Practices

1. **Regular Imports**: Upload transactions weekly for best tracking
2. **Category Review**: Check AI categorization monthly
3. **Budget Adjustments**: Update budgets based on spending patterns
4. **Goal Setting**: Use SMART goals (Specific, Measurable, Achievable, Relevant, Time-bound)
5. **Retirement Planning**: Re-run simulations quarterly with updated data
6. **Tax Planning**: Update parameters when income changes
7. **Debt Strategy**: Choose based on personality (avalanche for math, snowball for motivation)
8. **Portfolio Rebalancing**: Review quarterly, rebalance annually

## 🚨 Disclaimer

This tool is for informational purposes only and should not be considered financial advice. Always consult with qualified financial professionals for important financial decisions. The creators assume no liability for financial decisions made using this tool.

## 📞 Support

For questions or support:
- **GitHub Issues**: [Report bugs or ask questions](https://github.com/dnoice/Personal-Finance-Command-Center/issues)
- **Discussions**: [Join the conversation](https://github.com/dnoice/Personal-Finance-Command-Center/discussions)
- **Documentation**: Review this README thoroughly
- **Troubleshooting**: Check the troubleshooting section above
- **Browser Check**: Ensure you're using a supported browser
- **CSV Format**: Verify your CSV format matches examples

---

**Repository**: [github.com/dnoice/Personal-Finance-Command-Center](https://github.com/dnoice/Personal-Finance-Command-Center)

**Built with 💙 and ⚡ | Manage your finances in style**
