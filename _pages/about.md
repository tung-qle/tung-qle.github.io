---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a third-year PhD student in [OCKHAM team](https://team.inria.fr/dante/fr/), ENS Lyon, France. I am under the supervision of [Elisa Riccietti](http://perso.ens-lyon.fr/elisa.riccietti/) and [Rémi Gribonval](https://people.irisa.fr/Remi.Gribonval/). I am interested in theory of Neural Networks, non-convex optimization and other subjects in Theoretical Computer Science.
{: .text-justify}

# My PhD project

My PhD project considers several algorithmic and theoretical aspects of the training problem of sparse deep neural networks (DNNs) and the problem of sparse matrix factorization. In comparison to usual DNNs, Sparse DNNs have *sparse* weight matrices. Analoguously, in comparison to matrix factorization, sparse matrix factorization approximate a target matrix by product of (multiple) *sparse* factors.

For sparse DNNs, we study the existence of optimal solutions of their training problems. In addition, our study investigates several topological properties of the function space associated to sparse DNN architectures such as (non-)closedness. 

For Sparse Matrix Factorization, we study in detail one of its variant named "Fixed support matrix factorization" in which the knowledge of the supports (the set of non-zero entries) of factors are avaiblable and the factorization consists of optimizing the coefficients in the supports to minimize the distance between the target matrix and the product of sparse factors. We obtained results on the complexity, algorithms and landscape of the loss function for the case of two factors. Those results are extended to the case of multiple factors under the assumption that the supports of the factor admit the "butterfly structure" (see illustration below). This allows us to not only analyze several sparsity structures proposed for deep learning models but also establish a new theoretical guarantee for the so-called "butterfly algorithm".
{: .text-justify}

<figure>
  <img
    src="/images/hadamard.png"
     alt="An example of sparse matrix factorization"
     class="img-responsive"
     style="float: center; 
      margin-top: 1em;"
    >
    <figcaption>Butterfly structure of the Hadamard transformation</figcaption>
</figure>

