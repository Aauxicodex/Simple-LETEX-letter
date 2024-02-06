markdown
```
\documentclass[a4paper]{letter}

% Packages for formatting
\usepackage[utf8]{inputenc}
\usepackage[english]{babel}
\usepackage{lipsum} % for dummy text

% Sender information
\address{Your Name \\ Your Address \\ City, State, Zip Code \\ Country}
\signature{Your Name}

% Receiver information
\begin{document}
\begin{letter}{Recipient's Name \\ Recipient's Address \\ City, State, Zip Code \\ Country}

% Date
\date{\today}

% Opening
\opening{Dear Recipient,}

% Body of the letter
\lipsum[1-2] % Replace with your actual content

% Closing
\closing{Sincerely,}

\end{letter}
\end{document}
