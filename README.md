# GeneProtHub

"After some hours of intense work, you have just finished your data analysis in R (or in any other commercial statistical package). Now you have proudly ended up with a shortlist of genes/proteins that are diferentially expressed or that are important in the context of your experiment. Great! But... what do they actually mean? Ok, I have to check them online... buff... this would cost me quite some time (and mental energy that I don't have right now) to do it: several data bases, different layouts, a lot of info to be filtered out... is there any easy and straight forward way of getting concrete and useful information about genes and/or their corresponding proteins?"

Have you ever been in this situation? Probably you did if you were doing molecular research. That is the existential reason of **GeneProtHub**: to facilitate researchers in their assessment of *omics* results. It is a very simple application that makes queries to mainstream databases of genes and proteins (*ensembl*, *Uniprot* and *Human Protein Atlas*) retrieving some important, useful and concisely selected information about them. And just answering a couple of pretty simple questions!

REQUIREMENTS:

-   Python 3.10 or higher

-   The program does **not** run without an active internet connection, so please make sure that you are connected.


To use the application:

1)  Clone the repository in your computer.

2)  Open the terminal or your favourite python compiler and go to the folder where the repository has been cloned

3)  Run "./python3 question_flow.py" in the terminal or the whole file "question_flow.py" in your python compiler.

And that's all! Just answer the questions in the screen and you will get all the gene or protein information that you need.
