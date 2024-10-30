# Little-o

In addition to the big-O, big-$\Omega$, and big-$\Theta$ notation that
we covered at the beginning of this class, a few other notations are sometimes
used in asymptotic analysis.  For example, "little-$o$" notation.

Prove (i.e.\ give a formal mathematical proof) that $f(n)\in o(g(n))$ implies
that $f(n)\in O(g(n))$.

Hint: The proof will be *very* short and *very* easy. You can start by
identifying the differences between the definitions of O and o.

I have started with the formal definition of $o$ below. Add your answer to this
markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$f(n)\in o(g(n)) \iff \forall c>0, \exists n_0, \forall n\ge n_0: f(n) < c g(n)$

Big $O$: $f(n) \in O(g(n)) \iff  \exists (c, n_0) > 0: f(n) \le c(g(n)) \forall n \ge n_0$

Using the above, we know that $f(n) \in o(g(n)) \and f(n) \in O(g(n))$. We can prove this by choosing the same constants $c$ and $n_0$ for $f(n) \in o(g(n))$ and $f(n) \in O(g(n))$. Then, $f(n) \le c(g(n)) \forall n \ge n_0$. Therefor $f(n) \in o(g(n))$ implies $f(n) \in O(g(n))$

“I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.”
