# Session3Assignment3

Implement the calculation of credit card,
Use below mentioned formulas and steps while writing logic:
1. card balance will become your principal.
2. monthlyfloatInterestPaid= Math.round((principal * (rate / (100 * 12))))
3. monthlyPrinciple= minimum_payment-monthlyfloatInterestPaid
4. monthlyBalance=principal-monthlyPrinciple
5. For counting next month use below formula and repeat the step 2,3,4,5.
 principal= monthlyBalance
6. For calculating how many months you have to pay use count variable for step 5.
