# *Integrating Fundamentals and Technicals: A Multi-Strategy Approach to Dynamic Asset Allocation*

**✏️ Introduction**: 

Traditional portfolio construction methods such as Markowitz's Mean-Variance Model, in practice, often rely on the assumption of constant asset returns and covariance over time, regardless of the time-varying behavior of financial assets. The unending pursuit of the holy grail of investing underscores the absence of an optimal strategy. Given that existing literature focuses only on single dimension of factors, this study proposes a multi-strategy approach for dynamic asset allocation strategies that integrates fundamental and technical signals.


## ⛳️ Objectives 
- Build a dynamic asset allocation strategy that has the potential to outperform static portfolios
- Examine whether a multi-strategy framework would add value to asset allocation strategies
- Extend my previous [study](https://github.com/wayne-kuanghui-shen/python-spx_pricing_vecm_modeling), from determining pricing factors to building an investment strategy

## 📍 Conclusions
- Findings: The multi-strategy dynamic portfolio outperforms static benchmarks out-of-sample
  - The dynamic portfolio strategy delivers a Sharpe ratio of 1.20, compared to 0.7 of classic 60/40 portfolio
  - The dynamic portfolio generates the highest absolute return and lowest max drawdown vs. all benchmarks
  - The dynamic portfolio has an equity beta of only 0.37 and provides diversification in recessionary regimes
  - The performance results are robust under different input and parameter settings in the model
- Implication 1: The inclusion of technical signals within a layered framework adds value
  - Incorporating technical signals produces a Sharpe ratio of 1.20, vs. 1.08 of macro-only signals
  - This means A combination of different signals captures additional risk premia with superior performance
- Implication 2: Deriving asset covariance based on the prevailing macro regime leads to better outcome
  - The full-sample covariance portfolio yields a Sharpe ratio of 0.98, vs. 1.20 of regime-based covariance
  - The suggests using macro regime-based covariance in mean-variance optimization enhances returns

## 💡 Highlights 

<img src="https://github.com/wayne-kuanghui-shen/python-multi-strat-dynamic-asset-allocation/blob/main/highlights/macro_signal.png" >
<img src="https://github.com/wayne-kuanghui-shen/python-multi-strat-dynamic-asset-allocation/blob/main/highlights/technical_signal.png" >
<img src="https://github.com/wayne-kuanghui-shen/python-multi-strat-dynamic-asset-allocation/blob/main/highlights/portfolio_design.png" >
<img src="https://github.com/wayne-kuanghui-shen/python-multi-strat-dynamic-asset-allocation/blob/main/highlights/dynamic_portfolio_weight.png" >
<img src="https://github.com/wayne-kuanghui-shen/python-multi-strat-dynamic-asset-allocation/blob/main/highlights/out_of_sample_performance.png" >
<img src="https://github.com/wayne-kuanghui-shen/python-multi-strat-dynamic-asset-allocation/blob/main/highlights/performance_visualization.png" >
<img src="https://github.com/wayne-kuanghui-shen/python-multi-strat-dynamic-asset-allocation/blob/main/highlights/performance_across_regimes.png" >
