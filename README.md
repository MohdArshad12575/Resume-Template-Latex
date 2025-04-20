\documentclass[a4paper,11pt]{article}

\renewcommand{\rmdefault}{phv} % This will set the font to Helvetica
\renewcommand{\sfdefault}{phv} % This will set sans-serif to Helvetica

\usepackage{latexsym}
\usepackage{xcolor}
\usepackage{float}
\usepackage{ragged2e}
\usepackage[empty]{fullpage}
\usepackage{wrapfig}
\usepackage{lipsum}
\usepackage{tabularx}
\usepackage{titlesec}
\usepackage{geometry}
\usepackage{marvosym}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage{multicol}
\usepackage{graphicx}
\usepackage{cfr-lm}
\usepackage[T1]{fontenc}
\usepackage{fontawesome}
\usepackage[most]{tcolorbox}
\usepackage{indentfirst} % Ensure first line indentation

% Set the margins
\geometry{left=1.5cm, top=1.5cm, right=1.5cm, bottom=1.5cm}
% Define custom colors
\definecolor{myviolet}{RGB}{140, 93, 183}  % Define custom violet color
% Set the margins
\geometry{left=0.85cm, top=0.8cm, right=0.85cm, bottom=0.2cm}

% Paragraph indentation setting
\setlength{\parindent}{10pt} % Adjust the indentation value as needed

% Sections formatting with custom color
\titleformat{\section}{
  \vspace{-4pt}\color{myviolet}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-7pt}]

%-------------------------
% Custom commands
\newcommand{\resumePOR}[3]{%
\vspace{0.5mm}\item[]
    \begin{tabular*}{\textwidth}[t]{l@{\extracolsep{\fill}}r}
    \hspace{-3mm}{#1}:\hspace{1mm} & \hspace*{0pt}\hfill{\footnotesize{ #3}} \vspace{-0.5mm}\\ \hspace{-2.9mm}#2 
    \end{tabular*}
    \vspace{0mm}
}

\newcommand{\resumeExp}[4]{%
\vspace{0mm}\item[]
    \begin{tabular*}{\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \hspace{-4.4mm} \small\textbf{#1} & {\footnotesize{#3}}\vspace{-1.2mm}\\
        \hspace{-4.3mm} \footnotesize{\text{#2}} & \footnotesize{#4}
    \end{tabular*}
    \vspace{-6.1mm}
}

\newcommand{\resumeProject}[4]{%
\vspace{0mm}\item[]
    \begin{tabular*}{\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \hspace{-4.4mm} \small\textbf{#1} & {\footnotesize{#3}}\vspace{-1mm}\\
        \hspace{-4.3mm} \footnotesize{\text{#2}} & \footnotesize{#4}
    \end{tabular*}
    \vspace{-6.5mm}
}

\newcommand{\resumeEdu}[4]{%
\vspace{0mm}\item[]
    \begin{tabular*}{\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \hspace{-4.3mm} \small\textbf{#1} & \footnotesize{#3}\vspace{-1mm} \\
        \hspace{-4.3mm} \footnotesize{#2} & \footnotesize{#4}
    \end{tabular*}
    \vspace{-3.2mm}
}

\newcommand{\resumeAchieve}[3]{%
\hspace{-3.1mm}\textbf{ #1} & {#2} & \hspace{3mm}\footnotesize{#3}
\vspace{0mm}\\
}

\renewcommand{\labelitemi}{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*,labelsep=0mm,itemsep=-2.5mm]}

\newcommand{\resumeItemListStart}{\begin{justify}\begin{itemize}[leftmargin=3ex, rightmargin=2ex, noitemsep,labelsep=1.2mm,itemsep=0mm]\small}

\newcommand{\resumeSubHeadingListEnd}{\end{itemize}\vspace{-2mm}}
\newcommand{\resumeItemListEnd}{\end{itemize}\end{justify}\vspace{-1.5mm}}

\renewcommand{\arraystretch}{1}

\newcolumntype{L}{>{\raggedright\arraybackslash}X}%
\newcolumntype{R}{>{\raggedleft\arraybackslash}X}%
\newcolumntype{C}{>{\centering\arraybackslash}X}%

%---- End of Packages and Functions ------

%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%

\newcommand{\name}{Mohd Arshad}
\newcommand{\address}{New Delhi, India}
\vspace{-5.5mm}
\newcommand{\course}{BCA - Bachelor of Computer Applications} % Your Course
\newcommand{\phone}{8882615763} % Your Phone Number
\newcommand{\emaila}{mohdarshad12575@gmail.com} %Email 1

\begin{document}
\fontfamily{cmr}\selectfont

%----------HEADING-----------------
\begin{center}
    \LARGE{\textbf{\name}} \\
    \vspace{1mm}
    \small{\text{\address}}
\end{center}
\vspace{-5.5mm}

\begin{center}
     \small{\href{https://github.com/MohdArshad12575}{ \hspace{0.2mm} github} |  \href{https://www.linkedin.com/in/mohd-arshad-726b38286/}{ \hspace{0.2mm} linkedin} |
     \href{https://arshaddataanalyst.tech/}{ \hspace{0.2mm} Portfolio} |
     \href{mailto:mohdarshad12575@gmail.com}{\ \hspace{0.2mm}mohdarshad12575@gmail.com} | \ \hspace{0.2mm} +91-8882615763} |   {\href{https://www.youtube.com/@Arshad_Data_Analyst}{YT-Channel} 
\end{center}
\vspace{-3mm}

%-----------EDUCATION-----------------

\vspace{-4.5mm}
\section{Education}

\resumeSubHeadingListStart
\resumeEdu
{Jamia Hamdard University - New Delhi, India} 
{BCA- (Bachelor of Computer Applications)} 
{Nov 2022 - May 2025} 
{\textbf{CGPA: 7.9/10}} 
\vspace{4mm}

% \resumeSubHeadingListStart

\resumeEdu
{PM Shri Kendriya Vidyalaya, Andrews Ganj - New Delhi, India} 
{Science PCM - (Class XII)} 
{Apr 2016 - Mar 2022} %Event Dates
{\textbf{First Division}} %Website

\resumeSubHeadingListEnd
\vspace{-4.5mm}


%-----------EXPERIENCE-----------------
\section{Experience}
\resumeSubHeadingListStart
\vspace{-0.5mm}
\resumeExp
{\textbf{Project-Based Data Analyst – Operations Support}{(Intern)}}
{Innovatiview Pvt. Ltd.}
{2 Months}
{~}

\vspace{1mm}
\resumeItemListStart
\setlength{\itemsep}{1mm} % Add space between bullet points (adjust this value as needed)
\item[$\bullet$] Managed daily manpower deployment data across 2–3 cities, submitted by vendors for exam center operations.
\item[$\bullet$] Created structured Excel reports summarizing guard deployment, attendance, and center-wise status.
\item[$\bullet$] Consolidated data and 100+ arrival photos into an audit-ready file for final reporting.
\item[$\bullet$] Ensured data accuracy by communicating with vendors and resolving submission delays.
\resumeItemListEnd
\resumeSubHeadingListEnd
\vspace{-7mm} % Adjust spacing above section
%-----------PROJECTS-----------------
\section{Projects}
\resumeSubHeadingListStart

\resumeProject
{\textbf{Olist E-commerce Revenue and Order Analysis} \textnormal{ (GCS, BigQuery, SQL , Looker Studio)} }
{}
{\href{https://github.com/MohdArshad12575/Olist-Revenue-Order-Analysis-Report}{GitHub} \textbar {\href{https://youtu.be/Dw-GIS4x_ZY?si=r7BiL3t3-f9Z4EpC}{YouTube}}}

\vspace{-2mm} % Reduced space before item list
\resumeItemListStart
\item[$\bullet$] Analyzed order and revenue data from the Olist dataset, focusing on sales performance, product categories, and customer behavior.
\item[$\bullet$] Cleaned, transformed, and merged data using SQL and BigQuery to generate meaningful insights and KPIs for sales and customer analysis.
\item[$\bullet$] Built interactive dashboards in Looker Studio for visualizing trends, customer demographics, and revenue distribution.
\item[$\bullet$] Conducted in-depth analysis on factors affecting sales, such as product categories, pricing, and geographical distribution.
\resumeItemListEnd

\vspace{1mm} % Adjusted space between projects

\resumeProject
{\textbf{ETL and EDA on Laptop Market Analysis with Feature Engineering} \textnormal{ (Advanced SQL)}}
{}
{\href{https://github.com/MohdArshad12575/SQL-Based-ETL-EDA-for-Laptop-Market-Analysis}{GitHub} \textbar {\href{https://youtu.be/6gVogvRGpy0?si=8km3ej1x3gCrVGB-}{YouTube}}}


\vspace{-2mm} % Reduced space before item list
\resumeItemListStart
\item[$\bullet$] Performed ETL on a laptop market dataset, applying SQL-based data cleaning, feature engineering, and exploratory data analysis (EDA).
\item[$\bullet$] Extracted key features such as GPU/CPU details, memory splits, and touchscreen flags, and transformed raw data into actionable insights.
\item[$\bullet$] Analyzed pricing trends, product performance, and market segmentation, using SQL to aggregate and filter data.
\item[$\bullet$] Created histograms and summary statistics to explore relationships between product features, price, and sales.
\resumeItemListEnd

\vspace{1mm} % Adjusted space between projects

\resumeProject
{\textbf{Road Casualties Analysis and Visualization Dashboard} \textnormal{ (Excel, MySQL ,Power BI)}}
{}
{\href{https://github.com/MohdArshad12575/road-safety-insights-excel-sql-powerbi}{GitHub} \textbar {\href{https://www.youtube.com/@Arshad_Data_Analyst}{YouTube}}}

\vspace{-2mm} % Reduced space before item list
\resumeItemListStart
\item[$\bullet$] Analyzed road casualty data to identify patterns and trends, focusing on incidents, fatalities, and injuries by location, road type, and light conditions.
\item[$\bullet$] Built dynamic dashboards in Power BI to visualize key metrics such as total incidents, urban vs. rural accidents, and casualties by vehicle type.
\item[$\bullet$] Used SQL for data cleaning, transformation, and KPI generation, including categorizing incidents by vehicle involvement and accident severity.
\item[$\bullet$] Presented findings in a comprehensive dashboard with visualizations such as heatmaps, accident trends, and casualty breakdowns by road surface and lighting conditions.
\resumeItemListEnd

\resumeSubHeadingListEnd

\vspace{-7mm} % Adjusted to control the gap before Certifications section


%-----------SKILLS-----------------
\section{Skills}

\begin{tabular}{@{} l l @{}}
\textbf{Languages:} & Python \\
\textbf{BI Tools:} & Looker Studio, Power BI, Excel (PivotTables, Power Query, Power Pivot) \\
\textbf{Other Skills:} & MySQL, PostgreSQL, Google Sheets, PowerPoint,  \\
\textbf{Cloud:} & Google Cloud Storage, Google BigQuery, AWS S3 \\
\textbf{Data Skills:} & Data Cleaning, EDA, ETL, Feature Engineering, Data Transformation, Data Visualization \\
\textbf{Soft Skills:} & Report Building, Dashboard Development,  Communication \\
\end{tabular}

\vspace{-3.5mm}

%-----------Certifications-----------------
\section{Certifications}

\textbf{Advanced Excel – Simplilearn}  
\begin{itemize}
    \item[$\bullet$] Gained hands-on experience with Excel formulas (VLOOKUP, INDEX-MATCH), PivotTables, Conditional Formatting, and automation using Macros.
\end{itemize}

\vspace{-1mm} % Adjust spacing between certs

\textbf{SQL (Intermediate) – HackerRank}  
\begin{itemize}
    \item[$\bullet$] Demonstrated proficiency in complex SQL queries including Window Functions, Joins, Subqueries, and Aggregations through a timed assessment.
\end{itemize}

\end{document}


