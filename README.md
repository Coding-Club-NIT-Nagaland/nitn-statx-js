# 🧮 NITN-StatX (JavaScript)

**NITN-StatX** is a lightweight probabilistic and statistical library for **Node.js** and browser environments.  
Developed by **NIT Nagaland Coding Club**.

## 🚀 Features
- PDF, CDF, Quantiles for common distributions (Normal, Uniform, Exponential, Poisson)
- Hypothesis Testing (t-test, Chi-Square, Kolmogorov–Smirnov)
- Random Sampling & MCMC (Metropolis-Hastings)
- Bayesian Updating Helpers (Conjugate Priors)
- Time Series Utilities (Moving Average, ARIMA skeleton, Kalman Filter)
- Deterministic RNG with seeding

## 🧰 Installation
```bash
npm install nitn-statx
```

## 🧪 Quick Start

```javascript
import { Normal } from "nitn-statx";

const dist = new Normal(0, 1);
const p = dist.cdf(1.96);
const samples = dist.sample(1000);

console.log("CDF at 1.96:", p);
```

## 📂 Project Structure

```
nitn-statx-js/
├── src/
│   ├── distributions/
│   ├── stats/
│   ├── sampling/
│   ├── bayesian/
│   └── timeseries/
├── examples/
├── tests/
└── README.md
```

## 🤝 Contributing

We welcome contributions from students and open-source developers:

1. Fork the repo  
2. Run `npm install`  
3. Add your feature or fix with tests  
4. Run `npm test` to verify  
5. Submit a Pull Request 🚀

Follow standard JavaScript conventions and ensure code is well-documented.

## 🧑‍💻 Maintainers

* NIT Nagaland Coding Club  
* [GitHub Organization](https://github.com/NITN-Coding-Club)
