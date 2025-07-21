+++
date = '2025-07-20T20:20:19-04:00'
title = 'Matroid (Independence Axioms)'
+++

A _matroid_ is a {{< backlink "set" "set" >}} called the _ground
set_, together with a collection \(\mathscr{I}\) of
{{< backlink "subset" "subsets">}} called _independent sets_ such
that the following hold:

(1.) \( \emptyset \in \mathscr{I} \)

(2.) If \( I \in \mathscr{I} \) and \( J \subseteq I \), then
\( J \in \mathscr{I} \).

(3.) If \(I_1, I_2 \in \mathscr{I} \), and \( |I_1|<|I_2| \), then
there exists an \( e \in {I_2 \backslash I_1} \) for which \(I_1
\cup \{e\} \in \mathscr{I} \).

We call axiom (3.) the _augmentation axiom_.
