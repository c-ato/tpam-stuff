---
tags:
  - maths
  - physics
  - maths/topology
  - quantum
---
\documentclass[a4paper,12pt]{article}

% Packages

\usepackage{cancel}
\usepackage{amsmath}
\usepackage{amssymb}
\usepackage{amsfonts}
\usepackage{amsthm}
\usepackage{titlesec}
\usepackage{graphicx}
\usepackage{babel}
\usepackage[utf8]{inputenc}
\usepackage[useregional]{datetime}
\usepackage{esvect}
\usepackage[margin=1in,footskip=0.25in]{geometry}
\usepackage{hyperref}
\usepackage{titlesec}

% Callout stuff

\theoremstyle{definition}
\newtheorem{definition}{Definition}[section]
\theoremstyle{remark}
\newtheorem{remark}{Remark}
\theoremstyle{theorem}
\newtheorem{theorem}{Theorem}[section]
\theoremstyle{lemma}
\newtheorem{lemma}[theorem]{Lemma}
\theoremstyle{corollary}
\newtheorem{corollary}{Corollary}[theorem]

% Formatting

\renewcommand{\itemize}{\vspace{-0.4cm}}
\renewcommand{\thesubsection}{\thesection.\arabic{subsection}}
\renewcommand{\thesubsubsection}{\thesubsection.\arabic{subsubsection}}
\newcommand{\chapfnt}{\fontsize{16}{19}}
\newcommand{\secfnt}{\fontsize{12}{14}}
\newcommand{\ssecfnt}{\fontsize{12}{14}}
\titleformat{\section}{\normalfont\secfnt\bfseries}{\thesection}{1em}{}
\titleformat{\subsection}{\normalfont\ssecfnt\bfseries}{\thesubsection}{1em}{}
\titlespacing*{\chapter} {0pt}{50pt}{40pt}
\titlespacing*{\section} {0pt}{3.5ex plus 1ex minus .2ex}{2.3ex plus .2ex}
\titlespacing*{\subsection} {0pt}{3.25ex plus 1ex minus .2ex}{1.5ex plus .2ex}

% Title

\setlength{\parskip}{\baselineskip}%
\setlength{\parindent}{0pt}%
\title{\vspace{-3cm}Summer Research Programme Report}
\date{\vspace{-2cm}\daymonthyeardate\today}
\author{Mohammed Ridhwan Ali (Ridhwan)}

\begin{document}

\maketitle

\section*{Introduction}

The purpose of this report is to record and consolidate the information from this project in understanding and learning TQFT for two dimensions, where TQFT means topological quantum field theory. We will first understand topology, then move to Riemann surfaces and then a categorical definition of TQFT with Bords, functors, 

\tableofcontents
\addcontentsline{toc}{section}{Introduction}

\section{TQFT}

\subsection{Prerequisites in Topology}

We will want to start by defining what it means for something to be open and for this we will define a space with distance (metric space) and balls.

\begin{definition}[Metric Space]

This is a set $X$ where the structure of distance exists, formally it is as followed: for some $x,y\in X$, then $d(x,y):X\to \mathbb{R}$ is a function that determines distance between $x$ and $y$.\\\\It must also satisfy the following conditions:

\begin{itemize}
    \item $d(x,y)\geq 0\forall x,y \in X$
    \item $d(x,y)=0\iff x=y$
    \item $d(x,y)=d(y,x)$
    \item $d(x,z)\leq d(x,y)+d(y,z)$
\end{itemize}

\end{definition}

\begin{definition}[Balls]

Let $X$ be a metric space. A ball $B$ of radius $r$ around a point $x \in X$ is $B=\{ y \in X | d(x,y)<r \}$.

\end{definition}

\begin{definition}[Open Sets]

A subset $O \subseteq X$ is open if for every point $x \in O$, there is a ball around $x$ entirely contained in $O$.
\vspace{-0.4cm}
\end{definition}

From this we naturally obtain a definition for closed sets, however, by itself is not particularly useful so we will introduce limit points and the following theorem, which is more useful.

\begin{definition}[Closed Sets]

A set $C$ is closed if $X-C$ is open.

\end{definition}

\begin{definition}[Limit Point]

A point $z$ is a limit point for a set $A$ if every open set $U$ containing $z$ intersects $A$ in a point other than $z$. The point $z$ may or may not be in $A$

\end{definition}

\begin{theorem}[Closed Sets]
\label{Closed Sets}

A set $C$ is closed $\iff$ it contains all its limit points.
\vspace{-0.4cm}

\end{theorem}

We may now finally define what a topological space is, but for this, we will need to fully understand what a topology is first.

\begin{definition}[Topology]

A topology $\tau$ on a set $X$ consists of subsets of $X$ satisfying the following properties:

\begin{itemize}
    \item The empty set $\varnothing$ and the space $X$ are both sets in the topology.
    \item The union of any collection of sets in $\tau$ is contained in $\tau$.
    \item The intersection of any finitely many sets in $\tau$ is also contained in $\tau$.
\end{itemize}

\end{definition}

\begin{definition}[Topological Space]

A topological space is a pair $(X, \tau )$ where $X$ is a set and $\tau$ is a set of subsets of $X$ satisfying certain axioms. $\tau$ is called a topology

\end{definition}

We have now successfully defined a topological space and we may now explore its finer structure. From here I will also define what an Euclidean topology is as it will be useful later.

\begin{definition}

When $X$ is a set and $\tau$ is a topology on $X$, we say that the sets in $\tau$ are open. Therefore, if $X$ does have a metric (a notion of distance), then $\tau =\{\text{all open sets as defined with the ball}\}$ is indeed a topology. We call this topology the Euclidean topology. It is also referred to as the usual or ordinary topology.

\end{definition}

\end{document}
