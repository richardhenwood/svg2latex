
Homepage: 
--------
https://sites.google.com/site/richardhenwood/project/svg2latex2?authuser=0

Example inclusion:
-----------------

\documentclass[11pt,a4paper,twoside]{report}      %% LaTeX2e document.
\usepackage{graphicx}                %% Preamble.
\usepackage{color}

\begin{document}

\begin{figure}
\begin{center}
\scalebox{1.0}{\input{./somelatexfile.tex}}

\caption{a test of inkscape latex export extension.}

\label{fig:latexexport}
\end{center}
\end{figure}
\end{document}
