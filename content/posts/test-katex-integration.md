---
title: "Test Katex Integration"
date: 2020-09-15T18:19:12-05:00
draft: false
toc: false
math: true
tags:
  - mathematics
  - chemistry
  - katex
---

An nth Partial Sum:

$$
\sum_{i=1}^n i = \frac{n(n+1)}{2}
$$

A code example:

```cpp
int main(int argc, char *argv[]) 
{
	int count = 0;
	int max = argv[1];

	for (int i = 1; i <= max; i++) 
	{
		count += i;
	}
	
	std::cout << "Sum: " << count << std::endl;
}
```

Product $\prod_{i=a}^{b} f(i)$ inside text.

A chemical formula: 

$C_p[\ce{H2O(l)}] = \pu{75.3 J // mol K}$

A little bit more complex:

$\ce{Zn^2+  <=>[+ 2OH-][+ 2H+]  $\underset{\text{amphoteres Hydroxid}}{\ce{Zn(OH)2 v}}$  <=>[+ 2OH-][+ 2H+]  $\underset{\text{Hydroxozikat}}{\ce{[Zn(OH)4]^2-}}$}$

This is fun.