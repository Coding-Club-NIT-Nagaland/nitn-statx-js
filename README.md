# 🧮 NITN-StatX (Java)

**NITN-StatX** is a modular, high-performance probabilistic and statistical library in **Java**, built by **NIT Nagaland Coding Club**.  
Perfect for analytics, data science, and backend systems.

## 🚀 Features
- Common Distributions (Normal, Uniform, Exponential, Poisson)
- PDF, CDF, Quantiles, and Random Sampling
- Hypothesis Tests (t-test, Chi-Square, Kolmogorov–Smirnov)
- Random Sampling & MCMC (Metropolis-Hastings)
- Bayesian Updating (Conjugate Priors)
- Time Series Utilities (Moving Average, ARIMA skeleton, Kalman Filter)
- Deterministic RNG with seeding support

## 🧰 Installation (Maven)
```xml
<dependency>
  <groupId>edu.nitn</groupId>
  <artifactId>nitn-statx</artifactId>
  <version>0.1.0</version>
</dependency>
```

## 🧪 Quick Start

```java
import edu.nitn.statx.distributions.Normal;

public class Main {
    public static void main(String[] args) {
        Normal dist = new Normal(0.0, 1.0);
        double p = dist.cdf(1.96);
        double[] samples = dist.sample(1000);
        System.out.println("CDF at 1.96: " + p);
    }
}
```

## 📂 Project Structure

```
nitn-statx-java/
├── src/main/java/edu/nitn/statx/
│   ├── distributions/
│   ├── stats/
│   ├── sampling/
│   ├── bayesian/
│   └── timeseries/
├── src/test/java/
├── examples/
└── README.md
```

## 🤝 Contributing

We welcome contributions from students and open-source developers:

1. Fork the repository  
2. Clone your fork and create a new branch  
3. Implement your feature or fix with unit tests  
4. Run `mvn test` to ensure all tests pass  
5. Submit a Pull Request  

Please follow standard Java conventions and write clear, documented code.

## 🧑‍💻 Maintainers

* NIT Nagaland Coding Club  
* [GitHub Organization](https://github.com/NITN-Coding-Club)
