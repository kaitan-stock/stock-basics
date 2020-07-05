# Discoutned Cash Flow 估值方法

## 使用计算工具进行公司估值：[DCF Calculator](https://tradebrains.in/dcf-calculator/)

### Inputs

- Free cash flow `过去3年的平均free cash flow`
- Total cash `资产负债表的total cash from`
- Total debt `资产负债表的current debt + long term debt`
- Total number of outstanding shares `shares outstanding（取自key statistics-share statistics）`
- Expected growth rate `未来5年的growth rate（取自analysis-growth estimate）`
- Disoutn rate `WACC`
- Last FCF multiple  `enterprise value / EBITDA （取自Statistics）`
- Margin of Safety (%) `可以设置为10%-30%`

  > As the future of any company is unpredictable and moreover, no valuation method is
  perfect, we would recommend you to always take a margin of safety in order to give yourself
  (and your assumptions) a benefit of doubt. 
  A 10-30% discount on the intrinsic value can be considered as a good margin of safety.

  因为公司未来的不确定性，没有一种估值方法是万全的，所以给自己留出余地：将估值保守减少10-30%

### Outputs

- Intrinsic value per share `计算 margin of safety 之后的值`
- Current Share price `Input`
- Overvalued (%) `正代表overvalued`

  > If the above value is positive, then the stock is OVERVALUED compared to the current
  market price of the stock. Else, if it is negative, then the stock is UNDERVALUED at the
  current price.



# WACC计算工具：[WACC Calculator](https://www.calkoo.com/en/wacc-calculator)

<img src="https://i.upmath.me/svg/%0AWACC%20%26%3D%5Cfrac%7BE%7D%7BD%2BE%7D%5Ctimes%20r_%7BE%7D%2B%5Cfrac%7BD%7D%7BD%2BE%7D%5Ctimes%20r_%7BD%7D%5Ctimes%20(1-t)%5C%5C%0A" alt="
WACC &amp;=\frac{E}{D+E}\times r_{E}+\frac{D}{D+E}\times r_{D}\times (1-t)\\
" />

- Cost of equity (rE) = Risk Free Rate(RF) + Market Risk Premium(RM-RF) x BETA
  - RF - Market - US Treasury Bonds Rates - TNX
  - RM - 直接谷歌搜索 " average stock market return"， 目前是10%
  - BETA - from Summary
- Total equity (E)
  - Market Cap (取自 Key Statistics - Valuation Measures)
- Cost of debt (rD)
  - CoD (Pre-Tax) = Total Interest Cost Incurred/Total Debt x 100
  - CoD (Post-Tax) = Total Interest Cost Incurred x (1 - Effective Tax Rate)/Total Debt x 100
  
    > Total Interest Cost Incurred 取自 Income Statement-Interest Expense
  
  - Total debt (D)
  - Corporate tax rate (t) `Income Before Tax/Income Tax Expense (取自IC）`


