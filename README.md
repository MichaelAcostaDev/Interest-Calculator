# 💰 Interest Calculator

A simple and interactive web application for calculating **simple and compound interest** and understanding how money grows over time.

The project was built to make interest calculations easier to understand through clear results, formulas, visual charts and a dynamic growth table.

Instead of only returning a final number, the calculator lets you **calculate, compare and understand how your money grows over time.**

## ✨ Features

* 💵 **Simple Interest Calculator**
* 📈 **Compound Interest Calculator**
* 🔄 Switch between simple and compound interest
* 🧮 Automatic calculations in real time
* 📊 Interactive line, area and bar charts
* 📋 Dynamic growth table
* 💡 Short explanations of simple and compound interest
* 📐 Displays the formula used for each calculation
* 🌐 Automatic English / Spanish language detection
* 📱 Fully responsive design
* 🖱️ Interactive chart tooltips
* 💱 Localized currency and percentage formatting
* ♿ Semantic HTML and accessible form controls
* ⚡ Lightweight frontend with no framework

## 🧮 How It Works

The calculator supports two different types of interest.

### Simple Interest

Simple interest is calculated only from the original amount of money invested.

The formula used is:

```text
I = P × r × t
```

Where:

* `I` = Interest earned
* `P` = Initial principal
* `r` = Interest rate
* `t` = Time

The final amount is calculated with:

```text
A = P(1 + rt)
```

### Compound Interest

Compound interest is calculated from the original principal **plus the interest accumulated over time**.

The formula used is:

```text
A = P(1 + r/n)^(nt)
```

Where:

* `A` = Final amount
* `P` = Initial principal
* `r` = Annual interest rate
* `n` = Number of compounding periods per year
* `t` = Time

This allows the application to show how the difference between simple and compound interest grows over time.

## 📊 Charts

The application includes visual representations of the calculated results.

### Growth Over Time

Shows how the total balance changes throughout the selected period.

This makes it easier to see the progression instead of looking only at the final result.

### Interest Earned

Shows how much interest is generated during each period.

This helps visualize how the accumulated interest changes over time.

### Simple vs Compound

Compares both methods using the same initial values.

The chart makes the difference between the two calculation methods easier to understand, especially over longer periods.

Each view can be displayed as a line, area or bar chart. Charts resize with their
container, animate when values change, and include interactive period tooltips.
The animation respects the operating system's reduced-motion preference.

## 📋 Growth Table

The calculator also generates a detailed table based on the selected calculation.

Each period contains:

```text
Period
Starting Balance
Interest
Ending Balance
```

This provides a more precise view of the same data represented in the charts.

The table and charts are generated from the same calculation data so that the information remains consistent.

## 🌐 Internationalization

The application supports:

* 🇺🇸 English
* 🇪🇸 Spanish

There is no language selector.

Instead, the application automatically detects the browser language:

```text
Spanish browser → Spanish interface
Other languages → English interface
```

Spanish locales such as `es-DO`, `es-ES` and `es-MX` are recognized automatically.

All interface content is translated, including:

* Buttons
* Labels
* Descriptions
* Validation messages
* Form elements
* Chart titles
* Chart labels
* Tooltips
* Table headers
* Formulas and explanations
* Footer content

Number and currency formatting also adapts using the browser's locale.

## 📱 Responsive Design

The interface is designed to work across:

* Mobile phones
* Tablets
* Laptops
* Desktop monitors

On smaller screens, the calculator changes from a multi-column layout to a single-column layout.

Charts, forms, results, tables and navigation adapt to the available space without requiring horizontal page scrolling.

The mobile chart is intentionally compact so it does not dominate the screen or unnecessarily increase the page height.

## 🚀 Usage

You don't need a backend or database to use the application.

Clone the repository:

```bash
git clone https://github.com/MichaelAcostaDev/Interest-Calculator.git
```

Open the project:

```bash
cd Interest-Calculator
```

Install the TypeScript compiler and generate the browser JavaScript:

```bash
npm install
npm run build
```

Then serve the project root with any static web server and open the local URL.
`npm run check` runs TypeScript checks without changing the generated files.

The main structure is:

```text
interest-calculator/
├── index.html
├── src/
│   └── main.ts
└── README.md
```

## 🛠️ Technologies

The project was intentionally built without a frontend framework.

* **HTML5** — Semantic page structure and accessible form elements
* **Tailwind CSS** — Responsive layout and UI styling
* **TypeScript** — Calculations, application logic, state and interactions
* **TypeScript compiler** — Strict type checking and browser JavaScript output
* **Font Awesome** — Interface icons
* **Intl API** — Currency, percentage and locale formatting
* **Browser APIs** — Theme and language detection

No React, Vue, Angular, Next.js or other frontend framework is required.

## 🧠 What I Practiced

This project was also a practical exercise in building a complete frontend application without relying on a framework.

Some of the main concepts involved are:

* TypeScript interfaces and typed functions
* Mathematical calculations
* DOM manipulation
* Event handling
* Form validation
* Responsive UI design
* Internationalization
* Localization
* Theme management
* Data visualization
* Dynamic table generation
* State management
* Browser APIs
* Accessible HTML
* Responsive component design

The main idea was not just to build a calculator, but to turn a relatively simple mathematical problem into a small and complete user experience.

## 🎯 Purpose

The goal of **Interest Calculator** is to make financial mathematics easier to understand.

Interest calculations can look simple when reduced to a formula, but seeing the numbers change over time provides a much better understanding of how interest actually works.

The combination of:

* Calculations
* Formulas
* Charts
* Tables
* Explanations

makes the result easier to interpret instead of simply displaying a final amount.

## 📸 Preview

The application uses a clean, minimal interface focused on the numbers and the information being calculated.

The design intentionally avoids unnecessary visual effects and focuses on:

* Clear typography
* Structured spacing
* Readable numbers
* Simple controls
* Responsive layouts
* Useful visualizations

The objective is to make the interface feel like a real small product rather than a basic classroom calculator.

---

## 👨‍💻 Author

**Michael Acosta**

Full Stack Developer focused on web development, programming and building practical projects.

* ⭐ If you find this project useful, consider giving the repository a **star**.
* 🐙 Follow me on [GitHub](https://github.com/MichaelAcostaDev)
* 💼 Connect with me on [LinkedIn](https://www.linkedin.com/in/michael-acosta-dev/)

---

### ⭐ Support the Project

If you like this project:

1. ⭐ **Star the repository**
2. 🐙 **Follow me on GitHub**
3. 💼 **Connect with me on LinkedIn**
4. 📤 Share the project with someone learning about interest and finance

Thanks for checking it out.