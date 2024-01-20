# pandas-challenge
Module 4 Challenge Repo

I adjusted a few elements that were provided in the code for accuracy:

- When calculating the pass rates for the subjects, I subtracted the calculatioon from 100 and printed the resulting difference. This gave pass rate numbers that better aligned with the data (I went from pass rates in the single digit %'s to pass rates in the 90%s).

- I adjusted the code in cell 11 when calculating the overall pass rate to a "+" symbol from an "&" symbol. My experience when writing the code as written did not seem to conform properly and I believe the "&" symbol was operating as more of an "or." the "+" symbol forced the calculation to ensure the student was passing BOTH subjects to count. This slightly lowered the resulting percentage, which was more in line with other calculations.


Resources:

Why the Notebook created from Git Bash did not work - learned to create the new file from within the Jupyter UI:

https://discourse.jupyter.org/t/why-do-the-file-that-was-created-using-git-bash-command-cannot-be-opened-w-jupyter-notebook/16065

Formatting a pandas Dataframe column to percentage:

https://stackoverflow.com/questions/23981601/format-certain-floating-dataframe-columns-into-percentage-in-pandas