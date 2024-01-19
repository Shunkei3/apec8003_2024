---
class: middle

## Example: Prisoner's Dilemma

```{r  echo = F, out.width = "70%"}
knitr::include_graphics("photos/photo1.png")
```
<br>

Mathematically (you don't need to do this but), 

.content-box-green[For player 1]: $U_1(s_1=\color{red}{D}, s_2=C) > U_1(s_1=\color{blue}{C}, s_2=C)$ and $U_1(s_1=\color{red}{D}, s_2=D) > U_1(s_1=\color{blue}{C}, s_2=D)$. Therefore, $s_1=\color{red}{D}$ strictly dominates $s_1=\color{blue}{C}$.

.content-box-green[For player 2]: $U_2(s_2=\color{red}{D}, s_1=C) > U_2(s_2=\color{blue}{C}, s_2=C)$ and $U_2(s_2=\color{red}{D}, s_1=D) > U_2(s_2=\color{blue}{C}, s_2=D)$, therefore, $s_2=\color{red}{D}$ strictly dominates $s_2=\color{blue}{C}$.

So, $(s_1, s_2)=(D, D)$ is a strictly dominant strategy equilibrium. 


---