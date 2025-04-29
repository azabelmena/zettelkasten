+++
date = '2025-04-29T12:47:43-04:00'
title = 'Polynomial Multiplication'
+++

Let \(R\) be a ring, and let \(f(x)=a_0+a_1x+\dots+a_mx^m\) and
\(g(x)=b_0+b_1x+\dots+b_nx^n\) {{< backlink "polynomial" "polynomials" >}}
over \(R\). We define _polynomial multiplication over \(R\) to be the
{{< backlink "binary_operation" "binary operation" >}} \(\cdot\) given by
the rule:
\[
\cdot:(f(x),g(x)) \rightarrow fg(x)=f(x)g(x)=c_0+c_1x+\dots+c_kx^k
\]
where
\[
c_j=\sum_{i=0}^j{a_ib_{j-1}} \text{ and } k=m+n
\]
