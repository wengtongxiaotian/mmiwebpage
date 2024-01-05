---
title: "The Inconvenient Truth About Quantum Computing"
categories:
  - Blog
tags:
  - link
  - Post Formats
link: https://science.thewire.in/the-sciences/quantum-computing-qubits-error-correction-no-cloning-theorem/
---

Akshunna S. Dogra highlights the current challenges in quantum computing, where despite significant investment and research, a practical and error-resistant quantum computer remains out of reach for now.

We are in the middle of what the journal Nature has called the “quantum gold rush”. Governments around the world are ramping up their investments in quantum computing. Venture capitalists are pouring billions of dollars into startups sprouting out of university departments. Established technology companies like IBM, Google, Microsoft, Intel, Amazon and Honeywell have recruited highly qualified teams to build quantum computers.

On the websites of these companies, you will find a dazzling array of offerings – ranging from software libraries for quantum computing to consulting services. Their slick marketing collaterals may lead you into thinking quantum computers are already commonplace and are routinely being used to solve problems in finance, transportation, materials science, energy and defence, etc.

But if you look beyond the shiny whitepapers and posters, you might be disappointed. For all their promises of the future, humankind still doesn’t have a working quantum computer that can solve problems of practical importance faster than your laptop can. The ones we have are barely more than lab prototypes, and the promises are erected on the speculative profits of billions of dollars in the future. These prospects aren’t yet real.

So when will we build a useful quantum computer?

Experts stand divided on this question. Some say it will take five years; many others estimate it will take decades. A vocal minority has argued we won’t have one anytime in the foreseeable future.

A classical computer operates with bits that take the value of either 0 or 1. Quantum bits, or qubits, on the other hand can exist simultaneously as both 0 and 1, much like Schröndinger’s cat can be both dead and alive. This property of being in two states at the same time is known as superposition. Quantum computers can leverage superposition to execute multiple computational paths simultaneously, giving them their incredible power.

But unlike classical bits, qubits are extremely fragile. The physical objects that represent classical bits are made up of semiconductors. You can drop them on a table and they would still work fine. But if you so much as bumped against a table on which there is a functional qubit, it will break. Qubits are even affected by seemingly insignificant disturbances like stray electromagnetic waves, vibrations, temperature fluctuations and possibly cosmic rays.

Such tremendous physical brittleness is not the effect of the materials a qubit is made of but because the effects of quantum mechanics are inordinately sensitive to external conditions.

Qubit entanglement

Qubits can maintain superposition only for infinitesimally small intervals of time. Even the slightest interaction with the environment causes a qubit to collapse into a discrete state of either 0 or 1. This is called decoherence. And even before they decohere, random noise caused by non-ideal circuit elements can corrupt the state of the qubits, leading to computing errors.

All computational systems, including classical computers, suffer from numerical errors. To handle errors in classical computers, scientists have developed error-correcting algorithms that rely on redundancy. That is, the computer represents each logical bit by multiple physical bits. If a small number of physical bits is corrupted due to noise, say, the remaining bits can still be used to detect and correct the error.

For example, the logical bit 1 is represented by three physical bits, 111. If one of the physical bits gets corrupted to yield 101, we can still infer the correct value of the logical bit to be 1.

The no-cloning theorem in quantum mechanics says that we can’t make perfect copies of a qubit’s state. This means we can’t directly use classical error-correcting algorithms for quantum computers.

To further complicate things, the act of measuring a qubit causes it to ‘collapse’ from a superposition of states to a single, discrete state. As a result, the error-correcting algorithm needs to detect and correct errors without interacting with the qubits.

Fortunately, although qubits can’t be copied, they can be entangled. When we entangle two qubits with each other, their individual quantum states fuse to form a single joint state. In this setup, if we measure one qubit from a pair of entangled qubits, our act of measurement will instantaneously affect the other qubit as well, and its state will change in a predictable way.

So by constructing a grid of entangled physical qubits to represent a single logical qubit, we can detect and correct quantum-computing errors. And the larger the grid, the more errors we can correct.

Also read: What Is a Quantum Computer?

Quantum computers need sophisticated electronic circuits to initialise qubits before beginning a computation; perform a variety of mathematical operations on them via quantum gates; and measure the results afterwards. These activities need to be performed with high precision at ultra-low temperatures while keeping the qubits strictly isolated from the environment throughout the process. But however hard we try, some unavoidable disturbances inevitably produce small errors.

If the rate of these errors exceeds a certain threshold, entangling multiple qubits only increases the noise in the system instead of reducing it. So for error correction to work, it is vitally important that we become able to control qubits with an error rate that is below this threshold. We have still not been able to do this.

The largest quantum computers we have today consist of fewer than 100 qubits. IBM announced earlier in September that it plans to build a 1,000-qubit quantum computer by 2023.

Computers perform mathematical operations on data. In order to solve a problem, a quantum computer needs enough qubits to represent the input and store the output – in addition to the qubits required to process intermediate results of the computation. Researchers estimate that a quantum computer will need between 1,000 to 100,000 logical qubits to solve computational problems encountered in practice.

And to keep errors in check, we will need to represent each logical qubit by 1,000 to 100,000 physical qubits – depending on how well we can control the qubits. All together, we will need a few million qubits to make quantum computers perform useful work that is also reliable.

From the point of view of quantum physics, a system with a million qubits is an enormously complex thing. Since qubits can exist in superpositions of two values at a time, a system of N qubits can encode 2^N states. A quantum computer with just 300 qubits will thus have more states than the total number of atoms in the entire universe.

Nobody has figured out exactly how we are going to control such large quantum systems while keeping errors in check. Small, focused groups are working on these challenges at universities and technology companies – but the rest of the community has largely ignored them. Computer science researchers are designing algorithms for quantum computers. Software companies are releasing platforms and libraries to implement these algorithms. Many members of both groups seem to have assumed that sufficiently large quantum computers will be available soon.

Quantum winter

By itself, this is not a problem. Many algorithms in computer science were also designed at a time when we didn’t have the hardware to run them. In physics, it is common for theoretical results to precede experimental confirmation by decades. Physicists predicted the existence of the Higgs boson in 1964; it was found at the Large Hadron Collider 48 years later.

The problem arises when the hype surrounding a technology fuels a misleading impression that the technology will be available shortly, and with certain abilities. Sensational headlines have been inflating our expectations of quantum computers, especially of their imminence. University students have been organising quantum hackathons. Network security companies are thinking of becoming ‘quantum-proof’.

More problematically, investors seeking short-term returns on their investments are pouring millions into machines that don’t yet exist. And large companies, out of fear of missing out on the action, are aggressively pitching quantum solutions. Amazon Web Services and Microsoft have respectively launched products called Braket and Azure Quantum, which purportedly allow developers to access quantum computers in the cloud. However, offerings like these are typically rudimentary circuits without any error-correction or classical algorithms that simulate qubits.

This situation is quite similar to the hype surrounding artificial intelligence in the 1960s. Encouraging results in machine translation and game-playing algorithms led researchers to believe that true artificial intelligence was almost ready. The New York Times reported in 1958, “The Navy revealed the embryo of an electronic computer today that it expects will be able to walk, talk, see, write, reproduce itself and be conscious of its existence.”

When the tall promises didn’t materialise, the hype gave way to disappointment. People who had been sold on tall promises became disillusioned. Investors lost faith in AI and funds dried up. A prolonged period of inactivity followed, known today as the ‘AI winter‘. Faster processing speeds and larger datasets eventually fulfilled some of these promises but only in the last decade – almost sixty years after they were first made. Many more promises remain unfulfilled.

As things stand, we are multiple breakthroughs away from building commercially viable quantum computers. Robust qubits that last longer without decohering will reduce the degree of redundancy required. Better control over qubits will allow us to implement more complex circuits. Better error-correction techniques will enable us to correct more errors using fewer qubits.
