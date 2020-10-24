# Construction Loan Estimator
This project is an attempt to calculate the expected outcomes of a constuction loan given user defined parameters. These parameters will be used to determine the year-by-year costs and equity. This can also be extended to compare to the outcomes of renting as well. This should assist in the decision making process for those that are considering building vs. renting.

## Assumptions
This project is based on the process commonly called a "construction to permanent loan" rather than a "construction only loan." This type of loan is designed to provide the initial funds during the construction period, then convert the remaining loan value into a permanent loan (also called a mortgage, just like a normal home purchase).

In addition to this, the default values of some parameters are based on research online and each is detailed in the parameters section below. This includes macro-economic values like inflation and prime mortgage rates, as well as average based on the locations that are of interest to me. Please feel free to swap these parameters just like the others.

As part of the construction loan process, it is assumed that the disbursements (amounts paid from lender to builder) are continuously increasing during the construction term. The interest payments are only made on the cumulative disbursements and as such increase until the construction period is complete.

## Parameters
The following parameters are used in the calculations and described here:
* Property Cost
  * The total cost of purchasing the land on which the home will be built
* Construction Cost
  * The total cost of constructing the home not including the land
* Loan Term
  * The number of years in which payments will be made
* Estimated Value upon Completion
  * The estimated home value of the project once built (for equity)
* Contruction Term
  * The number of years that the construction project will take to complete
* Down Payment
  * The initial down payment (this is subtracted from the total loan amount)
* Inflation
  * The rate of inflation that will be assumed flat over the loan period
* Closing Costs
  * As this is a "single close" construction loan, this is only the proportion of the cost of the full loan, executed once at the beginning of term
* Square Footage
  * The estimated completed square footage of the home
* Maintenance Cost
  * The yearly maintenance cost
* Property Tax Assessment Rate
  * The rate of taxation on the value of the home
  * This will be re-evaluated each year
* Property Tax Mill Levy
  * The multiplier on the assessment rate
* Initial Rent Monthly Payment
  * The monthly payment for rent
* Rent Growth Rate
  * The annual rate of growth in the cost of renting
* Home Appreciation Rate
  * The annual rate of growth of the value of the home
* Loan Interest Rate
  * The interest rate on the long term mortgage and the construction period
* Total Loan Amount
  * The total amount of the loan minus the down payment