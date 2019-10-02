# BetaNYC-Hackathon-2019-09-21

Still a little messy, but this code was written for the Mobility for All Abilities on 9/21/2019 as part of the 'Reliable Access to Subways' team organized by TransitCenter and United Equal Access NY. Created while working alongside [Jen McKaig](https://github.com/jenmckaig]).

Input is a PDF file in the local directory, the first page of the PDF and the last page of the PDF. The function adjusts the first page to account for zero-based numbering. It will output a csv file back into the directory.

The function `pdf_transform_v5` is available in `Final Function.ipynb`, which has worked to convert 8 of the 10 available PDFs in this repository. As of 10/2/2019, the function isn't commented (yet). Once I'ce got the last two working, I'll add comments and explain how it's all working.