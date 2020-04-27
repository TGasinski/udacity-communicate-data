# udacity-communicate-data
This project was part of the Udacity Data Analyst Nanodegree program. For the assignment, I systematically explored a dataset and produced a short presentation with selected visualizations. 

# Motivation
I graduated from Udacity's Data Analyst Nanodegree program in April 2020. As part of the program, I was tasked with selecting a dataset, systematically exploring chosen variables, and producing a short presentation illustrating interesting properties, trends, and relationships that I discovered. I chose a dataset from Prosper Loan, a California-based FinTech which facilitates peer-to-peer loans. Prospective borrowers request personal loans through Prosper, with individual or institutional investors choosing who to fund. The loans, worth anywhere from 2,000 to 40,000 USD, are distributed through Prosper. Prosper also collects and allocates payments and interests from borrowers to lenders. Investors make lending decisions based on a borrower's credit score, rating, and history, as well as the category of the loan ([source](https://en.wikipedia.org/wiki/Prosper_Marketplace)). As someone also working in the FinTech industry, in mobile banking, I was excited to learn more about a different aspect of the sector. 

# Project Rubric
The goal of this project was to:

+ Supplement statistics with visualizations to build understanding of data.
+ Choose appropriate plots, limits, transformations, and aesthetics to explore a dataset, allowing you to understand distributions of variables and relationships between features.
+ Use design principles to create effective visualizations for communicating findings to an audience.

# Data Sources
The dataset itself was provided through Udacity's Data Analyst Nanodegree program, but similar historical data can also be obtained directly through Prosper via an API, as long as the requester has a valid Prosper account ([source](https://prosper.zendesk.com/hc/en-us/articles/210013083-Where-can-I-download-Prosper-loan-data-)). Documentation for the dataset is available through [Udacity](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) or [Prosper](https://www.prosper.com/Downloads/Services/Documentation/ProsperDataExport_Details.html).

# How to use
To run the .ipynb files, download the dataset from the /input folder. The original dataset was too large to be uploaded, but a smaller version with relevant columns was able to be uploaded in its place. Comment out cells #4, 5, 8, 9 and 10 in the 'exploratory-analysis.ipynb' file and upload the 'borrower.csv' file from the /input folder by adding a pd.read_csv() line to cell #12. To view the final output, there are two options: 
1. Run the 'explanatory-analysis.ipynb' file and convert to a slide deck using the 'output_toggle.tpl' file from the /input folder. This template file was written by a contributer to the nbconvert project and the original source can be viewed here: https://github.com/damianavila/blog/blob/master/posts/hide-the-input-cells-from-your-ipython-slides.ipynb
2. Open the 'explanatory-analysis.slides.html' file

# Project License
This project was submitted by Theresa Gasinski as part of the Udacity Data Analyst Nanodegree.

As part of Udacity Honor code, your submissions must be your own work, hence submitting this project as yours will cause you to break the Udacity Honor Code and the suspension of your account.

Me, the author of the project, allow you to check the code as a reference, but if you submit it, it's your own responsibility if you get expelled.

Copyright (c) 2020 Theresa Gasinski

Besides the above notice, the following license applies and this license notice must be included in all works derived from this project.

# MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
