## Models

1. **finance_residential_mortgages**
Integrates and processes loan origination and product system data to categorize loans based on their purpose and residual term. It maps loan purposes, joins origination data with product details, and applies rules to determine the EFS housing purpose and residual term. The final output includes derived rule IDs for further analysis.




## Source / Seeds

1. **RULE_ID_MAPPING**
Mapping of housing purposes to corresponding rule IDs used in a system.

2. **PRODUCT_SYSTEM**
Records of product systems including account details, product codes, balances, maturity dates, and currency information.

3. **ORIGINATION_SYSTEM**
Records of loan origination systems, capturing details such as application ID, purpose, currency, approval limit, and account ID.

4. **LOAN_PURPOSE**
Loan purpose data containing information about different lending purposes, including housing, personal, business, and leases.