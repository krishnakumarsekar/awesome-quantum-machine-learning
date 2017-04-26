# Awesome Quantum Machine Learning [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome quantum machine learning algorithms,study materials,libraries and software (by language).

## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [INTRODUCTION](#introduction)
    - [Why Quantum Machine Learning?](#introduction-why-quantum-machine-learning)
- [BASICS](#basics)
    - [What is Quantum Mechanics?](#basics-what-quantum-mechanics)
    - [What is Quantum Computing?](#basics-what-quantum-computing)
    - [What is Topological Quantum Computing?](#basics-what-topological-quantum-computing)
    - [Quantum Computing vs Classical Computing](#basics-quantum-classical-vs) 
- [QUANTUM COMPUTING](#quantumcomputing)
    - [Atom Structure](#quantumcomputing-atom-structure)
    - [Photon wave](#quantumcomputing-photon-wave)
    - [Electron Fluctuation or spin](#quantumcomputing-elecfluctuation-spin)
    - [States](#quantumcomputing-states)
    - [SuperPosition](#quantumcomputing-superposition)
    - [SuperPosition specific for machine learning(Quantum Walks)](#quantumcomputing-superpostion-machinelearning)
    - [Classical Bit](#quantumcomputing-classicalbit)
    - [Quantum Bit or Qubit or Qbit](#quantumcomputing-qubit)
    - [Basic Gates in Quantum Computing](#quantumcomputing-basicgates)
    - [Quantum Diode](#quantumcomputing-diode)
    - [Quantum Transistor](#quantumcomputing-transistor)
    - [Quantum Processor](#quantumcomputing-processor)
    - [Quantum Registery QRAM](#quantumcomputing-qram) 
    - [Quantum Entanglement](#quantumcomputing-entanglement)
- [QUANTUM COMPUTING MACHINE LEARNING BRIDGE](#qcmlbridge)
    - [Complex Numbers](#qcmlbridge-complexNumbers)
    - [Tensors](#qcmlbridge-tensors)
    - [Tensors Network](#qcmlbridge-tensors-network)             
    - [Oracle](#qcmlbridge-oracle)
    - [Hadamard transform](#qcmlbridge-hadamard)
    - [Hilbert Space](#qcmlbridge-hilbert)
    - [eigenvalues and eigenvectors](#qcmlbridge-eigen)
    - [Schr¨odinger Operators](#qcmlbridge-schrodinger)
    - [Quantum lambda calculus](#qcmlbridge-lamda)
    - [Quantum Amplitute Phase](#qcmlbridge-amp-phase)             
    - [convert classical bit to qubit](#qcmlbridge-classical-qubit)
    - [Quantum Dirac and Kets](#qcmlbridge-dirac-ket)
    - [Quantum Complexity](#qcmlbridge-complexity)
- [QUANTUM ALGORITHMS](#quantumalgorithms)
    - [Quantum Fourier Transform](#quantumalgorithms-fourier)
    - [Grovers Algorithm](#quantumalgorithms-grover)
    - [Shor's algorithm](#quantumalgorithms-shors)
    - [Hamiltonian Oracle Model](#quantumalgorithms-hamiltonian)
    - [Gradient Descent](#quantumalgorithms-gradient-descent)                 
    - [Phase Estimation](#quantumalgorithms-phase-estimation)
    - [Haar Tansform](#quantumalgorithms-haar)
    - [Quantum Ridgelet Transform](#quantumalgorithms-ridgelet)
- [QUANTUM MACHINE LEARNING ALGORITHMS](#quantumalgorithmsml)
    - [Quantum K-Nearest Neighbour](#quantumalgorithmsml-qknn)
    - [Quantum K-Means](#quantumalgorithmsml-kmeans)
    - [Quantum Fuzzy C-Means](#quantumalgorithmsml-qfcm)
    - [Quantum Support Vector Machine](#quantumalgorithmsml-svm)
    - [Quantum Genetic Algorithm](#quantumalgorithmsml-gn)
    - [Quantum Hidden Morkov Models](#quantumalgorithmsml-hmm)
    - [Quantum state classification with Bayesian methods](#quantumalgorithmsml-bayesian)
    - [Quantum Ant Colony Optimization](#quantumalgorithmsml-antcolony)
- [QAUNTUM NEURAL NETWORK](#qnn)
    - [Quantum perceptrons](#qnn-perceptron)
    - [QANN](#qnn-qann)
    - [QPN](#qnn-qpn)
    - [SAL](#qnn-sal)             
- [QUANTUM PROGRAMMING LANGUAGES , TOOLs and SOFTWARES](#qpl)
    - [ALL](#qpl-all)
- [QUANTUM ALGORITHMS SOURCE CODES , GITHUBS](#quantumsourcecode)
- [QUANTUM HOT TOPICS](#quantumhottopics)
    - [Quantum Cognition](#quantumhottopics-cognition)
    - [Quantum Camera](#quantumhottopics-camera)
    - [Quantum Mathematics](#quantumhottopics-mathematics)
    - [Quantum Information Processing](#quantumhottopics-informationprocessing)
    - [Quantum Image Processing](#quantumhottopics-imageprocessing)           
- [QUANTUM MEETUPS](#quantummeetups)
- [QUANTUM GOOGLE GROUPS](#quantumgroups)
- [QUANTUM BASED COMPANIES](#quantumcompanies)
- [QUANTUM LINKEDLIN](#quantumlinkedlin)
- [QUANTUM BASED DEGREES](#quantumdegrees)
- [CONSOLIDATED QUANTUM BOOKS](#quantumconsolidatedbooks)
- [CONSOLIDATED QUANTUM VIDEOS](#quantumconsolidatedvideos)

<!-- /MarkdownTOC -->

<a name="introduction"></a>
## INTRODUCTION

<a name="introduction-why-quantum-machine-learning"></a>
#### Why Quantum Machine Learning?
                 
##### Machine Learning(ML) is just a term in recent days but the work effort start from 18th century.

##### What is  Machine Learning ? , In Simple word the answer is making the computer or application to learn themselves . So its totally related with computing fields like computer science and IT ? ,The answer is not true . ML is a common platform which is mingled in all the aspects of the life from agriculture to mechanics . Computing is a key component to use ML easily and effectively . To be more clear ,Who is the mother of ML ?, As no option Mathematics is the mother of ML . The world tremendous invention complex numbers given birth to this field . Applying mathematics to the real life problem always gives a solution . From Neural Network to the complex DNA is running under some specific mathematical formulas and theorems.

##### As computing technology growing faster and faster mathematics entered into this field and makes the solution via computing to the real world . In the computing technology timeline once a certain achievements reached peoples interested to use advanced mathematical ideas such as complex numbers ,eigen etc and its the kick start for the ML field such as Artificial Neural Network ,DNA Computing etc.

##### Now the main question, why this field is getting boomed now a days ? , From the business perspective , 8-10 Years before during the kick start time for ML ,the big barrier is to merge mathematics into computing field . people knows well in computing has no idea on mathematics and research mathematician has no idea on what is computing . The education as well as the Job Opportunities is like that in that time . Even if a person tried to study both then the business value for making a product be not good.

##### Then the top product companies like Google ,IBM ,Microsoft decided to form a team with mathematician ,a physician and a computer science person to come up with various ideas in this field . Success of this team made some wonderful products and they started by providing cloud services using this product . Now we are in this [stage](https://cloud.google.com/vision/).

##### So what's next ? , As mathematics reached the level of time travel concepts but the computing is still running under classical mechanics . the companies understood, the computing field must have a change from classical to quantum, and they started working on the big Quantum computing field, and the market named this field as Quantum Information Science .The kick start is from Google and IBM with the Quantum Computing processor (D-Wave) for making Quantum Neural Network .The field of Quantum Computer Science and Quantum Information Science will do a big change in AI in the next 10 years. Waiting to see that........... .([google](https://research.google.com/pubs/QuantumAI.html), [ibm](http://research.ibm.com/ibm-q/)).

##### References
     
* [D-Wave](https://www.dwavesys.com/quantum-computing) - Owner of a quantum processor
* [Google](https://research.google.com/pubs/QuantumAI.html) - Quantum AI Lab
* [IBM](http://research.ibm.com/ibm-q/) - Quantum Computer Lab
* [Quora](https://www.quora.com/Is-quantum-computing-the-future-of-AI) - Question Regarding future of quantum AI
* [NASA](https://ti.arc.nasa.gov/tech/dash/physics/quail/) - NASA Quantum Works
* [Youtube](https://www.youtube.com/watch?v=CMdHDHEuOUE) - Google Video of a Quantum Processor
* [external-link](http://www.huffingtonpost.com/2013/07/29/quantum-computers-ai-artificial-intelligence-studies_n_3664011.html) - MIT Review
* [microsoft](https://www.microsoft.com/en-us/research/project/language-integrated-quantum-operations-liqui/) - Microsoft Quantum Related Works
* [Google2](https://research.googleblog.com/2009/12/machine-learning-with-quantum.html) - Google Quantum Machine Learning Blog
                                                
                                                
<a name="basics"></a>
## BASICS

<a name="basics-what-quantum-mechanics"></a>
#### What is Quantum Mechanics?
                 
##### In a single line study of an electron moved out of the atom then its classical mechanic ,vibrates inside the atom its quantum mechanics

* [WIKIPEDIA](https://en.wikipedia.org/wiki/Quantum_mechanics) - Basic History and outline
* [LIVESCIENCE](http://www.livescience.com/33816-quantum-mechanics-explanation.html). - A survey
* [YOUTUBE](https://www.youtube.com/watch?v=7u_UQG1La1o) - Simple Animation Video Explanining Great.

<a name="basics-what-quantum-computing"></a>
#### What is Quantum Computing?                 
                 
##### A way of parallel execution of multiple processess in a same time using qubit ,It reduces the computation time and size of the processor probably in neuro size 

* [WIKIPEDIA](https://en.wikipedia.org/wiki/Quantum_computing) - Basic History and outline
* [WEBOPEDIA](http://www.webopedia.com/TERM/Q/quantum_computing.html). - A survey
* [YOUTUBE](https://www.youtube.com/watch?v=g_IaVepNDT4) - Simple Animation Video Explanining Great.

<a name="basics-quantum-classical-vs"></a>
#### Quantum Computing vs Classical Computing
                 
* [LINK](http://www.thphys.nuim.ie/staff/joost/TQM/QvC.html) - Basic outline

                                                
<a name="quantumcomputing"></a>
## Quantum Computing

<a name="quantumcomputing-atom-structure"></a>
#### Atom Structure
                 
##### one line : Electron Orbiting around the nucleous in an eliptical format
 
* [YOUTUBE](https://www.youtube.com/watch?v=g_IaVepNDT4) - A nice animation video about the basic atom structure                   

[![atom](https://media.giphy.com/media/Tc1NorMBJTBXG/giphy.gif)](https://en.wikipedia.org/wiki/Atom)
                 
<a name="quantumcomputing-photon-wave"></a>
#### Photon Wave
                 
##### one line : Light nornmally called as wave transmitted as photons as similar as atoms in solid particles
                 
* [YOUTUBE](https://www.youtube.com/watch?v=fwXQjRBLwsQ) - A nice animation video about the basic photon 1                  
* [YOUTUBE](https://www.youtube.com/watch?v=KKr91v7yLcM) - A nice animation video about the basic photon 2
                 
[![Photon wave](https://www.wired.com/images_blogs/wiredscience/2013/07/photon1.jpg)](https://en.wikipedia.org/wiki/Photon)
                 
<a name="quantumcomputing-elecfluctuation-spin"></a>
#### Electron Fluctuation or spin
                 
##### one line : When a laser light collide with solid particles the electrons of the atom will get spin between the orbitary layers of the atom

[![Spin](http://www.tanmoydas.com/images/spinWave.gif)](https://en.wikipedia.org/wiki/Spin_(physics))
                 
* [YOUTUBE](https://www.youtube.com/watch?v=J3xLuZNKhlY) - A nice animation video about the basic Electron Spin 1                  
* [YOUTUBE](https://www.youtube.com/watch?v=3k5IWlVdMbo) - A nice animation video about the basic Electron Spin 2
* [YOUTUBE](https://www.youtube.com/watch?v=jvvkomcmyuo) - A nice animation video about the basic Electron Spin 3
                 
<a name="quantumcomputing-states"></a>
#### States
                 
##### one line : Put a point on the spinning electron ,if the point is in the top then state 1 and its in bottom state 0 

[![States](https://3c1703fe8d.site.internapcdn.net/newman/gfx/news/hires/2016/adeeplookint.jpg)](https://en.wikipedia.org/wiki/Quantum_state)
                 
* [YOUTUBE](https://www.youtube.com/watch?v=sICXOwOwS4E) - A nice animation video about the Quantum States
                 
<a name="quantumcomputing-superposition"></a>
#### SuperPosition
                 
##### two line : During the spin of the electron the point may be in the middle of upper and lower position, So an effective decision needs to take on the point location either 0 or 1 . Better option to analyse it along with other electrons using probability and is called superposition

[![SuperPosition](http://www.users.csbsju.edu/~frioux/superposition.GIF)](https://en.wikipedia.org/wiki/Quantum_superposition)
                 
* [YOUTUBE](https://www.youtube.com/watch?v=hkmoZ8e5Qn0) - A nice animation video about the Quantum Superposition

<a name="quantumcomputing-superpostion-machinelearning"></a>
#### SuperPosition specific for machine learning(Quantum Walks)
                 
##### one line : As due to computational complexity ,quantum computing only consider superposition between limited electrons ,In case to merge more than one set quantum walk be the idea

[![SuperPosition specific for machine learning](https://github.com/krishnakumarsekar/awesome-quantum-machine-learning/blob/master/Galtonboard4.theora.gif)](https://en.wikipedia.org/wiki/Quantum_walk)
                 
* [YOUTUBE](https://www.youtube.com/watch?v=86QsYPxoBow) - A nice video about the Quantum Walks
                                                                   
<a name="quantumcomputing-classicalbit"></a>
#### Classical Bits
                 
##### one line : If electron moved from one one atom to other ,from ground state to excited state a bit value 1 is used else bit value 0 used

[![Classical Bits](https://github.com/krishnakumarsekar/awesome-quantum-machine-learning/blob/master/InverseSpinHall.gif)](https://en.wikipedia.org/wiki/Bit)
                                                                   
<a name="quantumcomputing-qubit"></a>
#### Qubit
                 
##### one line : The superposition value of states of a set of electrons is Qubit 

[![Qubit](http://qoqms.phys.strath.ac.uk/figures/qubit.png)](https://en.wikipedia.org/wiki/Qubit)
                                                                   
* [YOUTUBE](https://www.youtube.com/watch?v=zNzzGgr2mhk) - A nice video about the Quantum Bits 1
* [YOUTUBE](https://www.youtube.com/watch?v=F8U1d2Hqark&t=179s) - A nice video about the Bits and Qubits 2
                                                                   
