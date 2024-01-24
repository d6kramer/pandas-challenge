# pandas-challenge
Module 4 Challenge Repo

The actual submission file to be considered is "PyCitySchools_Final."

I left the starter file in the repo, as well as a "working" file ("PyCitySchools_Working) to show the various files I had created while working on this project. I discovered the value of keeping a working Notebook and making copies in order to experiment and preserve working (or close to working) code. This was also valuable when accessing aid such as tutoring, since I found that changes made directly into my only notebook could cause problems down the line and prevent me from referencing prior material that could be utilized.

**Note: Due to some issues when using the provided formatting further into the challenge, I opted to remove this as an optional "nice to have." The data contained in the tables I produced was still legible/interpretable from a data analysis standpoint and did not affect my ability to find trends. I did have a tutor show one option to get around the formatting issue, but opted not to implement the method and saved the information on a copy of the challenge not contained in my repo folder.


Resources:

Why the Notebook created from Git Bash did not work - learned to create the new file from within the Jupyter UI:

https://discourse.jupyter.org/t/why-do-the-file-that-was-created-using-git-bash-command-cannot-be-opened-w-jupyter-notebook/16065

Formatting a pandas Dataframe column to percentage:

https://stackoverflow.com/questions/23981601/format-certain-floating-dataframe-columns-into-percentage-in-pandas

**Note that this actually contributed to some later problems in the project since it re-classifies objects in a way that didn't play nice with code further down in the challenge. I did utilize this, however in the district overal summary.

Getting a proper formatted count of school names by type (cell 11 in notebook) - ".max" method:

My tutor, Geronimo, showed me this method of collecting the schools by type, which eliminated extraneous brackets and quotation marks that showed up with my original line of code.