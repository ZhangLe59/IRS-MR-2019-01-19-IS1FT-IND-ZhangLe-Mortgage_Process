# Worksop Project Submission
# IRS-MR-2019-01-19-IS1FT-IND-ZhangLe-Mortgage_Process
# Name: ZhangLe  StudentNumber:A0176176W
=======================


1. Import Zip folder into JBPM
2. Rule added : DecisionTable - MortgageDecisionTable
   - mortgagecalculation : IF Applicant Annual income between (1000,9999) THEN Mortgage Amount is 3000
3. Rule added : DecisionTable - MortgageMachineResoningDT
   - MortgageMachineReasoningDT :
      Add AgeLess, ageGE, creditating condition.

4. Test Procedure:
  Input :  
  DownPayment-50000; Years of amortization-20; Age-25; CreditRating:10; Hasjob; OwnHouse;
  AnnualIncome-110000;SalePrice-250000;
  Result :
  Mortgage amount:200000; Inlimit
  
