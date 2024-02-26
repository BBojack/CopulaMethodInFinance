# CopulaMethodInFinance

###
Over the past few decades, the dependency structure of assets and risk factors has been playing a
critical rule in financial market. In trading strategy, a popular method named pair trading is basically built upon the estimated correlation among different financial products. In risk management,
the new term correlation risk [1] is meant to identify the shift of risk exposures triggered by changes
in correlation of risky assets. In portfolio management, a reliable estimate of the dependency of underlying assets helps investors do a risk arbitrage efficiently. To better investigate the dependency
structure, the dependency functions or copula functions come into play.

###
Copula methods in finance can be briefly summarized as a bottom-up methodology which constructs the joint distribution of underlying assets by the marginal distributions of each asset which
are easily to observe. Because of the flexibility of copula functions, this project will mainly focus on the application of copula in multivariate process which represents a collection of variables
representing the value of each asset or risk factors.( [1]) One of the advantages of using copula to
model dependency rather than the vector autoregression(VAR) is that the we can extent copula
model to other non-linear of non-Gaussian cases which are not available in the VAR. What’s more,
the dependency structure captured by copula method is more complete than that from the sample correlation coefficient which only reveals the strength of the linear dependence between the
underlying random variables.

###
The structure of this project as follows:
• Introduce the basic idea of copula and techniques used in parametric and nonparametric
estimation.
• Estimate the tail dependency structure of S&P500 and DAX30 before and after the financial
crisis in 2008 with nonparmatric method.
• Estimate the dynamic tail dependency structure of S&P500 and DAX30 in the period around
the financial crisis in 2008 with different copulas such as Gaussian copula,Student t copula
and Joe-Clayton copula.
• Compare the results

###  Plot of time varying TDCs when Joe-Clayton-copula is used


![JC](https://github.com/BBojack/CopulaMethodInFinance/assets/42468209/45b68f7c-afb8-4f6d-af64-4b127c29201a)


