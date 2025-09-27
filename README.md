# 💰 Compound Interest Calculator

**MGMT 310 Mini-Project 1: Ship Something Using DRIVER Loops**

A web-based compound interest calculator that visualizes investment growth over time, built using the DRIVER methodology and applying concepts from Session 2's Time Value of Money studies.

## 🎯 Project Overview

This tool calculates and visualizes compound interest using the formula **FV = PV × (1 + r)^n** from our Session 2 coursework. Built through iterative DRIVER loops to demonstrate the power of compound interest with interactive charts.

### Live Demo
- **Replit**: [View Live Calculator](https://replit.com/@your-username/compound-interest-calculator)
- **GitHub**: [Source Code](https://github.com/amanic75/310MiniProject)

## ✨ Features

### Version 2.0 (Current)
- ✅ **Interactive Calculator** - Input initial investment, interest rate, and time period
- ✅ **Real-time Visualization** - Chart.js powered growth curve showing year-by-year progression
- ✅ **Currency Formatting** - Professional display of financial results
- ✅ **Input Validation** - Prevents errors with proper form validation
- ✅ **Responsive Design** - Works on desktop and mobile devices
- ✅ **Mathematical Accuracy** - Validated against Python calculations

### Version 1.0 (Loop 1)
- ✅ Basic compound interest calculation
- ✅ Simple web interface
- ✅ Core functionality working

## 🚀 How to Use

1. **Enter your investment details**:
   - Initial Investment (in dollars)
   - Interest Rate (annual percentage)
   - Time Period (in years)

2. **Click "Calculate Future Value"**

3. **View your results**:
   - Final investment value
   - Total growth amount  
   - Interactive growth chart showing yearly progression

## 📊 Example Scenarios

| Initial Investment | Interest Rate | Years | Final Value |
|-------------------|---------------|-------|-------------|
| $1,000 | 5% | 10 | $1,628.89 |
| $5,000 | 8% | 20 | $23,304.79 |
| $10,000 | 6% | 30 | $57,434.91 |

## 🔧 Technical Implementation

### Technologies Used
- **HTML5/CSS3** - Structure and styling
- **JavaScript (ES6)** - Core calculations and interactivity  
- **Chart.js** - Professional data visualization library
- **Replit** - Development and hosting platform

### Core Formula (From Session 2)
```javascript
// Compound Interest: FV = PV × (1 + r)^n
const futureValue = principal * Math.pow(1 + rateDecimal, years);
```

### Architecture
```
├── index.html          # Complete single-page application
├── README.md          # This file
└── Session_Three.ipynb # Complete project documentation
```

## 📈 DRIVER Loop Development Process

### Loop 1: "Just Make It Exist"
- **D**iscover: Need basic compound interest calculator
- **R**eason: Simplest version - 3 inputs, 1 output  
- **I**mplement: Built functional calculator in 90 minutes
- **V**erify: Mathematical accuracy confirmed
- **E**volve: Users wanted to SEE growth, not just final number
- **R**eflect: Building is more about deciding what NOT to build

### Loop 2: "Make It Less Crappy"  
- **D**iscover: Users wanted visual representation of growth
- **R**eason: Add Chart.js line graph showing year-by-year progression
- **I**mplement: Enhanced with interactive visualization
- **V**erify: Chart displays correctly, improves user engagement significantly
- **E**volve: Future loops could add scenario comparison, monthly contributions
- **R**eflect: Visual storytelling beats raw numbers every time

## 🎓 Academic Connection

This project directly applies concepts from **MGMT 310 Session 2**:
- **Time Value of Money**: Core FV formula implementation
- **Compound Interest**: Visualization of exponential growth effects
- **Financial Decision Making**: Interactive tool for investment scenarios
- **Mathematical Validation**: Python verification matching course methodology

## 🚀 Getting Started

### Run Locally
1. Clone this repository
2. Open `index.html` in any modern web browser
3. Start calculating!

### Replit Integration
1. Import this GitHub repo into Replit
2. Click "Run" to launch the web server
3. Share the live link with others

## 🔮 Future Enhancements (Loop 3+)

- [ ] **Monthly Contributions** - Apply growing annuity formula from Session 2
- [ ] **Scenario Comparison** - Side-by-side investment strategy analysis  
- [ ] **Inflation Adjustment** - Real vs nominal value calculations
- [ ] **Mobile App Version** - React Native implementation
- [ ] **Data Export** - CSV/PDF report generation

## 📝 Reflection

### Key Insights
> **"Building is different from coding"** - Most effort was deciding what NOT to build, not writing code.

> **"Visual beats numbers every time"** - The chart transformed user engagement completely.

> **"Iteration actually works"** - DRIVER loops made improvement systematic and manageable.

### Skills Developed
- Web development fundamentals
- Financial formula implementation  
- Data visualization techniques
- User experience design
- Iterative development methodology

---

**Built with 💚 for MGMT 310 | Fall 2024**

*This project demonstrates that finance professionals who can build tools will lead in an AI-powered world.*
