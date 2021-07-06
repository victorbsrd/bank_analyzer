[UNDER CONSTRUCTION]
This is a code I developped for a fun personal project.
I didn't finish it, but ot could be great to see how far we can go.

END GOAL:
Given a bank account, and accessing the data, 1) give intersting and understandable KPIs 2) try to classify every transaction (similar to what Bankin' is doing) 3) build a detector that spots outliers (strange transactions)

INPUT:
The input is a set of csv document (typically output by my textractor script) with 5 columns:
0) Date: a string representing a date
1) Valeur: a string representing a date
2) Nature: de l'opération: a string representing a string
3) Debit: a string representing a float (! some NaN values)
4) Crédit: a string representing a float (! some NaN values)

Then run the preprocessing notebook
Then run the exploit_data notebook (I stopped at using the Google API) 
