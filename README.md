### Hello



\documentclass{article}
\usepackage{array}
\usepackage{booktabs}
\usepackage{xcolor}

\begin{document}

\begin{table}[h]
    \centering
    \caption{Programming Language Usage}
    \begin{tabular}{@{}>{\columncolor{blue!20}}l >{\columncolor{blue!10}}c@{}}
        \toprule
        \textbf{Programming Language} & \textbf{Usage Percentage} \\ \midrule
        R                             & 83.7\%                     \\ 
        Python                        & 16.3\%                     \\ \bottomrule
    \end{tabular}
    \label{tab:usage}
\end{table}

\end{document}
