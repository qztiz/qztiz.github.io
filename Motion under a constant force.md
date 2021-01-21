# Motion under a constant force 

Suppose a force $F$ acts on a body for a time $t$, the body is assume to be initially at rest, and ends up with a speed $v$, then:
$$
Ft=mv=\frac{m_0}{(1-\frac{v^2}{c^2})^{1/2}}v
$$
Therefore, 
$$
\begin{align*}
1-\frac{v^2}{c^2}&=(m_0v/Ft)^2\\
c^2 &= v^2[1+(m_0c/Ft)^2]
\end{align*}
$$
and, by dividing $[1+(m_0c/Ft)^2]$, 
$$
v(t)=\frac{c}{[1+(m_0c/Ft)^2]^{1/2}}
$$
To consider two extreme cases

1. $Ft\ll m_0c$:
   $$
   (m_0c/Ft)^2 \gg 1 \\
   \therefore v(t) \approx\frac{c}{m_0c/Ft}= \frac{F}{m_0}t
   $$

2. $Ft\gg m_0c$:
   $$
   (m_0c/Ft)^2 \to 0
   \therefore v(t)\approx c
   $$
   

the first case correspond to the classical Newtonian mechanics. the second shows that speed $c$ is the upper limit speed. 



# Einstein’s box unhinged 

![image-20200728233534531](C:\Users\hp\OneDrive - Shenzhen College of International Education\typora pictures\image-20200728233534531.png)

Two mass $m_1$ and $m_2$, $m_1$ suffers a mass change to $m_1'$ , when a $E$ emits from it. It also acquires a velocity $v_1$: 
$$
v_1=\frac{-E/c}{m_1'}
$$
assume $m_1$ were originally at $x=0$, its position at $t$ is given by;
$$
x_1(t)=\frac{-E/c}{m_1'}t
$$
when the energy arrives at $m_2$, causing a recoil and changing the mass to $m_2'$. For the position of $m_2'$
$$
x_2(t)=L+\frac{E}{m_2'c}(t-L/c)
$$
Let the total mass be $M$, position of the centre of mass be $\bar x$ before emission and $\bar x'$ after it was absorbed. Then, 
$$
M\bar x =m_10+m_2L
$$
and 
$$
M\bar x'=m_1(\frac{-E}{m_1'c}t)+m_2'[L+\frac{E}{m_2'c}(t-L/c)]
$$
i.e., 
$$
\begin{align}
M\bar x'&=-\frac{E}{c}t+m_2'L+\frac{E}{c}t-\frac{E}{c^2}L \nonumber \\
		&=m_2'L-\frac{E}{c^2}L
\end{align}
$$
Since there is no external force applied, therefore the position of the centre of mass should not change, which indicates that $\bar x = \bar x'$. Combining Eq. (10) and Eq. (8), we have:
$$
\begin{align}
m_2L&=m_2'L-\frac{E}{c^2}L\nonumber \\
(m_2'-m_2)L&=\frac{E}{c^2}L \nonumber \\
\because m_2'-m_2 &=\Delta m_2'=-\Delta m_1' \nonumber \\
\frac{E}{c^2}&=\Delta m_2'=-\Delta m_1'

\end{align}
$$
