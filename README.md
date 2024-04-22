# LEAVES
Based on the open datasets of ASAS-SN, Gaia and ZTF, we construct a compatible light curve dataset named LEAVES for automated recognition of variable stars, from the work " LEAVES: An Expandable Light Curve Dataset for Automatic Classification of Variable Stars ". The dataset contains a total of 979,962 variable and 134,592 non-variable light curves, in which the supported variables are divided into 6 superclasses and 9 subclasses. We validate the compatibility of the data set through experiments and use it to train a hierarchical random forest classifier. 


We provide the light curves of these objects by class in csv files in https://drive.google.com/drive/folders/1R8r4oBXKxLdC6puUkS4IUx4VTY_lTluW. The composition of LEAVES is shown in table below:

\begin{table}[]
\begin{tabular}{c|c|c|c|c|c|c}
\hline
Class & Subclass & ASAS-SN\_v & ASAS-SN\_g & ZTF & Gaia & Total \\ \hline
\multirow{2}{*}{Eclipsing binaries(EB)} & EA & 37463 & 10695 & 29198 & \multirow{2}{*}{6785} & \multirow{2}{*}{421025} \\
 & EW & 57058 & 22724 & 257093 &  &  \\ \hline
Rotational variables(ROT) & ROT & 16850 & 4202 & 98060 & 0 & 119112 \\ \hline
\multirow{2}{*}{RR Lyrae(RR)} & RRAB & 13244 & 10981 & 17598 & 840 & 61366 \\
 & RRC & 5959 & 3624 & 9120 &  &  \\ \hline
Cepheids(CEP) & CEP & 1003 & 405 & 1074 & 2 & 2484 \\ \hline
\multirow{2}{*}{Long period variables(LPV)} & SR & 140997 & 143376 & 46738 & \multirow{2}{*}{5095} & \multirow{2}{*}{355374} \\
 & M & 7884 & 6133 & 5151 &  &  \\ \hline
Delta Scuti(DSCT) & DSCT & 3718 & 939 & 13944 & 0 & 18601 \\ \hline
Non-var &  & 134592 &  &  &  & 134592 \\ \hline
\end{tabular}
\end{table}


The full data set and machine learning models are also available and will be released officially at the China National Astronomical Data Center. 
