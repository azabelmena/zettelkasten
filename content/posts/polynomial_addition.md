+++
date = '2025-04-29T12:47:34-04:00'
title = 'Polynomial Addition'
+++

Let \(R\) be a ring, and let \(f(x)=a_0+a_1x+\dots+a_mx^m\) and
\(g(x)=b_0+b_1x+\dots+b_nx^n\) {{< backlink "polynomial" "polynomials" >}}
over \(R\), with \(m \leq n\). We define _polynomial addition_ over \(R\)
to be the {{< backlink "binary_operation" "binary operation" >}} \(+\)
given by the rule:
\[
+:(f(x),g(x)) \rightarrow f+g(x)=f(x)+g(x)=c_0+c_1x+\dots+c_nx^n
\]
where
\[
c_j=a_j+b_j \text{ and } a_j=0 \text{ for all } m < j \leq n
\]
