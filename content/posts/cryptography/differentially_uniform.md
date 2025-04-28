+++
date = '2025-04-28T11:09:56-04:00'
title = 'Differentially Uniform'
+++

Given \( \delta \in \Z^+ \), we call an [\( (m,n,p)
\)-function](/zettelkasten/posts/cryptography/nmp-function)
_differentially \(\delta\)-uniform_ if for every nonzero \( a \in
\mathbb{F}_{p^m} \), and for every \( b \in \mathbb{F}_{p^n} \), the
difference equation:

[
\[
D_a{f(x)}=b
\]
](/zettelkasten/posts/cryptography/derivative)
has at most \(\delta\)-solutions.
