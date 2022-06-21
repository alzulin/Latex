# Modelo de avaliação tex

Copiar o código aqui:

````

\documentclass[12pt,a4paper]{report}
\usepackage{amssymb,amscd,amsfonts,amsmath,graphicx,amsthm}
\usepackage[utf8]{inputenc}
\usepackage{latexsym}
\usepackage[brazil]{babel}
\usepackage[ansinew]{inputenc}%para usar acentos comuns
\usepackage{mathrsfs}
\usepackage{graphicx}
\usepackage{fancyhdr}
\usepackage[margin=2cm]{geometry}
%\usepackage[top=2cm,bottom=2cm,left=2cm,right=2cm]{geometry} %%margens
\usepackage{makeidx}
\usepackage{setspace}
\usepackage{wrapfig}
\usepackage{fancyhdr}
\usepackage{array}
\usepackage{changepage}
\usepackage{multicol}
\usepackage{enumerate}
%\renewcommand{\baselinestretch}{1.5}

%=========================================================
%------------DIGITE AQUI
%=========================================================
\newcommand{\escola}{COL. EST. MARCO ANTÔNIO PIMENTA}
\newcommand{\ensino}{Ensino Fundamental e Médio}
\newcommand{\disciplina}{Matemática}
\newcommand{\professor}{Zulin}
\newcommand{\ano}{2022}
\newcommand{\turma}{3ºA}
\newcommand{\prova}{Prova de Recuperação do 1º Trimestre}
\newcommand{\valor}{6,0}
%=========================================================

\renewcommand{\familydefault}{\sfdefault}

\setlength\extrarowheight{3pt}

\fancypagestyle{plain}{%
  \fancyhf{}
  \renewcommand{\headrulewidth}{0.1pt}
  \fancyhead[L]{\includegraphics[width=0.05\textwidth]{logo_seed}}
  \fancyhead[R]{\thepage}
  \fancyhead[C]{\textbf{\escola \ - \ensino} \\
                \small{Professor \professor \hspace{2.5cm} \disciplina}}

\renewcommand{\headrulewidth}{0.5pt}
	%Footers
	\fancyfoot[L]{\today}
	\fancyfoot[C]{}
	\fancyfoot[R]{Boa Prova!}
\renewcommand{\footrulewidth}{0.5pt}
       
}

\pagestyle{plain}

\begin{document}
\begin{center}
\begin{tabular}{|p{14.5cm}|p{1.73cm}|}
\hline
 \prova \hfill Turma: \turma \hfill  valor: \valor \newline \newline
 Aluno(a): \hspace{7.7cm} Nº: \hfill  Data: \ \ \  / \ \ \  /\ano & NOTA \\
\hline
\end{tabular}
\end{center}
\vspace*{0.02cm}
%\begin{multicols}{2}
%\setlength{\columnseprule}{1pt}
\begin{enumerate}
  \item

  
\end{enumerate}
%\end{multicols}
\end{document} 


```
