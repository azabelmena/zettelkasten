+++
date = '2025-05-18T11:59:13-04:00'
title = 'Category'
+++

A _category_ \(\mathscr{C}\) is a collection of _objects_, denoted
\(\text{obj}{\mathscr{C}}\) together with a collection of classes of _morphisms_
between pairs of objects, each of which is denoted \(\text{Mor}{(a,b)}\) for any pair
\(a,b \in \text{obj}{\mathscr{C}}\), such that the following data is given:

(1). For any objects \(a,b,c \in \text{obj}{\mathscr{C}}\), there
exist _composition maps_
\[
\circ:\text{Mor}{(b,c)} \times \text{Mor}{(a,b)} \rightarrow \text{Mor}{(b,c)}
\]
associating to each pair of morphisms \((g,f)\) a morphism \(g \circ f\) called the
_composition_ of the morphism \(g\) with the morphism \(f\).

(2). For any objects \(a,b,c,d \in \text{obj}{\mathscr{C}}\), and for
any morphisms \(f \in \text{Mor{(a,b)}}\), \(g \in
\text{Mor{(b,c)}}\), and \(h \in \text{Mor{(c,d)}}\), the composition
maps between morphisms associate wherever they exist; that is:
\[
h \circ (g \circ f)=(h \circ g) \circ f
\]
whenever either \(h \circ (g \circ f)\) or \((h \circ g) \circ f\)
exists.

(3). For any object \(a \in \text{obj}{\mathscr{C}}\), there is a
morphism \(id_a \in \text{Mor}{(a,a)}\), called the _identity
morphism_ on \(a\), such that for any objects \(b,c \in \text{obj}{\mathscr{C}}\),
and for any morphisms \(f \in \text{Mor}{(a,b)}\) and \(g \in \text{Mor}{(c,a)}\), '
the following holds:
\[
f \circ id_a=f \text{ and } id_a \circ g=g
\]
Given objects \(a,b \in \text{obj}{\mathscr{C}}\), we denote a morphism \(f \in
\text{Mor}{(a,b)}\) by \(f:a \rightarrow b\).

{{< sidenote "remark" >}}
Here we take the terms _object_ and _morphism_ to be undefined.
{{< /sidenote >}}
