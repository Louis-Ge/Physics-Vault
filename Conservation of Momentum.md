**In the absence of external forces, the total momentum of a system is constant.**
$$\dot{\mathbf{P}}=\mathbf{F}_{\text{ext}}$$
**Derivation:**
In a system with N particles, every particle can exert a force on the other ones. There could also be an external force on each particle.
$$\begin{align}
\mathbf{F}_{\alpha}&=\sum_{\beta \neq\alpha}\mathbf{F}_{\alpha\beta}+\mathbf{F}_{\alpha}^{\text{ext}}=\dot{\mathbf{p}}_{\alpha} \\
\mathbf{P}&=\sum_{\alpha}\mathbf{p}_{\alpha}\quad\left(\frac{d}{dt}\right) \\
\dot{\mathbf{P}}&=\sum_{\alpha}\dot{\mathbf{p}}_{\alpha}=\sum_{\alpha}\sum_{\beta\neq\alpha}\mathbf{F}_{\alpha\beta}+\sum_{\alpha}\mathbf{F}_{\alpha}^{\text{ext}} \\
\sum_{\alpha}\sum_{\beta\neq\alpha}\mathbf{F}_{\alpha\beta}&=\sum_{\alpha}\sum_{\beta>\alpha}\cancelto{ 0 }{ (\mathbf{F}_{\alpha\beta}+\mathbf{F}_{\beta\alpha}) } \\
\therefore\quad \dot{\mathbf{P}}&=\sum_{\alpha}\mathbf{F}_{\alpha}^{\text{ext}}\equiv \mathbf{F}^{\text{ext}}
\end{align}$$
Interestingly, this law is equivalent to [[Newton's Third Law]].

Once relativity is important, this law fails because $\mathbf{F}_{21}$ and $\mathbf{F}_{12}$ can't always be simultaneous because one moment is different for different observers.