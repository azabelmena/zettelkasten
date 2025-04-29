+++
date = '2025-04-29T13:11:45-04:00'
draft = true
title = 'Multivaraiate Polynomial Ring'
+++

Let \(R\) be a {{< backlink "ring" "ring" >}}. We define the
_multivariate polynomial ring_ \(R[x_1, \dots, x_n]\) in \(n\)
_variables_ with _coefficients_ in \(R\) to be the polynomial ring
defined recursively as:

(1). \(R[x_1,x_2]=(R[x_1])[x_2]\).
(2). \(R[x_1, \dots, x_n, x_{n+1}]=
(R[x_1, \dots, x_n])[x_{n+1}]\).
