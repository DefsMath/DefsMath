---
 layout: page
 title: vector-valued integral
 permalink: /chicago/vector-valued_integral
---
Let $X$ be a [locally compact](https://defsmath.github.io/DefsMath/locally_compact) [Hausdorff](https://defsmath.github.io/DefsMath/Hausdorff) [topological space](https://defsmath.github.io/DefsMath/topological_space). Fix an [integral](https://defsmath.github.io/DefsMath/Lebesgue_integral) $\int_X$ and $V$ a finite-[dimensional](https://defsmath.github.io/DefsMath/dimension_of_vector_space) [vector space](https://defsmath.github.io/DefsMath/vector_space). Choose a [basis](https://defsmath.github.io/DefsMath/basis) $\{v_i\}_{i=1}^n$ for $V$ so that any [continuous](https://defsmath.github.io/DefsMath/continuous) function $f:X\to V$ can be expressed as $$f(x) = \sum_{i=1}^n f_(x)v_i \text{ for all } x\in X$$ where the $f_i$ are the [components](https://defsmath.github.io/DefsMath/component_function) of $f$. Define the **vector-valued integral** of $f$ as $$\int_X f(x) \text{d} x = \sum_{i=1}^n \left(\int_X f_i(x)\text dx \right)v_i.$$ We can say that it is given by the integrals of the coordinates. 