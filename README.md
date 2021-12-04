# Insurance charges prediction using regression algorithm

Health Insurance companies have a tough task at determining premiums for their customers. While the health care law in the United States does have some rules for the companies to follow to determine premiums, it’s really up to the companies on what factor/s they want to hold more weightage to.

# Approch
I considered these as independent variables (columns) in the dataset:

  1. Age
  2. Sex
  3. Body mass index (bmi)
  4. Smoker (whether the person smokes)
  5. Region (where the person lives)

These independent variables are assumed to have statistical significance in determining insurance premium charges of the customer. 

We determine this by the ML principle “Lower the p-value, higher the statistical significance. More Asterisk means more statistical significance”. Asterisks are a significance code.

Compare the predicted value with the test set to know about the accuracy with which our model is predicting.
