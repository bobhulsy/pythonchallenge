

## Pybank

The `pybank.ipynb` notebook contains Python code that reads in financial data from a CSV file, performs financial analysis, and writes the results to a text file. The notebook uses the `csv` module to read in the `budget_data.csv` file, which contains financial data for a company over a period of several years.

The notebook calculates various financial metrics, such as the total number of months, the total profit/loss, the average change in profit/loss, and the greatest increase and decrease in profits. It then formats the results as a string and writes them to a file called `financial_analysis.txt`.

The notebook is organized into several sections, each of which performs a specific task. The first section reads in the financial data from the CSV file and initializes variables to hold the financial metrics. The second section loops over each row in the CSV file, incrementing the total number of months and adding the profit/loss to the total. It also calculates the change in profit/loss since the previous month and adds it to a list of changes. The third section checks if the current change in profit/loss is the greatest increase or decrease in profit/loss and stores the date and amount if it is. The final section formats the financial analysis results as a string and writes them to a file.

## Pypoll

The `pypoll.ipynb` notebook contains Python code that reads in election data from a CSV file, performs election analysis, and writes the results to a text file. The notebook uses the `csv` module to read in the `election_data.csv` file, which contains data on the votes cast in an election.

The notebook calculates various election metrics, such as the total number of votes, the percentage of votes each candidate received, and the winner of the election. It then formats the results as a string and writes them to a file called `election_analysis.txt`.

The notebook is organized into several sections, each of which performs a specific task. The first section reads in the election data from the CSV file and initializes variables to hold the election metrics. The second section loops over each row in the CSV file, incrementing the total number of votes and adding the vote to the candidate's vote count. The third section calculates the percentage of votes each candidate received and adds it to the candidates dictionary. It also checks if the current candidate has more votes than the current winner. The final section formats the election analysis results as a string and writes them to a file.
