Features
id: Unique identifier for each loan application. This is often used to track and differentiate each record.

person_age: The age of the individual applying for the loan. Age can provide insights into financial maturity and risk.

person_income: The annual income of the individual. Higher income generally indicates a greater ability to repay loans.

person_home_ownership: This feature indicates whether the individual owns a home, rents, or has another form of housing. Common values might be "Own", "Rent", or "Mortgage". Homeownership can be a sign of financial stability.

person_emp_length: Length of employment (in years) for the individual. Longer employment tenure might suggest job stability, which can be a positive factor in loan approval.

loan_intent: The purpose of the loan, such as "debt consolidation", "home improvement", "business", or "medical expenses". Loan purpose helps lenders understand the reason behind the borrowing.

loan_grade: A rating assigned to the loan that reflects the creditworthiness of the borrower. Grades might range from A to F, with A being the best.

loan_amnt: The amount of money the individual is requesting as a loan.

loan_int_rate: The interest rate that will be charged on the loan. Higher rates are typically associated with higher-risk loans.

loan_percent_income: The percentage of the individual’s income that the loan payments will represent. A lower percentage is generally more favorable for loan approval, as it indicates the loan is more affordable relative to income.

cb_person_default_on_file: Indicates whether the individual has a history of defaulting on a loan or credit card (Yes/No). A history of defaults can be a major negative factor.

cb_person_cred_hist_length: The length of the individual's credit history, typically measured in years. A longer credit history often reflects more financial experience and reliability.

loan_status: The current status of the loan, such as "Approved", "Rejected", or "Pending". This is often the target variable in a loan approval model.
