https://apps.sfc.hk/productlistWeb/searchProduct/UTMF.do



资产类别、费率、投资范围、亮点和特点，以及相较于过去三年、五年和十年的变化



##### what's in the Key_stats

- Investment Objective
- Minimum redemption:
- Investment Strategy





##### To-Do:

- Search WIND & Bloomberg's API for HK funds products.








- 资产类别

  Boolean variable on the raw `.csv` file.  Deriv_Fund

- 费率







##### PKF structure

- Quick Facts

  - Dealing frequency
  - Base currency
  - entities

- What is this product?

- Objective and Investment Strategy

  contains the investment strategy, need to use Regular Expression

- Use of derivatives / investment in derivatives

  The Sub-Fund’s net derivative exposure may be up to {50%} of its net asset value.

- What are the key risks?

  ​	can be text analyzed.

- How has the Sub-Fund performed?

  ​	may contains images of former performance

- Is there any guarantee?

- What are the fees and charges?

  - Charges which may be payable by you
    - Initial charge/Subscription fee
      - Initial charge(payable to Investment Manager)
      - Subscription fee(payable to Trustee)
    - Switching charge(payable to Investment Manager)
    - Redemption charge/fee
      - Redemption charge (payable to Investment Manager)
      - Redemption fee (payable to Trustee)
  - Ongoing fees payable by the Sub-Fund
    - Investment management fees (payable to Investment Manager)
    - Trustee fee (payable to Trustee)
    - Performance fee
    - Administration fee
  - Other fees

- Additional Information

- Important(fixed)



#### Database Design

target_fund_list+

- Dealing frequency
  - `label`: `freq`
  - `value`: day/week/month
- Base currency
  - `label`: `currency`
  - `value`: `str` e.g USD, CNY
- entity
  - `label`: 
  - `value`: `str`
- e
  - `label`: 
  - `value`: `dict` with key as fee type, value as percent

















































