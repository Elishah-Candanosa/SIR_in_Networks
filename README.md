# The SIR Model implemented on Complex Networks

<img width="673" height="427" alt="image" src="https://github.com/user-attachments/assets/76565a43-bd43-4285-bfc8-99e80829f0b0" />


**Abstract**

This work presents a generalization of the classical SIR (Susceptible-Infected-Recovered) epidemiological model applied to complex networks—specifically **Barabási-Albert scale-free networks**. The aim is to simulate disease propagation without relying on idealizations such as a "well-mixed" society, while ensuring the model reduces to the classical case in the appropriate limit for continuous time evolution (in contrast to the discretization employed in this work).

In this context, we analyzed the impact of network topology on contagion dynamics. Furthermore, we assessed how infecting nodes with varying centralities influences the development of the pandemic, specifically utilizing **Degree, Betweenness, Closeness, Eigenvector, Katz, and Load** centrality metrics.

Numerical simulations revealed that, unlike the classical model which tends to overestimate the extent of infection, the network approach captures phenomena of local containment, reflecting real-world observations. Additionally, it was demonstrated that the centrality of "patient zero" significantly influences the propagation speed and the time to the epidemic peak, yet has only a marginal impact on the total accumulated magnitude of the pandemic. These results suggest that in scale-free networks, the global structure and the characteristics of the infectious agent predominate over the individual characteristics of the initial node.

## Paper
You may find the full PDF in this repository. It is written in Spanish, but if time allows it, an English version might be made. Nonetheless, the code is written entirely in English.

## Authors & Collaborators
* **Elishah Candanosa** - Model Design, Code Implementation, and Numerical Analysis
* **Maximiliano Rojas** - Mathematical Formalism, and Literature Review

Should you happen to have any doubt, you may contact me on my institutional email!

carlos.candanosa@correo.nucleares.unam.mx
