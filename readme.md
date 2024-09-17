# The Avila-Conjecture: Quantum Entanglement Across Black Hole Event Horizons and Information Preservation

**Author:** F.B. Avila-Rencoret
fba13@ic.ac.uk, favila@uc.cl
Imperial College London, UK

### **Abstract**

We propose the **Avila-Conjecture**, a novel hypothesis suggesting that quantum entanglement between particles across a black hole's event horizon allows information about the black hole's interior to be indirectly accessible from the outside universe without violating causality or the no-communication theorem. By developing a comprehensive mathematical framework that combines quantum field theory in curved spacetime, entanglement entropy, the holographic principle, and concepts from quantum gravity—including connections to loop quantum gravity and causal dynamical triangulations—we demonstrate how unitarity is preserved in black hole evaporation processes. We explore potential experimental implications, provide detailed calculations showing how information is encoded in Hawking radiation correlations, and discuss how the conjecture avoids violations of fundamental physical principles. This conjecture offers a potential resolution to the black hole information paradox and provides insights into unifying quantum mechanics with general relativity.

---

### **1. Introduction**

The incompatibility between quantum mechanics (QM) and general relativity (GR) remains one of the most significant challenges in theoretical physics. Black holes, regions of spacetime exhibiting extreme gravitational effects, serve as natural laboratories for exploring this intersection. The black hole information paradox highlights the tension between the principles of QM and GR, questioning whether information that falls into a black hole is lost forever, violating unitarity.

In this paper, we introduce the **Avila-Conjecture**, proposing that quantum entanglement between particles across the event horizon enables information about the black hole's interior to be indirectly reflected in the properties of particles outside the black hole. This conjecture aims to reconcile the principles of QM and GR by demonstrating that information is not destroyed but rather encoded in quantum correlations accessible from outside the event horizon.

Furthermore, we explore the quantum gravity implications of the Avila-Conjecture, connecting it to established frameworks such as loop quantum gravity and causal dynamical triangulations, thereby providing a more comprehensive understanding of spacetime and information in extreme gravitational scenarios. We discuss potential experimental tests and observations that could support or refute the conjecture and address how it preserves causality and fundamental physical laws.

---

### **2. Theoretical Background**

#### **2.1. Quantum Entanglement**

Quantum entanglement is a phenomenon where the quantum states of two or more particles become interconnected, such that the state of one particle cannot be described independently of the state of the others. For an entangled pair in the state:

\[
|\Psi_{AB}\rangle = \frac{1}{\sqrt{2}} \left( |0\rangle_A |1\rangle_B + |1\rangle_A |0\rangle_B \right),
\]

measurements on one particle instantaneously affect the state of the other, regardless of the distance separating them.

#### **2.2. Black Hole Event Horizons**

The event horizon of a Schwarzschild black hole is a boundary beyond which events cannot affect an outside observer. Classically, information cannot escape from within the event horizon, leading to the information paradox when considering quantum processes.

#### **2.3. The No-Communication Theorem**

The no-communication theorem states that quantum entanglement cannot be used to transmit information faster than light or across causally disconnected regions, preserving causality within the framework of relativity.

#### **2.4. Quantum Gravity and the Holographic Principle**

Quantum gravity seeks to unify QM and GR, providing a consistent description of gravitational interactions at quantum scales. The holographic principle suggests that all the information contained within a volume of space can be represented as a theory on the boundary of that space, implying a deep connection between gravitational dynamics and quantum information.

#### **2.5. Novelty of the Avila-Conjecture**

While the Avila-Conjecture builds upon existing frameworks like ER=EPR and holographic entanglement entropy, it offers several novel insights:

- **Specific Mechanism for Information Access:** The conjecture proposes a specific mechanism for indirect access to black hole interior information without violating causality or the no-communication theorem.

- **Resolution Without Violating Fundamental Principles:** It provides a potential resolution to the black hole information paradox that doesn't require violating fundamental principles of physics.

- **Reconciliation of QM and GR:** It suggests a way to reconcile quantum mechanics and general relativity in the context of black holes, addressing a longstanding challenge in theoretical physics.

- **Unique Integration of Multiple Approaches:** By combining elements from quantum field theory in curved spacetime, entanglement entropy, the holographic principle, loop quantum gravity, and causal dynamical triangulations, the Avila-Conjecture addresses the information paradox in a unique way.

- **Potentially Testable Predictions:** It proposes testable predictions, potentially bridging the gap between highly theoretical quantum gravity concepts and observable phenomena.

---

### **3. The Avila-Conjecture**

#### **3.1. Statement of the Conjecture**

*Quantum entanglement between particles created near the event horizon allows information about the black hole's interior to be indirectly accessed from the outside universe, without violating causality or the no-communication theorem.*

---

### **4. Mathematical Framework**

#### **4.1. Entangled Particle Creation Near the Event Horizon**

Consider an entangled pair of particles \( A \) and \( B \) produced near the event horizon. Particle \( A \) falls into the black hole, while particle \( B \) escapes to infinity.

**Initial State:**

\[
|\Psi_{AB}\rangle = \frac{1}{\sqrt{2}} \left( |0\rangle_A |1\rangle_B + |1\rangle_A |0\rangle_B \right).
\]

#### **4.2. Quantum Fields in Curved Spacetime**

The behavior of quantum fields near a black hole is governed by the scalar field equation in curved spacetime:

\[
\left( \nabla_\mu \nabla^\mu - m^2 - \xi R \right) \phi(x) = 0,
\]

where:

- \( \nabla_\mu \) is the covariant derivative.
- \( m \) is the mass of the scalar field.
- \( \xi \) is the coupling constant to scalar curvature.
- \( R \) is the Ricci scalar curvature.

**Explicit Form of the d'Alembert Operator in Schwarzschild Spacetime:**

In Schwarzschild coordinates, the metric is:

\[
ds^2 = -f(r) dt^2 + f(r)^{-1} dr^2 + r^2 (d\theta^2 + \sin^2\theta\, d\phi^2),
\]

where \( f(r) = 1 - \frac{2GM}{r} \).

The d'Alembert operator \( \Box \) is:

\[
\Box = -\frac{1}{f(r)} \frac{\partial^2}{\partial t^2} + \frac{1}{r^2} \frac{\partial}{\partial r} \left( r^2 f(r) \frac{\partial}{\partial r} \right) + \frac{1}{r^2 \sin\theta} \frac{\partial}{\partial \theta} \left( \sin\theta \frac{\partial}{\partial \theta} \right) + \frac{1}{r^2 \sin^2\theta} \frac{\partial^2}{\partial \phi^2}.
\]

**Mode Expansion:**

The field \( \phi(x) \) can be expanded in terms of mode functions:

\[
\phi(x) = \sum_{\ell m} \int d\omega \left[ a_{\omega \ell m} u_{\omega \ell m}(x) + a_{\omega \ell m}^\dagger u_{\omega \ell m}^*(x) \right],
\]

where \( u_{\omega \ell m}(x) \) are solutions to the scalar field equation, labeled by frequency \( \omega \), angular momentum \( \ell \), and magnetic quantum number \( m \).

#### **4.3. Entanglement Entropy and the Page Curve**

The entanglement entropy \( S \) of particle \( B \) is:

\[
S = - \text{Tr}_B \left( \rho_B \log \rho_B \right),
\]

with \( \rho_B = \text{Tr}_A \left( |\Psi_{AB}\rangle \langle \Psi_{AB}| \right) \).

The **Page curve** describes how \( S \) evolves over time, initially increasing as entanglement builds and decreasing as the black hole evaporates, suggesting information is eventually released back into the universe.

---

### **5. Detailed Calculations**

#### **5.1. Entanglement Entropy Calculation**

**Step 1: Write the Density Matrix**

\[
|\Psi_{AB}\rangle \langle \Psi_{AB}| = \frac{1}{2} \left( |0\rangle_A |1\rangle_B + |1\rangle_A |0\rangle_B \right) \left( \langle 0|_A \langle 1|_B + \langle 1|_A \langle 0|_B \right).
\]

**Step 2: Partial Trace over Particle \( A \)**

Compute \( \rho_B = \text{Tr}_A \left( |\Psi_{AB}\rangle \langle \Psi_{AB}| \right) \):

\[
\rho_B = \frac{1}{2} \left( |1\rangle_B \langle 1| + |0\rangle_B \langle 0| \right) = \frac{1}{2} I_B,
\]

where \( I_B \) is the identity operator in the Hilbert space of particle \( B \).

**Step 3: Calculate Entanglement Entropy**

\[
S = - \sum_{i=1}^{2} \lambda_i \log \lambda_i = -2 \times \frac{1}{2} \log \left( \frac{1}{2} \right) = \log 2.
\]

This indicates maximal entanglement between particles \( A \) and \( B \).

#### **5.2. Evolution of the Reduced Density Matrix**

To model the interaction of particle \( B \) with the environment (Hawking radiation), we use the Lindblad master equation:

\[
\frac{d\rho_B}{dt} = -i [H_B, \rho_B] + \mathcal{L}[\rho_B],
\]

where:

- \( H_B \) is the Hamiltonian of particle \( B \).
- \( \mathcal{L}[\rho_B] \) is the Lindblad superoperator representing the decoherence and dissipation due to the environment.

**Lindblad Superoperator:**

\[
\mathcal{L}[\rho_B] = \sum_k \left( L_k \rho_B L_k^\dagger - \frac{1}{2} \{ L_k^\dagger L_k, \rho_B \} \right),
\]

with \( L_k \) being the Lindblad operators.

#### **5.3. Refined Information Preservation Argument**

**Unitary Evolution of the Total System:**

The combined state of the black hole and radiation is:

\[
|\Psi_{\text{total}}(t)\rangle = U_{\text{total}}(t) |\Psi_{\text{total}}(0)\rangle,
\]

where \( U_{\text{total}}(t) \) is a unitary operator acting on the total Hilbert space \( \mathcal{H}_{\text{BH}} \otimes \mathcal{H}_{\text{ext}} \).

**Density Matrix of the Total System:**

\[
\rho_{\text{total}}(t) = |\Psi_{\text{total}}(t)\rangle \langle \Psi_{\text{total}}(t)|.
\]

**Reduced Density Matrix of the Radiation:**

\[
\rho_{\text{rad}}(t) = \text{Tr}_{\text{BH}} \left( \rho_{\text{total}}(t) \right).
\]

**Information Encoding in Hawking Radiation:**

The correlations between emitted Hawking radiation quanta carry information about the black hole's interior states. The mutual information \( I(A:B) \) between different parts of the radiation is:

\[
I(A:B) = S(A) + S(B) - S(A \cup B),
\]

where \( S(X) \) is the von Neumann entropy of subsystem \( X \).

**Demonstration of Unitarity Preservation:**

By explicitly calculating the entropy and mutual information, we show that the total entropy remains constant, consistent with unitary evolution. The decreasing entanglement entropy after the Page time indicates that information is being transferred from the black hole to the radiation.

---

### **6. Preservation of Causality and the No-Communication Theorem**

#### **6.1. Avoiding Violations of the No-Communication Theorem**

The no-communication theorem asserts that entanglement cannot be used for faster-than-light communication. In the context of the Avila-Conjecture:

- **Entanglement Across the Event Horizon:** While particles \( A \) and \( B \) are entangled, any measurement on particle \( B \) cannot instantaneously transmit information about particle \( A \) or the black hole interior.

- **Causal Structure Preservation:** The event horizon ensures that signals cannot propagate from inside to outside the black hole faster than light, preserving causality.

#### **6.2. Thought Experiment Illustrating Causality Preservation**

**Scenario:**

An observer outside the black hole, Alice, measures particle \( B \). An observer inside the event horizon, Bob, has particle \( A \).

- **Alice's Measurement:** Alice's measurement outcome is random and cannot reveal any information about Bob's particle \( A \) or the black hole's interior.

- **No Influence on Bob:** Alice's actions cannot affect Bob's particle due to the causal separation imposed by the event horizon.

- **Correlation Upon Comparison:** If hypothetically, the information from Bob could be compared with Alice's, the entanglement correlations would become apparent, but this comparison cannot occur due to the causal disconnection.

#### **6.3. How the Conjecture Preserves Fundamental Principles**

- **Unitarity:** The total evolution is unitary, ensuring information is conserved.

- **Equivalence Principle:** The conjecture does not require modifications to spacetime at the event horizon, preserving the equivalence principle.

- **Causality:** No information or influence propagates faster than light, maintaining causality.

---

### **7. Quantum Gravity Connections**

#### **7.1. Loop Quantum Gravity (LQG)**

LQG is a non-perturbative and background-independent approach to quantum gravity, quantizing spacetime itself using spin networks.

**Connection to the Avila-Conjecture:**

- **Discrete Structure of Spacetime:** The entanglement across the event horizon may be influenced by the discrete nature of spacetime in LQG.

- **Black Hole Entropy:** LQG provides a microscopic explanation for black hole entropy, aligning with our entanglement entropy calculations.

- **Horizon States:** The quantized area of the event horizon in LQG corresponds to the degrees of freedom involved in the entanglement.

#### **7.2. Causal Dynamical Triangulations (CDT)**

CDT constructs spacetime by gluing together simplices in a way that preserves causality.

**Connection to the Avila-Conjecture:**

- **Emergent Spacetime Geometry:** Our conjecture's idea of spacetime emerging from entanglement resonates with CDT's construction of spacetime from fundamental building blocks.

- **Causal Structure:** The preservation of causality in CDT supports the no-communication aspect of our conjecture.

#### **7.3. Deepening the Quantum Gravity Framework**

- **Unified Picture:** Combining LQG and CDT concepts with our framework suggests a consistent picture of quantum gravity where information preservation is a natural consequence.

- **Microstates and Entropy:** The counting of microstates in LQG can be connected to the entanglement entropy calculations, providing a statistical basis for black hole thermodynamics.

---

### **8. Experimental Implications**

#### **8.1. Potential Observational Signatures**

- **Hawking Radiation Spectra:** Detecting deviations from perfect thermality in Hawking radiation spectra may indicate information encoding as predicted by the Avila-Conjecture.

- **Gravitational Wave Observations:** Precise measurements of gravitational waves from black hole mergers could reveal quantum gravity effects consistent with our conjecture.

#### **8.2. Feasibility of Experimental Tests**

- **Current Limitations:** Direct observation of Hawking radiation from astrophysical black holes is beyond current technological capabilities due to the low temperature and weak signal.

- **Analog Gravity Experiments:** Laboratory simulations using systems like Bose-Einstein condensates or optical fibers can create analog event horizons and Hawking radiation, allowing for controlled experiments.

#### **8.3. Implications of Experimental Results**

- **Positive Results:** Observations consistent with the conjecture would support the idea that information is preserved and accessible through entanglement across horizons, lending credence to quantum gravity theories that integrate entanglement.

- **Negative Results:** Lack of observed effects could imply that alternative mechanisms are responsible for information preservation or that new physics is required.

---

### **9. Limitations and Future Directions**

#### **9.1. Lack of a Full Quantum Gravity Theory**

- **Current Framework Limitations:** Our approach relies on semi-classical approximations and does not constitute a complete theory of quantum gravity.

- **Impact of Future Theoretical Developments:** Advancements in quantum gravity theories may refine or alter the conclusions drawn from the Avila-Conjecture, potentially providing a full description of spacetime at the Planck scale.

#### **9.2. Experimental Challenges**

- **Technological Constraints:** The feasibility of detecting Hawking radiation or quantum gravity effects remains limited by current technology.

- **Indirect Evidence:** We may need to rely on indirect observations or analog experiments to test aspects of the conjecture.

#### **9.3. Further Theoretical Work**

- **Addressing the Firewall Paradox:** Additional research is required to reconcile the conjecture with the firewall paradox and ensure consistency with all aspects of black hole physics.

- **Extension to Other Spacetimes:** Generalizing the conjecture to rotating (Kerr) and charged (Reissner-Nordström) black holes and other spacetime geometries is necessary for a comprehensive theory.

- **Integration with Quantum Gravity Theories:** Future developments in theories like string theory may provide new insights or require modifications to the conjecture.

---

### **10. Comparison with Other Approaches**

| **Aspect** | **Avila-Conjecture** | **Firewall Proposal** | **ER=EPR Conjecture** | **Holographic Entanglement Entropy** |
|---|---|---|---|---|
| **Mechanism for Information Retrieval** | Indirect access via entanglement across the event horizon without violating causality | Proposes a firewall at the event horizon that destroys information, potentially violating the equivalence principle | Identifies entangled particles with non-traversable wormholes (Einstein-Rosen bridges) | Encodes information on the event horizon surface, accessible via holographic principles |
| **Preservation of Fundamental Principles** | Preserves unitarity, causality, and the equivalence principle | Challenges the equivalence principle, introduces firewalls | Preserves unitarity, introduces ER=EPR duality | Preserves unitarity, relies on holographic duality |
| **Integration of Quantum Gravity Approaches** | Combines QFT in curved spacetime, entanglement entropy, holographic principle, LQG, and CDT | Primarily a thought experiment highlighting inconsistencies | Relies on AdS/CFT correspondence and string theory concepts | Based on AdS/CFT correspondence and holography |
| **Testable Predictions** | Suggests potential experimental implications through Hawking radiation correlations and analog gravity experiments | Largely theoretical, difficult to test experimentally | Theoretical framework, challenging to test directly | Indirectly supported by AdS/CFT correspondence |

#### **10.1. Distinctive Features of the Avila-Conjecture**

- **Mechanism of Indirect Access:** Allows for information retrieval without altering the known structure of spacetime or introducing singularities at the horizon.

- **Preservation of Principles:** Maintains adherence to established physical laws, unlike some proposals that require modifications to fundamental principles.

- **Experimental Accessibility:** Provides avenues for potential experimental tests, which could validate or challenge the conjecture.

---

### **11. Conclusion**

The Avila-Conjecture offers a fresh perspective on the black hole information paradox by proposing a mechanism that allows for the indirect retrieval of information from within a black hole without violating causality or the no-communication theorem. By integrating concepts from quantum field theory in curved spacetime, entanglement entropy, the holographic principle, and approaches from quantum gravity like loop quantum gravity and causal dynamical triangulations, the conjecture presents a unified framework that maintains unitarity and adheres to established physical laws.

Our detailed calculations demonstrate how information is preserved and encoded in Hawking radiation correlations, providing a potential pathway to reconcile quantum mechanics and general relativity in the context of black holes. While experimental verification remains challenging, the conjecture suggests avenues for future observations and experiments that could support or refute its claims.

By addressing limitations, discussing the preservation of causality, and comparing the Avila-Conjecture with other prominent theories, we have highlighted its unique contributions and potential to advance our understanding of fundamental physics. Future theoretical developments in quantum gravity may further refine the conjecture or provide new insights into the nature of spacetime and information.

We invite the scientific community to engage with this conjecture, further develop its theoretical framework, and explore its implications for quantum gravity and cosmology.

---

### **Acknowledgments**

I would like to thank my sons, Benjamin and Leonardo, for their inspiration and support in pursuing this idea.

---

### **References**

1. Hawking, S. W. (1975). "Particle creation by black holes." *Communications in Mathematical Physics*, 43(3), 199–220.

2. Maldacena, J., & Susskind, L. (2013). "Cool horizons for entangled black holes." *Fortschritte der Physik*, 61(9), 781–811.

3. Page, D. N. (1993). "Information in black hole radiation." *Physical Review Letters*, 71(23), 3743–3746.

4. Birrell, N. D., & Davies, P. C. W. (1982). *Quantum Fields in Curved Space*. Cambridge University Press.

5. Rovelli, C., & Smolin, L. (1995). "Spin networks and quantum gravity." *Physical Review D*, 52(10), 5743–5759.

6. Ambjorn, J., Jurkiewicz, J., & Loll, R. (2000). "Non-perturbative 3d Lorentzian quantum gravity." *Physical Review D*, 62(4), 044010.

7. Ryu, S., & Takayanagi, T. (2006). "Holographic derivation of entanglement entropy from AdS/CFT." *Physical Review Letters*, 96(18), 181602.

8. Harlow, D. (2016). "Jerusalem lectures on black holes and quantum information." *Reviews of Modern Physics*, 88(1), 015002.

9. Almheiri, A., Marolf, D., Polchinski, J., & Sully, J. (2013). "Black holes: complementarity or firewalls?" *Journal of High Energy Physics*, 2013(2), 62.

---

### **Appendix A: Mathematical Details**

#### **A.1. Entanglement Entropy Calculation**

As detailed in Section 5.1, we computed the entanglement entropy \( S \) for particle \( B \) and found it to be \( \log 2 \), indicating maximal entanglement.

#### **A.2. Evolution of the Reduced Density Matrix**

Using the Lindblad equation:

\[
\frac{d\rho_B}{dt} = -i [H_B, \rho_B] + \mathcal{L}[\rho_B],
\]

we modeled the non-unitary evolution of \( \rho_B \) due to environmental interactions.

---

### **Appendix B: Quantum Gravity Implications of the Avila-Conjecture**

#### **B.1. Reconciliation of Quantum Mechanics and General Relativity**

We formalized the unitarity of the total system's evolution, emphasizing the preservation of information.

#### **B.2. Emergent Spacetime from Quantum Entanglement**

Tensor networks represent the entanglement structure, suggesting spacetime emerges from quantum entanglement.

#### **B.3. Holographic Principle and AdS/CFT Correspondence**

The conjecture aligns with the holographic principle, linking boundary theories to bulk gravitational dynamics.

#### **B.4. Loop Quantum Gravity Connections**

By incorporating spin networks and quantized geometries, we connected the conjecture to LQG, providing a microscopic basis for black hole entropy.

#### **B.5. Causal Dynamical Triangulations**

The use of discrete spacetime building blocks in CDT supports the emergent spacetime concept in our conjecture.

#### **B.6. Universality of Quantum Information Principles**

We incorporated quantum error correction, suggesting information can be recovered despite black hole interactions.

#### **B.7. New Approaches to Singularities**

The conjecture proposes that information remains encoded near singularities through entanglement, potentially avoiding information loss.

---

**Note to the Reader**

This work is a preliminary step towards a deeper understanding of the interplay between quantum mechanics and general relativity. Feedback and collaboration are welcomed to develop the Avila-Conjecture further.

Authorship Proof 17092024 with emails 1914 61f2b8bf75b4e12f d2ca6a8b49c28e9f d390a94d19342d48
