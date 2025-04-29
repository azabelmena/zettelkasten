+++
date = '2025-04-25T22:35:41-04:00'
title = 'Group'
+++

A _group_ is a non-empty {{< backlink "set" "set" >}}
\(G\) together with a {{< backlink "binary_operation" "binary operation" >}}
\(\ast: G \times G \rightarrow G\) such that the following hold:

(Closure) For every \(a,b \in G\), the product \(a \ast b \in G\).

(Associativity) The binary operation \(\ast: G \times G \rightarrow G\) is
{{< backlink "associative" "associative" >}}.

(Identity) \(G\) has an {{< backlink "identity_element" "identity element" >}}.

(Inverse) There exists an {{< backlink "inverse_element" "inverse element ">}}
for every element \(a \in G\).

{{< sidenote "remark" >}}
We remark that the closure axiom is redundant in this definition.
Indeed, by definition of a {{< backlink "binary_operation" "binary operation">}}
we are guaranteed that: \(\ast(G \times G) \subseteq G\).
{{< /sidenote >}}
