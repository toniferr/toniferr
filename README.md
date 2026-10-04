# Hi, I'm Toni 👋

*Computer science, from the bottom up, in five lines of mathematics.*

**1 · Logic.** One gate is enough for every Boolean function $f:\lbrace 0,1\rbrace^n\to\lbrace 0,1\rbrace$:

$$\mathrm{NAND}(x,y)=1-xy,\qquad \neg x=\mathrm{NAND}(x,x),\qquad x\wedge y=\neg\,\mathrm{NAND}(x,y).$$

**2 · Automata.** Finite memory makes a finite automaton, $M=(Q,\Sigma,\delta,q_0,F)$ with $\delta:Q\times\Sigma\to Q$.
It recognises exactly the regular languages, and it cannot count: $\lbrace a^nb^n\rbrace$ is out of reach. Climbing
Chomsky's hierarchy adds power:

$$\mathsf{REG}\subsetneq\mathsf{CFL}\subsetneq\mathsf{CSL}\subsetneq\mathsf{RE}.$$

**3 · Computation.** An unbounded tape gives Turing's machine, $\delta:Q\times\Gamma\to Q\times\Gamma\times\lbrace L,R\rbrace$,
and the first impossible problem: no program decides, for every program, whether it halts.

$$\nexists\,H\ \ \forall\,M,w:\quad H(\langle M\rangle,w)=\mathbf{1}[\,M \text{ halts on } w\,].$$

**4 · Information.** Learning is compression: every LLM minimizes the cross-entropy between the data and its model.

$$H(p,q)=H(p)+D_{\mathrm{KL}}(p\,\|\,q)\ \ge\ H(p)=-\sum_x p(x)\log_2 p(x).$$

**5 · Quantum.** Swap the 1-norm of probabilities for the 2-norm of complex amplitudes, and a bit becomes a qubit:

$$|\psi\rangle=\alpha|0\rangle+\beta|1\rangle,\qquad |\alpha|^2+|\beta|^2=1.$$

The long version, with proofs and interactive demos, is in **[Math of AI](https://toniferr.github.io/math-of-ai/)** and
**[Math of Quantum](https://toniferr.github.io/math-of-quantum/)**.

## 🔭 Currently

- Expanding the GitOps course module by module (Kustomize, Helm, multi-environment, secrets…).
- Writing more chapters and demos for the math sites.
- Exploring AI agents for software engineering, with **Claude Code** as a daily companion.

---

<sub>Built with plain Markdown. Say hi on <a href="https://es.linkedin.com/in/antonio-ferreiro-couto">LinkedIn</a> or visit <a href="https://toniferr.github.io/">my site</a>, in Spanish, English and Galician.</sub>
