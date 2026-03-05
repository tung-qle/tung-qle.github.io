---
title: "Mini-project of Numerical Optimization course"
layout: archive
---
<div style="margin-top: 2em;"></div>

# General rules of the mini-project
<div style='text-align: justify;'>
The mini-project contributes to the final evaluation of Graduate School (GS) students only. Therefore, only GS students are required to participate. Other students can participate but they are not allowed to team up with GS students and their projects will not be supervised or evaluated. They can consult advices from the teaching teams though.
<br>
GS students form groups of 4 students (or fewer if we cannot form all 4-member groups). They will have to choose and explore one of the following projects. You can propose your own project but please consult the teaching teams (either me or Thomas).
<br>
In the end, each group is expected to prepare: 
<ul style='text-align: justify;'>
<li>An <b>implementation</b> in Python for your project</li>
<li>A <b>short report</b> to summarize your project: the report should be around 3-5 pages (there is no strict page limit though). If your reports have many images/figures/graphs, you can have more pages, but please try to be as concise as possible. Lengthy report badly affects your note.</li>
<li>A <b>presentation</b>: you will prepare a presentation of 15 minutes to present to the teaching teams. You do not need to send your presentation.</li>
</ul>

Please send us your code and reports to the teaching teams mail addresses: <a href="mailto:quoc-tung.le@univ-grenoble-alpes.fr">Quoc-Tung Le</a> and <a href="mailto:thomas.guilmeau@inria.fr">Thomas Guillaume</a>. Several important remarks:

<ul style='text-align: justify;'>
<li><b>Duration</b>: 6 weeks</li>
<li><b>Deadline for code and report</b>: 23h59 (Paris time), 18 April 2026</li>
<li><b>Project presentation date</b>: During the week 20-24 April 2026</li>
</ul>
</div>

# Evaluation of the mini-project
<div style='text-align: justify;'>
All projects will be evaluated based on their respective levels. More specifically, we categorize each project into 4 levels:

<ul style='text-align: justify;'>
<li><b>Level 0</b>: The project fails the objectives. Either the implementation or the report fails to prove that the students understand the core ideas of the paper and use it for specific applications.</li>
<li><b>Level 1</b>: The project successfully accomplishes the initial objectives given in its description. The code and report clearly show the understanding of the topics, techniques and related applications. You should get <b>65-80%</b> (depending on the difficulties of the project) of the maximum note at this point.</li>
<li><b>Level 2</b>: Surpassing the initial objectives, students consider, implement and compare related models/algorithms/methods of the original project. This can be accomplished by reading and investigating researches citing/improving the original paper. You can also search for a review paper that summarizes the litterature of the original paper. Attaining this level, you will get <b>90-95%</b> maximum note.</li>
<li><b>Level 3</b>: The students now have a very good understanding of the field and can either: identify fundamental challenges of the methods/techniques and/or propose new approach. Note that you need to reach level 2 before getting level 3: simply proposing (dump or supposedly new) ideas (without knowing existing works) does not get you to level 3. At this level, you typically get <b>100%</b> (or more, there is no limit after) the maximum note.</li>
</ul>

Finally, please state clearly the contributions of each member. Without this information, we will assume that individual contributions are equal.
</div>
<br>

# Project proposals for the course: Numerical Optimization, M1 Applied Mathematics

## Project 1: Nonnegative matrix factorization (NMF) and applications

<div style='text-align: justify;'>
This project introduces the nonnegative factoziation modelisation and its applications. Students are required to understand and implement the well-known <i>multiplicative update rule</i> and apply it to certain applications.
<br>
</div>

### Main references
<ul style='text-align: justify;'>
<li> <b>The multiplicative update rule</b>: <a href="https://proceedings.neurips.cc/paper_files/paper/2000/file/f9d1152547c0bde01830b7e8bd60024c-Paper.pdf">Link to paper</a></li>
<li> <b>Applications</b>: Several applications of NMF are introduced in Section 1.3 of the <a href="https://www.dropbox.com/scl/fi/48xd9r662xw5vrtug919i/NMFbook_SIAM_reprint.pdf?rlkey=9jre7n93dspdaime9whjkhzg3&e=1&dl=0">NMF book by Nicolas Gillis</a>. You can find the datasets for these applications there-in. </li>
</ul>

## Project 2: A Fast Iterative Shrinkage-Thresholding Algorithm for Linear Inverse Problems
<div style='text-align: justify;'>
This project investigate a fast proximal algorithm to minimize a composite function of the form f = g + h where h can be a non-convex function. We then use this algorithm to perform image denoising task.
<br>
</div>


### Main references
<div style='text-align: justify;'>
Our main reference is the <a href="https://www.ceremade.dauphine.fr/~carlier/FISTA">seminal paper by Amir Beck and Marc Teboulle</a>, which provides a counterpart for Nesterov optimal algorithm in non-convex case. Students are expected to understand this paper, implement the methods and re-implement experiments (notably image denoising) in Section 5 of this paper.  
</div>

## Project 3: Sparse matrix factorization and applications
<div style='text-align: justify;'>
This project focus on sparse matrix factorization, a generalized version of the well-known linear inverse problems. We investigate how to approximate a matrix by the product of sparse factors, which can reduce the memory footage and accelerate the matrix-vector product operation. Students are expected to read and re-implement existing algorithms, then use their own implemented algorithms to factorize real-world matrices.
<br>
</div>

### Main references
<ul style='text-align: justify;'>
<li> <b>Problem formulation and algorithms</b>: <a href="https://arxiv.org/pdf/1506.07300">Link to the paper</a>. Note that the main algorithms in the previous paper is called Proximal Alternating Linearized Minimization (PALM), which is originally proposed and analysed in <a href="https://www.researchgate.net/profile/Jerome-Bolte/publication/257480087_Proximal_alternating_linearized_minimization_for_nonconvex_and_nonsmooth_problems/links/547216f30cf2d67fc035b0c5/Proximal-alternating-linearized-minimization-for-nonconvex-and-nonsmooth-problems.pdf">PALM paper</a>. It is noteworthy that the latter is more difficult to understand.</li>
<li> <b>Sample codes</b>: Several applications are discussed in Sections V-VI of <a href="https://arxiv.org/pdf/1506.07300">Sparse Matrix Factorization paper</a>. Some tutorials are available <a href="https://faust.inria.fr/tutorials/pyfaust-jupyter-notebooks/using-the-palm4msa-mhtp-algorithm-with-pyfaust/">here</a>. </li>
</ul>

## Project 4: Robust Principal Component Analysis
<div style='text-align: justify;'>
This project is about Robust Principal Component Analysis (RPCA), a generalization of the well-known Principal Component Analysis (PCA). Students are expected to understand the modeling of RPCA, its corresponding optimization problem and implement an algorithm to solve it. Applications of RPCA are also expected from the project.
</div>

### Main references
<div style='text-align: justify;'>
Our main reference is the <a href="https://arxiv.org/pdf/0912.3599">seminal paper by Emmanuel J. Candès, Xiaodong Li, Yi Ma, and John Wright</a>, which provides the theoretical framework for RPCA. An algorithm for RPCA is presented in Section 5. Applications can be found in Section 4. Re-implementing that algorithm and trying it with applications in this paper can be a good start. 
<br>
</div>

## Project 5: Black box variational inference
<div style='text-align: justify;'>
This project aims at performing variational inference, that is approximate a Bayesian posterior distribution by a simpler distribution, in a black box way, that is without using model-specific computations. Students are expected to implement the basic BBVI algorithm, use it to approximate simple Bayesian posteriors, and investigate variance reduction techniques and alternative algorithms.
</div>

### Main references
<div style='text-align: justify;'>
Black-box variational inference (BBVI), was introduced in <a href="https://proceedings.mlr.press/v33/ranganath14.html">the eponymous paper from Rajesh Ranganath, Sean Gerrish, and David M. Blei</a>, which proposed a stochastic gradient descent algorithm to solve the problem in Section 2. Strategies to reduce the variance are discussed in Section 3, and other algorithmic strategies in Section 4. Experiments are provided in Section 5. 
</div>

## Project 6: Expectation-maximization
<div style='text-align: justify;'>
Expectation-maximization (EM) is a classic algorithm for maximum likelihood estimation, in cases where the likelihood depends on unobserved latent variables.For this project, students are expected to implement the EM algorithm in the case of finite mixtures.
</div>

### Main references
<div style='text-align: justify;'>
The EM algorithm was formalized by <a href="https://academic.oup.com/jrsssb/article/39/1/1/7027539?login=true">Arthur P. Dempster,  Ann Laird, and Donald B. Rubin in 1977</a>. The algorithms is defined in Section 2, and theoretical properties are provided in Section 3. Note that Section 3 also introduces a generalized EM algorithm. Section 4 is devoted to examples of applications. The EM algorithm is also introduced in a more modern format in <a href="https://www.microsoft.com/en-us/research/publication/pattern-recognition-machine-learning/">the book Pattern Recognition and Machine Learning by Christopher M. Bishop (Chatper 9)</a>.
</div>

## Project 7: Splitting methods in optimal control
<div style='text-align: justify;'>
Optimal control is the problem of computing trajectories whose dynamics respect some constraints and which minimize some objective function. In the case of discrete-time formulation, optimal control can be seen as a constrained finite-dimensional optimization problem. The goal of this project is to implement a splitting optimization algorithm to solve such problems.

### Main references
The sutdents are expected to implement the splitting algorithm proposed by <a href="https://web.stanford.edu/~boyd/papers/pdf/oper_splt_ctrl.pdf">Brendan O’Donoghue, Giorgos Stathopoulos, and Stephen Boyd</a> to solve discrete-time optimal control problem that exhibit linear dynamics constraints. Section II introduces the considered setting and Section III is devoted to the presentation of the splitting algorithm. Examples of applications are presented in Section IV. The students are expected to reproduce the results obtained in this paper (starting with the box-constrained linear-quadratic optimal control problem).
</div>

## Project 8: Semi-smooth Newton methods for non-linear complementarity problems
<div style='text-align: justify;'>
Newton's method can be extended from the resolution of root-finding problems for smoth function to the resolution of so-called non-linear complementarity problems, which are non-smooth. These problems encompass in particular the resolution of constrained optimization problems and of game theory equilibriums. The students are expected to implement a semi-smooth version of the Newton's method and use it to solve problems from constrained optimization and game theory. 
</div>

### Main references
<div style='text-align: justify;'>
We consider the semi-smooth Newton's method proposed by <a href="https://link.springer.com/article/10.1007/BF02592192">Tecla De Luca, Francisco Facchinei, and Christian Kanzow</a>. In this paper, Section 2 introduces some definitions associated with semi-smooth functions, Section 3 presents the algorithm, Section 4 and 5 presents some sufficient conditions for the well-posedness of the problem and the algorithm, the convergence proof is given in Section 6, and Section 7 gives some details about the implementation of the algorithm with some numerical results. Numerical experiments are performed on problems taken from the extensive numerical experiments in <a href="https://link.springer.com/article/10.1007/BF01580617">the earlier paper by Jong-Shi Pang and Steven A. Gabriel</a>.
</div>
