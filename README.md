# University-of-Electronic-Science-and-Technology-of-China-Bachelor-Thesis-Overleaf for International Undergraduate Students
Well detailed Overleaf Latex version of University of Electronic Science and Technology of China (UESTC) Bachelor's Thesis for International Undergraduate students who wish to format their final year thesis using overleaf latex template rather than the traditional methods which can be stressful and challenging.

# Description
UESTC Thesis Format for International Undergraduate Students has always been in word doc. template which makes it difficult for final year undergraduate international students to meet up with all the necessary formats. To this, I have rewritten the latex format to suit the International undergraduate students. 

# Disclaimer
This is an independent task and the author of this repository has no cooperation with the authorities of the University of Electronic Science and Technology of China. You are freely permitted to use this for your document formatting.

# Addition
You can always use the following links for any extra formatting:

a) for table generation: https://www.tablesgenerator.com/

b) for equation geeneration: https://latexeditor.lagrida.com/

![Bachelor Cover](https://user-images.githubusercontent.com/61402731/150671042-04cb0708-319e-4c2c-aea8-e2c44678b814.png)

Front view of the Bachelor Thesis

# Structural display of the thesis contents
On opening the 'chapter' folder, each chapter is organized in a file called .tex (eg c2.tex).

On opening the 'pic' folder, each chapter folder has its own folder wherein are attached images/diagrams in any extension format (.png/.jpg).

![environment](https://user-images.githubusercontent.com/61402731/150673083-42579b54-8d25-4c48-a351-3063d8382f2f.png)

An image showing how the contents are organized


# Remember:
Kindly note that for the compilation of your work, always run from the 'main_file.tex and click on "Recompile' on a green background located on the right hand side.

# New Addition, 2022
### 2022 UESTC Thesis/Dissertation New Format
In 2022, UESTC made few changes to the Thesis/Dissertation format. These changes are mainly on the style of the 'Table and the Reference style'. I have provided the code to correctly effect the new style of the Table and I have also included a new source file named "thesis-uestc.bst" to handle the new changes to the reference format.

# Example 1 of the new Table style

%%%%%%%%%%%%%%%%%%%%%%%%%% TABLE 2 %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\begin{table}[h!]

 \scriptsize
 
 \centering
 
 \caption{The Distribution of Relabeled Data}
 
 \begin{tabular}{cccl}
 
\toprule

\textbf{Label}   & \textbf{Class}   & \textbf{Number}  & \textbf{Percentage} \\

\midrule

0                & No RDR       & 548                & 45.6\%  \\

1                & RDR          & 652                & 54.4\%  \\

\bottomrule

\end{tabular}

\label{tab3-1-2}

\end{table}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
