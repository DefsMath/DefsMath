---
 layout: page
 title: contragradient representation
 permalink: /contragradient_representation
---
Let $\mathbb k$ be some [field](https://defsmath.github.io/DefsMath/field). Let $G$ be a [group](https://defsmath.github.io/DefsMath/group) and let $\rho:G\to GL(V)$ be a [representation](https://defsmath.github.io/DefsMath/group_representation) of $G$ in the $\mathbb k$-[vector space](https://defsmath.github.io/DefsMath/vector_space) $V$. Let $V^* = \text{Hom}_\mathbb k(V,\mathbb k)$ be the [dual space](https://defsmath.github.io/DefsMath/dual_space) of $V$. By the [Riesz representation theorem](https://defsmath.github.io/DefsMath/Riesz_representation_theorem), there is a canonical pairing $\langle \cdot,\cdot \rangle:V^*\times V \to\mathbb k$ that lets us write [linear](https://defsmath.github.io/DefsMath/linear_transformation) functionals $\phi:v\mapsto \phi(v)$ as $\langle \phi,v\rangle$. 

The $G$-[action](https://defsmath.github.io/DefsMath/conjugacy_classes) $v\mapsto \rho(g)v$ on $V$ induces [the action on the space of functions on](https://defsmath.github.io/DefsMath/induced_action_of_group_on_maps) $V$, of which $V^*$ is an [invariant subspace](https://defsmath.github.io/DefsMath/invariant_subspace). Explicitly, $g\in G$ acts on $\phi \in V^*$ by $$[v\mapsto \phi((\rho(g))^{-1}(v))] = \langle \phi, (\rho(g))^{-1}v\rangle = \langle ((\rho(g))^{-1})^\intercal, v\rangle = \langle (\rho(g^{-1})^\intercal, v\rangle$$ where $(\rho(g^{-1}))^\intercal$ is the [adjoint of a adjoint](https://defsmath.github.io/DefsMath/adjoint_of_a_######################adjoint) of the [operator](https://defsmath.github.io/DefsMath/######################operator) $\rho(g):V\to V$. This action on $V^*$ gives a [group homomorphism](https://defsmath.github.io/DefsMath/group_homomorphism) $\rho^\vee:G\to GL(V^*)$ where $\rho^\vee(g) = (\rho(g^{-1}))^\intercal$ that is called the **contragradient representation** of the original representation $\rho$. 