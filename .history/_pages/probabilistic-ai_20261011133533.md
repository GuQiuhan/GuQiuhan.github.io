---
layout: page
title: "A Personal Perspective on Probabilistic Abstract Interpretation"
permalink: /probabilistic-ai/
last_updated: 2026-10-11
---

<p style="color: var(--global-text-color-light); font-style: italic;">Last updated on {{ page.last_updated | date: "%B %-d, %Y" }}</p>

Personally, I have always had a habit of finding connections between the science I study and the philosophy of everyday life. Perhaps this is my way of keeping my research and my life from becoming two entirely separate worlds. So, rather than offering another formal introduction to my research, I would like to share something a little more personal: how I think about *probabilistic abstract interpretation*, and why I find it fascinating.

Much of life is about learning from experience. We observe the world, make predictions, discover that some of them are wrong, and gradually revise our understanding. Yet no matter how much we learn, uncertainty never really disappears. **Probability theory offers us a mathematical language for reasoning about this uncertainty.** In particular, Bayesian reasoning provides a principled way to update what we believe in light of new evidence. I find this idea rather beautiful: we do not need to know everything about the world to reason about it, and being uncertain does not mean being unable to learn.

Probabilistic programming brings this perspective into the world of computation. It allows us to describe complex systems involving randomness, uncertainty, and dependencies through programs. Unfortunately, the probability distributions induced by these programs can be extraordinarily complicated, making exact reasoning computationally intractable in many cases.

This is where *abstract interpretation* comes in. To me, abstract interpretation is **the art of making the complicated simple, without losing what matters**. Instead of attempting to capture every detail of a program's behavior, we construct a simpler representation that allows us to reason about it with mathematical guarantees. There is something deeply philosophical about this idea: understanding a system does not always require knowing everything about it. Sometimes, the real challenge is knowing what we can safely forget, and what we must preserve.

Over the past fifty years, abstract interpretation has developed into a rich and beautiful theory, with remarkable achievements in program analysis and verification. Yet its development in the probabilistic setting has been comparatively limited, leaving many fundamental questions open. I hope to spend my PhD years contributing, however modestly, to filling this gap. Perhaps I can add just one small grain of sand to this vast landscape of research. At least, that is the current plan. My research interests might wander somewhere completely different along the way. Who knows? After all, it would be rather ironic for someone studying probability to insist on predicting her own future with certainty.

Developing probabilistic abstract interpretation means going all the way back to the foundations: understanding the semantics of probabilistic programming languages, formalizing their concrete semantics, designing sound abstract semantics, and eventually turning these theories into practical analysis techniques. Beyond that lie exciting possibilities for connecting these foundations with modern neural networks, autonomous agents, and other increasingly complex computational systems. Every step presents its own difficulties, and every difficulty seems to open the door to even more questions. But perhaps that is exactly what makes research so enjoyable.

In the end, what fascinates me most about probabilistic abstract interpretation is not merely the mathematics or the possibility of building better analysis tools. It is the underlying question that seems to connect my research back to everyday life:

**How much of the world's complexity can we set aside, while still reasoning about what remains with confidence?**

I do not know how far I will get toward answering this question. But I am very much looking forward to finding out.

[← Back to Home]({{ '/' | relative_url }})
