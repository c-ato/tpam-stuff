[[Year 1 Assessed Problems 8 1.pdf]]
\section{Problem 1. A busy shop has three queues of people. Unfortunately the three tills are somewhat unreliable. 
- Till A fails with probability 0.1. 
- Till B fails with probability 0.1. 
- Till C fails with probability 0.05. 

Once a till fails it must be reset, and then it continues to work. After an hour, 30 people used Till A, 35 used Till B and 35 used Till C.}

\subsection{What is the probability that someone (if selected at random) used till A or C? [2]}
$$
\frac{30+35}{30+35+35}=\frac{65}{100}=\frac{13}{20}
$$
\subsection{What is the probability of someone having a till failure if selected at random? Hint: Marginalise. [2]}
$$
\frac{30\times 0.1+35\times 0.1+ 35\times 0.05}{100}=\frac{8.25}{100}=\frac{33}{400}
$$
\subsection{Two people are selected at random. What is the probability that exactly one of them had a till failure? [2]}

Assuming replacement:
$$
2\times\frac{33}{400}\left( \frac{367}{300} \right)=\frac{12111}{80000}
$$
\subsection{Three people are selected at random. What is the probability that they all used different tills? State your sampling assumptions (with or without replacement. [2]}
Assuming replacement:
$$
6\times\frac{30}{100}\left( \frac{35}{100} \right)\left( \frac{35}{100} \right)=\frac{441}{2000}
$$
\subsection{Given that someone experienced a failing till, what is the probability that the till they used was B? [2]}
$$
\frac{0.1 \times \frac{35}{100}}{\frac{33}{400}}=\frac{14}{33}
$$
\subsection{What is the probability that that person did not use Till B? [1]}
$$
1-\frac{14}{33}=\frac{19}{33}
$$
