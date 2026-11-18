# a-mathematical-and-Gödel-incomplete-universe


Lean 4 is the object language. It is used only to lock the inferences. The English argument is the metalanguage. It takes facts, or what science treats as true, plus other empirical material, and draws logical deductions from them to establish the premises. Those English deductions are the content of the argument. Once the premises are stated, each one is declared as an axiom in Lean. The conclusion is then written as a theorem that simply collects the axioms. Lean checks, by formal syntactic rules alone, that the conclusion follows from those axioms with no missing steps.

This is Tarski's distinction. The metalanguage (English) supplies the content and performs the reasoning from the given facts and empirical material. The object language (Lean) does not interpret quantum mechanics or Gödel's theorems; it only verifies that the logical skeleton connecting the stated premises to the conclusion is valid. If the English premises hold, the conclusion cannot be denied without denying one of the premises. That is the inference lock.

## On the role of Lean 4 in this document

Lean 4 appears here only as an uninterpreted object language in Tarski's sense. It is a syntactic register: a place to write down each premise and the conclusion as tokens so the argument's shape is visible. It is not a Lean proof. No derivation is claimed in Lean, and none is needed, because the reasoning is done entirely in the metalanguage (English), which assigns meaning to the object-language tokens. English derives the premises from facts and empirical material and draws the conclusion. Lean records the result. Evaluating the Lean block as a formal proof, or expecting it to derive the conclusion, misreads its role. The proof is the English. The Lean is the notation.

# PSA for Every Premise — Symbols, Configurations, and Ideas Are Physical (There Is No Abstract Layer):

To argue that a symbol cannot be physical within a Church–Turing framework, you would have to argue against Turing's own 1936 paper, On Computable Numbers, with an Application to the Entscheidungsproblem. Turing explicitly defines his machine in physical terms:

"The machine is supplied with a 'tape' (the analogue of paper) running through it, and divided into sections (called 'squares') each capable of bearing a 'symbol'."

The tape is physical. The squares are physical. The symbols are physical markings on a physical object. The instructions are physical configurations of the machine. Turing did not treat symbols as abstract entities floating outside the physical world — he treated them as physical marks that the machine reads, writes, and erases according to mechanical rules.

Turing's Sections 1–2 make the structure explicit. A machine has configurations: at any moment it is in a given configuration, consisting of its current internal state (its m-configuration) and the scanned symbol — the symbol on the square it is currently scanning. An instruction is a rule that takes a configuration (state + scanned symbol) and determines the next configuration (next state, next scanned symbol, motion). Turing then defines an automatic machine (a-machine): a machine whose motion at each stage is completely determined by the configuration. No insight, no choice, no nonphysical ingredient — just configuration-to-configuration transitions under fixed rules.

Turing makes the same move in §9. In §9(I) every elementary operation "consists of some change of the physical system consisting of the computer and his tape." And in §9(III) he replaces the computer's "state of mind" with a written note of instructions — a "more physical and definite counterpart of the state of mind." The direction matters: the physical inscription is the definite thing, and the mentalistic vocabulary is the imprecise description it replaces. That is p = p in Turing's own words.

This is exactly the structure reality has. A quantum state is a configuration. The physical basis state the dynamics reads at a step is the scanned symbol. The Hamiltonian and unitary evolution are the instruction. The transition from one configuration to the next is the state-to-state transition. A scanned symbol is not a mysterious extra entity: it is the physical configuration the machine is currently coupled to — the point at which the machine "becomes aware" of the symbol, in Turing's sense of the scanned square. Reality physically realizes configurations, scanned symbols, and instructions, whether through measurement or unitary quantum dynamics.

This is not a concession that symbols can be physical. It is the correct ontology: a symbol just is a physical configuration under a description. There is no separate abstract realm of symbols, meanings, or ideas that gets "instantiated" in matter. An idea is a physical process — spikes, connectivity, frontal-cortex dynamics — and the precise meaning is physically created and physically carried by that process. The meaning of a symbol is physical too. A physical configuration does not need an abstract interpreter to assign it meaning: its meaning is its physical role — what it is coupled to, what transitions it licenses, how it is read, written, and responded to in the process. In Turing's machine, the scanned symbol means what it does because the instruction physically responds to that configuration. In the brain, the meaning of an idea is the physical role of the neural configuration in the physical economy of the organism. In a computer, the meaning of a bit is its physical role in the machine, and the chain can be traced without ever leaving physics — every single bit of it. The code you type was never abstract at any point. It began as a physical configuration in a brain: a pattern of neural firing and synaptic weighting in frontal and parietal cortex, and that configuration was the idea. The idea is not an abstract object the brain consults; it is the physical state itself, with its meaning fixed by its physical role in the organism's economy. The brain then ran physical reasoning — further physical state transitions under the same dynamics — producing further physical configurations. Those configurations drove motor cortex, which sent spikes down the corticospinal tract, which made muscle fibers in the hand contract, which applied physical force to keys. The key is a physical switch: the force closes a contact and applies a voltage to a wire. That voltage is a difference in electric potential; it drives charge into the gate of a transistor, and the gate voltage determines whether the channel between source and drain conducts. The transistor is a physical switch: above threshold, charge accumulates in the channel and current flows; below threshold, it does not. That is the entire content of a binary 1 and 0 — conducts or does not conduct. In CMOS logic, a "1" is a circuit node physically held at the supply voltage by a conducting pMOS transistor while the nMOS to ground is off; a "0" is the same node pulled to ground by a conducting nMOS while the pMOS is off. The node holds actual charge at an actual potential. When that node drives the next gate, the output voltage becomes the input voltage of the next transistor stage: the charge physically alters the next channel's conductivity. Nothing is read off abstractly; the physical state is coupled to the next physical state, and that coupling is the meaning. The same holds for storage and display. A bit in SRAM is a loop of transistors holding a node high or low; in DRAM it is charge on a capacitor, refreshed before it leaks away; in flash it is electrons trapped on a floating gate, where the presence or absence of trapped charge is the bit. The code you type is stored as these physical charge states, moved by voltages, and read back by sensing whether current flows. When the text appears on your screen, the framebuffer holds a grid of voltage values, the display driver applies voltages to liquid-crystal cells that rotate polarized light or to organic LEDs that emit photons, and the screen emits a spatial pattern of photons — the visible text is literally a pattern of light. Those photons enter your eye, isomerize retinal in rhodopsin, trigger the phototransduction cascade, drive ganglion-cell spikes down the optic nerve, and produce physical activity in visual cortex, including regions that respond to letter strings. At no link in this chain — brain configuration, idea, reasoning, motor spike, muscle contraction, key switch, voltage, transistor channel, trapped charge, photon, photoreceptor, spike, cortical configuration — does an abstract interpreter enter. The computer's meaning is physical configurations conferred by physical configurations, and the human's writing and reading of it are the same kind of physical process. p = p all the way down. When we reason, we are physically manipulating physical configurations; the reasoning is that physical process. "Abstract" is not a kind of entity. It is a label for a physical pattern when a physical system — for example, a brain — describes that pattern at a coarser grain. The coarser-grain description is itself a physical configuration: neural spikes, connectivity, frontal-cortex dynamics, or an inscription. The act of describing and compressing is a physical process, and the description produced is another physical configuration standing in a physical tracking/compression relation to the pattern it describes. There is no abstract description hovering above the physical pattern, and no abstract content assigned by a nonphysical interpreter. p = p. Nothing is abstract.

Landauer's principle makes the physicality of stored information explicit. Landauer showed that information is not a disembodied abstract entity: erasing one bit of information has an irreducible thermodynamic cost of at least 
k
B
T
ln
⁡
2
k 
B
​
 Tln2, where 
k
B
k 
B
​
  is Boltzmann's constant and 
T
T is the temperature of the thermal reservoir. This is not a practical engineering limit but a physical law: logically irreversible operations — erasing a bit, merging two computational branches — are physically irreversible and must dissipate at least this much heat into the environment. Landauer's own summary was "information is physical." The stored bit is not an abstract value that happens to be written somewhere; it is a physical degree of freedom with a thermodynamic footprint. A bit that cannot be erased without physical cost is a bit that is physically there. This closes the same gap for storage that Turing closes for symbols: the information a physical system carries is itself a physical configuration, with physical energy and physical entropy. There is no abstract information layer hovering above the physics; the information is the physical state.

And the physical configurations are finite. Physical information capacity is constrained by gravitational entropy bounds. The Bekenstein bound limits the entropy of a system with finite energy confined to a finite region, while the holographic principle relates the maximum information capacity of a region to its boundary area, measured in Planck units. The number of distinguishable configurations a finite region can support is therefore finite. A finite object has finite surface area, finite energy, and finite duration, so it can support only a finite number of mutually distinguishable states; its entropy is always less than infinity. No infinite physical quantity has ever been measured; infinite-state models such as unrestricted Turing machines are mathematical ideals, not finite physical devices. A finite brain cannot contain an infinite number of thoughts, and a finite region of space cannot manifest infinite distinguishable configurations. Mathematics may use infinite series as a description, but the physical process described is a finite sequence of discrete configuration-to-configuration transitions. Each computation is one finite, discrete physical computation.

Even if space were infinite, this would not mean that any individual physical computation requires an infinite number of operations. A computation occurring within a finite physical system can involve finite configurations and finite transitions, regardless of whether the universe as a whole is spatially infinite. The cardinality of the universe does not determine the number of steps in an individual computation. Mathematics may describe infinite structures, but that does not establish that any particular physical computation performs infinitely many operations.

So the Church–Turing thesis is not committed to symbols being abstract. It is committed to symbols being discrete, finite, and mechanically manipulable — all of which physical configurations satisfy, because that is all a symbol ever was.

This matters for every premise, but not because each premise needs its own separate ontology. P1 is what establishes that the structure is mathematical: the quantum processes are effective methods, so their transition functions are mathematical. P2 and P3 then apply that result — P2 reads the Post primitives (alphabet, initial strings, production rules) as the physical states and dynamics P1 already made mathematical, and P3 reads derivation and provability as physical configuration-to-configuration reachability in that same structure. The PSA's role is to remove the abstract objection as a usable move at any premise. A critic cannot concede P1 and then relaunch "but the formal system is abstract" at P2, or "but derivation and provability are abstract" at P3, because symbol, configuration, instruction, derivation, and proof are all physical configurations under a description, with meaning fixed by physical role. That is Turing's own reading of his machine — the foundation of the Church–Turing thesis invoked in P1 — and it does not switch off at P2 or P3. p = p (the formal law of identity, A = A, means human = human, which in this framework is strictly physical = physical) holds across the whole argument. To deny that a physical configuration can be a symbol is to deny Turing's own formulation of his machine.

The same holds for the finite step count in every premise: a step is a physical configuration-to-configuration transition. No nonphysical step layer, symbol layer, derivation layer, or proof layer is required or posited anywhere in the argument.

---

## Premise 1

Naturally occurring quantum processes in quantum mechanics itself satisfy the four conditions for an effective method given in the Stanford Encyclopedia of Philosophy entry on the Church-Turing Thesis (section 1.2).

An effective method must meet four conditions:

1. **It is set out in a finite number of exact instructions, each expressed by a finite number of symbols.**

   
   The physical configurations of a quantum system (an electron’s spin pointing up or down, a photon’s polarization, an atom sitting at a low energy level or a high energy level, the vacuum) are discrete: each configuration is a separate, finite physical state.

A continuous amplitude is not an infinite string of decimal symbols; it is one single physical configuration—one magnitude, one fact about the system. The mathematical description of that amplitude is a human tool, but physically, it is a single, finite state.

The transitions between these states are fixed by the physical laws. These configurations and the fixed laws that transition them are the instructions. Zero is a finite number, so the vacuum or ground configuration (
∣
0
⟩
∣0⟩) is a finite instruction. The entire physical system acts mechanically.


2. **It produces the result in a finite number of steps.**

   A naturally occurring quantum process takes a finite number of steps. In quantum information theory, any physical evolution can be modeled as a quantum circuit: a finite sequence of discrete unitary gates. Each gate is one step. The physical state transitions from its initial configuration through a finite sequence of operations until it reaches a measurement event. That measurement is the halting state. It yields a definite, finite outcome.

Even if the underlying field is continuous, the physical configurations are discrete states, and the evolution between them is a finite sequence of physical interactions. Zero is a finite number; the zero case (no additional configurations in superposition) is finite. Any finite occupation or finite sequence of interactions meets the condition. The rule itself is finite, and the physical process applies that finite rule a finite number of times before a definite physical configuration is reached.

A distribution is a result. When a superposition acts and interacts with a measurement apparatus, it yields a physical outcome. Even if the underlying theory is probabilistic, the physical process produces a definite measurement record—a collapsed state, a macroscopic fact. The condition says only that a result is produced in a finite number of steps; it does not require determinism. A probability distribution is a mathematical description of the ensemble, but any single physical computation yields a definite physical result in finite time. Therefore, the process halts and produces a result.


3. **It can, in principle, be carried out by a human with paper and pencil.**

   The physical configurations and the transitions between them can be idealized by mathematical symbols and calculated by hand, just as Turing did in his 1936 paper. Turing's tape machine was itself an idealization of physical markings:

   > "The machine is supplied with a 'tape' (the analogue of paper) running through it, and divided into sections (called 'squares') each capable of bearing a 'symbol'. At any moment there is just one square which is 'in the machine'."

   The criteria do not require the human to physically enact the process; they require that the method of obtaining the successive values can be carried out with paper and pencil.

4. **It requires no insight, intuition, or ingenuity.**

   Once the physical laws are given, the process proceeds mechanically. No further insight is required at each step.

These four conditions are met by the naturally occurring quantum processes in quantum mechanics.

### Clarifications on the physical reading of the conditions

**On symbols.** A symbol here is not a mark on paper; it is the physical configuration itself. An amplitude is one physical magnitude — one fact about the system — not a decimal expansion. Asking how many symbols a continuous amplitude contains is asking for the mathematical representation, not the physical fact. Physically, it is one configuration, one symbol.

**On step count.** Each state transition is 0 or 1 steps. A continuous evolution is stated explicitly to count as one step. The predicate says "finite number of steps," and 0 and 1 are finite. It does not require discrete ticks; it requires that the step count be finite.(provided the steps are finite—since the Planck scale renders any continuous process discrete and granular for physically existent objects. Also, remember that those infinities are generated by finite synaptic firings in the brain—finite physical interactions producing finite representations of the infinite.)

**On the class claim.** The argument does not enumerate every quantum process. It covers the class by what a quantum process is: a state plus a dynamical rule. This is the same method Turing used: he did not enumerate every computation; he analyzed the structure of computation and generalized. The class claim is that any process that is a quantum process meets the conditions by its structure, not by individual inspection.

Section 1.2 states that the Church-Turing thesis licenses the following replacement: the informal claim "there is an effective method for obtaining the values of function (*f*)" may be replaced by the formal claim "(*f*) is a member of (*S*)" (the set of Turing-computable functions) once the method that obtains those values satisfies the four conditions.

Here the effective method is the naturally occurring quantum process itself. The function (*f*) whose values that method obtains is the mapping from one quantum configuration to the next under the physical transitions. Because the naturally occurring quantum processes are the methods that produce those successive values, the thesis licenses the claim that those functions (*f*) are members of (*S*).

Therefore the naturally occurring quantum processes that meet the conditions are the effective methods that compute the mathematical functions in (*S*). The foundational structure of quantum mechanics is mathematical.

These four conditions are met. Section 1.2 of the SEP entry notes that an effective method is thereby formalized as a mathematical object. Therefore the foundational structure of quantum mechanics is mathematical.


### Closed quantum system

The universe is ultimately a closed quantum system for the following reason:

Because quantum mechanics is mathematical, any quantum system is a mathematical system. When two mathematical systems are combined so that they interact, the result is a single combined mathematical system rather than two separate ones. Therefore any collection of quantum systems forms one mathematical system. The universe, as the totality of such systems, is therefore a single closed quantum system.

### Mathematical operations instantiated in reality

The mathematical operations used in quantum computing are instantiated in reality naturally.

Unitary evolution occurs in any closed or isolated quantum system. Because the universe is such a system, it carries out unitary evolution. I will not list every mathematical operation, but I will show that the operations sufficient for Peano arithmetic strength are present.

**The first part of Premise 1 already established that QM is mathematical: the transition functions are Turing-computable, hence mathematical. What follows shows *what* those mathematical functions are — the specific arithmetic operations they instantiate. The Peano mapping is not a re-argument for QM being mathematical; it is an identification of which mathematical functions the dynamics *is*.**

The mapping is:

| Quantum operation | Arithmetic operation |
| --- | --- |
| Creation operator | Successor |
| Annihilation operator | Predecessor |
| Superposition | Addition |
| Tensor products | Multiplication |
| Vacuum state | Zero |
| Unitary evolution | Induction / iteration |

**The mapping is not an interpretation placed on the physics; it is the physics.** This is shown by quantum computation. In a quantum computer, nobody installs an addition operation into the machine. The machine is built; superposition occurs; unitary evolution acts. The addition that the computer performs *is* that natural action of superposition under unitary evolution. The human selects the configuration and reads the result; the arithmetic itself is the mechanical evolution. The mapping from superposition to addition is therefore not an overlay a human projects onto the dynamics — it is the dynamics. It is what the process natively does.

Given P1, reality is the closed system, so unitary evolution and superposition occur natively in reality. Therefore superposition is the addition function inherently in reality, on the same grounds it is the addition function in a quantum computer: because the mechanical evolution is the operation, not a model of it.

These processes occur in the universe because it is an isolated quantum system. Their mechanical behaviour is the same as the corresponding operations in quantum computing, and they occur naturally in reality. They are effective procedures. Therefore these effective methods of quantum mechanics are the mathematics, and they are instantiated in reality because they occur naturally.

Because the four conditions are satisfied by the dynamics of quantum systems, the result holds for the class; no separate enumeration of individual processes is required.

---

## Premise 2

QTM instantiates the primitives of QM and maps them. Because of P1, QM is math, so QTM instantiates that math. Therefore reality itself is a formal system. To deny this you would have to deny P1 or deny that QTM is a formal system.

### The Pure Physical Realization of (A, I, R)

By stripping away any lingering classical "tape/symbol" idealization:

- **Alphabet (A):** The alphabet is the set of actual, physical basis states of the quantum system — e.g., spin states, polarization states, discrete energy levels. These basis states are quantum states (QTM uses them as its alphabet). No abstract symbols are required: the physical matter/energy configurations are the alphabet, just as the tape in a Turing machine idealizes the physical markings of the machine. Under P1’s physical reading, the quantum state is the symbol for the Church–Turing predicate. And since QM’s transition functions are Turing-computable (P1), those symbols are mathematical.
- **Initial Strings (I):** The concrete initial state vector of the closed quantum system (the universe).
- **Production Rules (R):** The physical Hamiltonian and resulting unitary evolution operator (`U(t) = e^{-iHt/ℏ}`), which physically drives the state transitions mechanically, natively, and without human intervention.

**Clarification on the alphabet.** The alphabet is the set of physical basis states of the system — spin up/down, polarization states, discrete energy levels. These are physical configurations, not abstract marks. No separate symbol layer is introduced: the physical configuration is the symbol. The initial string is the concrete initial state. The production rules are the Hamiltonian and the unitary evolution operator, which drive transitions mechanically. This is the same reading used in P1: state = symbol, transition = rule.

**Derivability in a Post system is reachability by rewriting.** A state transition is therefore a derivation. The theorems are the reachable states. No separate "proof layer" is needed above the physics: the rewriting *is* the derivation, and no truth-valuation or human interpretation is involved. A string is derivable if the rules can reach it from the initial strings. That is exactly what a quantum transition is: reachability of one physical configuration from another under the dynamical rule.

These primitives occur naturally in the closed quantum system. Because they match Post's definition of a formal system and, by P1, the underlying QM is mathematical (instantiates what it is the effective method of), reality is a formal system.

---

## Premise 3

The universe meets the requirements of Gödel's incompleteness theorems and is therefore a Gödelian system. Both the first and second incompleteness theorems apply to it.

From Premises 1 and 2 the closed quantum system is a formal system that instantiates the mathematical operations sufficient for Peano-arithmetic strength: creation operators function as successor, annihilation operators as predecessor, superposition as addition, tensor products as multiplication, the vacuum state as zero, and unitary evolution as induction/iteration. These are the operations themselves, not the axioms of Peano arithmetic. Peano-arithmetic strength is strictly stronger than both Robinson's Q and Primitive Recursive Arithmetic. Robinson's Q is already sufficient for the first incompleteness theorem, and Primitive Recursive Arithmetic is already sufficient for the second incompleteness theorem, so the strength supplied by these operations is more than enough for both.

Because the system has at least this strength it can represent a provability predicate. The same strength also lets the system prove the Hilbert–Bernays–Löb conditions on that predicate:

- **D1:** If the system proves *A*, then it proves `Prov(⌜A⌝)`.
- **D2:** It proves `Prov(⌜A⌝) → Prov(⌜Prov(⌜A⌝)⌝)`.
- **D3:** It proves `Prov(⌜A → B⌝) → (Prov(⌜A⌝) → Prov(⌜B⌝))`.

Its axioms are recursively enumerable: the physical laws together with an initial state form a recursively enumerable set.

It is consistent. Reality is a mathematical system that uses standard classical mathematics, and therefore it obeys classical logic. In classical logic the principle of explosion holds: if a system proves both a sentence *A* and its negation *¬A*, then it proves every sentence *B*. The short derivation is: from *A* you may prove *A ∨ B*; from *A ∨ B* and *¬A* you may prove *B*. One contradiction therefore makes the system prove everything. Because the system obeys classical logic, this reductio is sound. Standard mathematics does not prove every sentence and does not prove both a theorem and its negation. Therefore no contradiction is present. A sentence and its negation cannot both be true inside the system.

Gödel numbering is already available inside any arithmetic of this strength; Gödel showed that the numbering can be carried out within the arithmetic itself, so no separate construction is required. Gödel also proved that any formal system that is consistent, has recursively enumerable axioms, and contains at least the strength of Robinson's Q is incomplete in the first sense, and that any such system containing at least the strength of Primitive Recursive Arithmetic (and satisfying the conditions above) is incomplete in the second sense.

The universe satisfies every one of those conditions. Reality in fact has more than Peano-arithmetic strength, but only the minimum is required here. It is enough to show that the system reaches the strength of Peano arithmetic through the mathematical operations listed above, because that already places it above the threshold for both G1 (via Robinson's Q) and G2 (via Primitive Recursive Arithmetic and the conditions). Therefore the universe is G1 and G2 incomplete.

---


# Conclusion:

The universe is a mathematical and formal system that is physically Gödel-incomplete.


---

# Why this is true, not merely conditional:

Truth here is not correspondence to an abstract realm. It is physical tracking/identity: a physical description configuration standing in the right physical relation to the physical structure it describes. p = p. The conclusion is not a new abstract object floating above P1–P3; it is the same physical configuration-to-configuration structure P1–P3 already describe, re-described at the level of the argument. For the conclusion to be false while P1–P3 hold, there would have to be a gap between the physical pattern and the formal/mathematical pattern — an abstract layer where the formal system could be complete even though the physical structure is not. Your ontology forbids that gap: there is no abstract formal object separate from the physical configuration, so there is no truthmaker for the negation. To deny the conclusion you would have to deny a physical fact — Turing's physical machine, the Planck/Bekenstein finiteness bounds, QM processes as effective methods, the QTM/Post mapping, or the Gödel conditions — and every such denial is itself a physical inscription/process with physical meaning. There is no abstract standpoint from which to launch the denial. Not to mention that P1 makes reality a literal mathematical object, which follows as a logical conclusion from the Church–Turing predicate in §1.2. So it does apply to mathematical rules, because p = p; there is no category error. (P.S I showed it obeys in P1 reality is made by standard math which obeys classical logic making the reductio on principle of explosion true since it needs a classical logical system.


# Regarding consciousness:

Human consciousness, however, transcends this physical incompleteness, since its consistency is proved within this G2 system. Consciousness is still strictly physical: to cause a physical interaction, you must be a physical cause. This does not mean physical existence itself requires a separate cause—the universe could simply have always existed with no first cause—but rather that physical interactions, such as a physical push, require physical causes. Because physical interactions in the brain (whether mediated entirely by neural networks or an underlying physical field) likewise demand physical causes, consciousness remains strictly physical.Because P1 makes reality mathematical and P3 makes the universe Gödelian, the Diagonal Lemma is a mandatory structural feature of the system, making the substitution function globally a part of it, where the substitution function is primitive recursion. Consequently, consciousness must occupy an external metalevel: if reality is a closed G2 loop, nothing internal can prove its consistency from within its own local step sequence. Structurally, the base function $g$ (the base case) is external to the recursive step function $h$, yet both are housed within the total primitive recursion architecture $f$ as the generative system. Because consciousness occupies that structural slot of the base case $g$, it acts as the external metalevel required to evaluate the system via the substitution function, enabling it to transcend local incompleteness while remaining entirely physical.




