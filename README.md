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
    - [Qubits Encode and Decode](#qcmlbridge-encode-decode)
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
    - [Quantum NP Problem](#quantumalgorithms-npproblem)
- [QUANTUM MACHINE LEARNING ALGORITHMS](#quantumalgorithmsml)
    - [Quantum K-Nearest Neighbour](#quantumalgorithmsml-qknn)
    - [Quantum K-Means](#quantumalgorithmsml-kmeans)
    - [Quantum Fuzzy C-Means](#quantumalgorithmsml-qfcm)
    - [Quantum Support Vector Machine](#quantumalgorithmsml-svm)
    - [Quantum Genetic Algorithm](#quantumalgorithmsml-genetic)
    - [Quantum Hidden Morkov Models](#quantumalgorithmsml-hmm)
    - [Quantum state classification with Bayesian methods](#quantumalgorithmsml-bayesian)
    - [Quantum Ant Colony Optimization](#quantumalgorithmsml-antcolony)
    - [Quantum Cellular Automata](#quantumalgorithmsml-caautomata)
    - [Quantum Classification using Principle Component Analysis](#quantumalgorithmsml-pca)
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
    - [Quantum Cryptography](#quantumhottopics-cryptography)
    - [Quantum Elastic Search](#quantumhottopics-elasticsearch)
    - [Quantum DNA Computing](#quantumhottopics-dna)
    - [Adiabetic Quantum Computing](#quantumhottopics-adiabetic)
    - [Topological Big Data Anlytics using Quantum](#quantumhottopics-topologicalbigdata)
- [QUANTUM MACHINE LEARNING VS DEEP LEARNING](#qmlvsdl)
- [QUANTUM MEETUPS](#quantummeetups)
- [QUANTUM GOOGLE GROUPS](#quantumgroups)
- [QUANTUM BASED COMPANIES](#quantumcompanies)
- [QUANTUM LINKEDLIN](#quantumlinkedlin)
- [QUANTUM BASED DEGREES](#quantumdegrees)
- [CONSOLIDATED QUANTUM ML BOOKS](#quantumconsolidatedbooks)
- [CONSOLIDATED QUANTUM ML VIDEOS](#quantumconsolidatedvideos)
- [CONSOLIDATED QUANTUM ML Reserach Papers](#quantumconsolidatedresearchpapers)
- [CONSOLIDATED QUANTUM ML Reserach Scientist](#quantumconsolidatedresearchscientist)
                                                                   

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
                                                                   
<a name="quantumcomputing-basicgates"></a>
#### Basic Gates in Quantum Computing
                 
##### one line : As like NOT, OR and AND , Basic Gates like NOT, Hadamard gate , SWAP, Phase shift etc can be made with quantum gates 

[![Basic Gates in Quantum Computing](http://www.mdpi.com/entropy/entropy-16-05290/article_deploy/html/images/entropy-16-05290f1-1024.png)](https://en.wikipedia.org/wiki/Quantum_gate)
                                                                   
* [YOUTUBE](https://www.youtube.com/watch?v=2Qsh_w2kq9Y) - A nice video about the Quantum Gates
                                                                   
<a name="quantumcomputing-diode"></a>
#### Quantum Diode
                 
##### one line : Quantum Diodes using a different idea from normal diode, A bunch of laser photons trigger the electron to spin and the quantum magnetic flux will capture the information  

[![Basic Gates in Quantum Computing](https://upload.wikimedia.org/wikipedia/en/thumb/4/42/Simple_qw_laser_diode.svg/1280px-Simple_qw_laser_diode.svg.png)](https://www.nature.com/articles/ncomms12978)
                                                                   
* [YOUTUBE](https://www.youtube.com/watch?v=doyK1olswX4) - A nice video about the Quantum Diode
                                                                   
<a name="quantumcomputing-transistor"></a>
#### Quantum Transistors
                 
##### one line : A transistor default have Source ,drain and gate ,Here source is photon wave ,drain is flux and gate is classical to quantum bits 

[![Quantum Transistors1](https://images.sciencedaily.com/2010/05/100514075106_1_900x600.jpg)](http://www.mpq.mpg.de/4987844/qip)
[![Quantum Transistors2](http://www.mpq.mpg.de/5016851/standard-1412932044.png)](https://en.wikipedia.org/wiki/Magnetic_flux_quantum)

                                                                                                                                    
* [QUORA](https://www.quora.com/What-is-the-equivalent-of-the-transistor-in-a-quantum-computer) -Discussion about the Quantum Transistor
* [YOUTUBE](https://www.youtube.com/watch?v=ZTxR2n2mvjc) - Well Explained
                                                                   
<a name="quantumcomputing-processor"></a>
#### Quantum Processor
                 
##### one line : A nano integration circuit performing the quantum gates operation sorrounded by cooling units to reduce the tremendous amount of heat 

[![Quantum Processor1](https://www.dwavesys.com/sites/default/files/cooling-082015%20copy.png)](https://www.dwavesys.com/tutorials/background-reading-series/introduction-d-wave-quantum-hardware#h2-0)
[![Quantum Processor2](https://www.photonics.com/images/Web/Articles/2014/6/5/Quantum_Circuit.png)](https://quantumexperience.ng.bluemix.net/qstage/?cm_mc_uid=36641337812614766932472&cm_mc_sid_50200000=1493295650#/user-guide)
[![Quantum Processor3](https://universe-review.ca/I13-13-superconductive.jpg)](https://www.cbinsights.com/blog/quantum-computing-corporations-list/)
                                                                                                                                    
* [YOUTUBE](https://www.youtube.com/watch?v=CMdHDHEuOUE) - Well Explained
                                                                   
<a name="quantumcomputing-qram"></a>
#### Quantum Registery QRAM
                 
##### one line : Comapring the normal ram ,its ultrafast and very small in size ,the address location can be access using qubits superposition value ,for a very large memory set coherent superposition(address of address) be used

[![QRAM1](https://ai2-s2-public.s3.amazonaws.com/figures/2016-11-08/94d487c6ef4d0fa5594eff352aac19e2bfd47ffa/2-Figure1-1.png)](https://arxiv.org/pdf/0708.1879.pdf)
[![QRAM2](https://github.com/krishnakumarsekar/awesome-quantum-machine-learning/blob/master/QRAM.png)](https://www.researchgate.net/publication/51394884_Quantum_Random_Access_Memory)
                                                                   
* [PDF](https://arxiv.org/pdf/0807.4994.pdf) - very Well Explained


<a name="qcmlbridge"></a>
## QUANTUM COMPUTING MACHINE LEARNING BRIDGE
                                                                   

<a name="qcmlbridge-complexNumbers"></a>
#### Complex Numbers
                 
##### one line : Normally Waves Interference is in n dimensional structure , to find a polynomial equation n order curves ,better option is complex number 

[![Complex Numbers1](http://www2.clarku.edu/~djoyce/complex/powers.gif)](https://en.wikipedia.org/wiki/Complex_number)
[![Complex Numbers2](http://theoryofeverything.org/MyToE/wp-content/uploads/2014/12/outChaos2.png)](https://www.mathsisfun.com/numbers/complex-numbers.html)
[![Complex Numbers3](http://www.mathwarehouse.com/algebra/complex-number/images/graphs/diagram-complex-plane.png)](https://en.wikipedia.org/wiki/Complex_number)
                                                                                                                                    
* [YOUTUBE](https://www.youtube.com/watch?v=T647CGsuOVU) - Wonderful Series very super Explained                                                                  

<a name="qcmlbridge-tensors"></a>
#### Tensors
                 
##### one line : Vectors have a direction in 2D vector space ,If on a n dimensional vector space ,vectors direction can be specify with the tensor ,The best solution to find the superposition of a n vector electrons spin space is representing vectors as tensors and doing tensor calculus

[![Tensors1](https://i.stack.imgur.com/5QsMD.png)](https://en.wikipedia.org/wiki/Tensor)
[![Tensors2](https://pbs.twimg.com/media/CK-LzV7VAAAdIC3.jpg)](https://www.quantiki.org/wiki/tensor-product)
[![Tensors3](https://inspirehep.net/record/1082123/files/Fig1.png)](https://en.wikipedia.org/wiki/Tensor_product)
[![Tensors4](https://inspirehep.net/record/1237922/files/fig1.png)](https://en.wikipedia.org/wiki/Tensor_product_of_Hilbert_spaces)
                                                                                                                                    
* [YOUTUBE](https://www.youtube.com/watch?v=f5liqUk0ZTw) - Wonderful super Explained tensors basics
* [YOUTUBE](https://www.youtube.com/watch?v=xzG6c96PsLs) - Quantum tensors basics                                                                  
                                                                   
<a name="qcmlbridge-tensors-network"></a>
#### Tensors Network
                 
##### one line : As like connecting multiple vectors ,multple tensors form a network ,solving such a network reduce the complexity of processing qubits

[![Tensors Network1](http://www.cse.unsw.edu.au/~billw/cs9444/tensor-stuff/tensor-intro-0418.gif)](https://arxiv.org/pdf/1306.2164.pdf)
[![Tensors Network2](http://www.quantuminfo.physik.rwth-aachen.de/global/show_picture.asp?id=aaaaaaaaaaiejix)](https://en.wikipedia.org/wiki/Tensor_network_theory)
[![Tensors Network3](https://inspirehep.net/record/1242488/files/gSymTN.png)](https://www2.warwick.ac.uk/fac/sci/physics/current/postgraduate/pglist/phrfbk/presentations/leeds14.pdf)
                                                                                                                                    
* [YOUTUBE](https://www.youtube.com/watch?v=bD-CWgbsCeI&list=PLgKuh-lKre10UQnP7gBCFoKgq5KWIA7el) - Tensors Network Some ideas specifically for quantum algorithms
                                                                   

<a name="quantumalgorithmsml"></a>
## QUANTUM MACHINE LEARNING ALGORITHMS
                                                                   

<a name="quantumalgorithmsml-qknn"></a>
#### Quantum K-Nearest Neighbour
                 
##### info : Here the centroid(euclidean distance) can be detected using the swap gates test between two states of the qubit , As KNN is regerssive loss can be tally using the average 
                                                                                                                                    
* [PDF1 from Microsoft](https://www.microsoft.com/en-us/research/publication/quantum-nearest-neighbor-algorithms-for-machine-learning/) - Theory Explanation
* [PDF2](https://arxiv.org/pdf/1409.3097.pdf) - A Good Material to understand the basics
* [Matlab](https://github.com/krishnakumarsekar/) - Yet to come soon
* [Python](https://github.com/krishnakumarsekar/) - Yet to come soon
                                                                   
<a name="quantumalgorithmsml-kmeans"></a>
#### Quantum K-Means
                 
##### info : Two Approaches possible ,1. FFT and iFFT to make an oracle and calculate the means of superposition 2. Adiobtic Hamiltonian generation and solve the hamiltonian to determine the cluster 
                                                                                                                                    
* [PDF1](https://pdfs.semanticscholar.org/6d77/54d33958b4a41d57ec99558eb28ae88f9884.pdf) - Applying Quantum Kmeans on Images in a nice way
* [PDF2](http://www.machinelearning.org/proceedings/icml2007/papers/518.pdf) - Theory
* [PDF3](https://arxiv.org/pdf/1307.0411.pdf) - Explaining well the K-means clustering using hamiltonian 
* [Matlab](https://github.com/krishnakumarsekar/) - Yet to come soon
* [Python](https://github.com/krishnakumarsekar/) - Yet to come soon
                                                                   
<a name="quantumalgorithmsml-qfcm"></a>
#### Quantum Fuzzy C-Means
                 
##### info : As similar to kmeans fcm also using the oracle dialect ,but instead of means,here oracle optimization followed by a rotation gate is giving a good result
                                                                                                                                    
* [PDF1](https://pdfs.semanticscholar.org/6d77/54d33958b4a41d57ec99558eb28ae88f9884.pdf) - Theory
* [Matlab](https://github.com/krishnakumarsekar/) - Yet to come soon
* [Python](https://github.com/krishnakumarsekar/) - Yet to come soon
                                                                   
<a name="quantumalgorithmsml-svm"></a>
#### Quantum Support Vector Machine
                 
##### info : A little different from above as here kernel preparation is via classical and the whole training be in oracles and oracle will do the classification, As SVM is linear ,An optimal Error(Optimum of the Least Squares Dual Formulation) Based regression is needed to improve the performance
                                                                                                                                    
* [PDF1](https://arxiv.org/pdf/1307.0471.pdf) - Nice Explanation but little hard to understand :)
* [PDF2](http://www.scirp.org/journal/PaperInformation.aspx?paperID=72542) - Nice Application of QSVM
* [Matlab](https://github.com/krishnakumarsekar/) - Yet to come soon
* [Python](https://github.com/krishnakumarsekar/) - Yet to come soon
                                                                   
<a name="quantumalgorithmsml-genetic"></a>
#### Quantum Genetic Algorithm
                 
##### info : One of the best algorithm suited for Quantum Field ,Here the chromosomes act as qubit vectors ,the crossover part carrying by an evaluation and the mutation part carrying by the rotation of gates
  
[![Flow Chart](https://www.hindawi.com/journals/mpe/2013/730749.fig.001.jpg)]()                                                                   

* [PDF1](https://www.hindawi.com/journals/mpe/2013/730749/) - Very Beautiful Article , well explained and superp                                                                 
* [PDF2](https://arxiv.org/pdf/1202.2026.pdf) - A big theory :)
* [PDF3](http://ccis2k.org/iajit/PDF/vol.9,no.3/2107-6.pdf) - Super Comparison
* [Matlab](http://www.codelooker.com/id/155/717734.html) - Simulation
* [Python1](https://github.com/ResearchCodesHub/QuantumGeneticAlgorithms/) - Simulation
* [Python2](https://github.com/krishnakumarsekar/) - Yet to come
                                                                   
<a name="quantumalgorithmsml-hmm"></a>
#### Quantum Hidden Morkov Models
                 
##### info : As HMM is already state based ,Here the quantum states acts as normal for the markov chain and the shift between states is using quantum operation based on probability distribution 
  
[![Flow Chart](https://github.com/krishnakumarsekar/awesome-quantum-machine-learning/blob/master/quantum%20HMM.png)]()                                                                   

* [PDF1](https://arxiv.org/pdf/1503.08760.pdf) - Nice idea and explanation                                                              
* [PDF2](https://arxiv.org/pdf/1207.4304.pdf) - Nice but a different concept little
* [Matlab](https://github.com/krishnakumarsekar/) - Yet to come
* [Python1](https://github.com/krishnakumarsekar/) - Yet to come
* [Python2](https://github.com/krishnakumarsekar/) - Yet to come
                                                                   
<a name="quantumalgorithmsml-bayesian"></a>
#### Quantum state classification with Bayesian methods
                 
##### info : Quantum Bayesian Network having the same states concept using quantum states,But here the states classification to make the training data as reusable is based on the density of the states(Interference) 
  
[![Bayesian Network Sample1](https://image.slidesharecdn.com/sweden-150720134538-lva1-app6892/95/quantumlike-bayesian-networks-using-feynmans-path-diagram-rules-13-638.jpg?cb=1437400046)]()                                                                   
[![Bayesian Network Sample2](https://image.slidesharecdn.com/sml-150512222733-lva1-app6891/95/quantum-models-for-decision-and-cognition-83-638.jpg?cb=1431469807)]()                                                                   
[![Bayesian Network Sample3](http://ars.els-cdn.com/content/image/1-s2.0-S1568494614004499-fx1.jpg)]()                                                                   
                                                                   
* [PDF1](https://arxiv.org/pdf/1204.1550.pdf) - Good Theory                                                              
* [PDF2](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4726808/) - Good Explanation
* [Matlab](https://github.com/krishnakumarsekar/) - Yet to come
* [Python1](https://github.com/krishnakumarsekar/) - Yet to come
* [Python2](https://github.com/krishnakumarsekar/) - Yet to come
                                                                   
<a name="quantumalgorithmsml-antcolony"></a>
#### Quantum Ant Colony Optimization
                 
##### info : A good algorithm to process multi dimensional equations, ACO is best suited for Sales man issue , QACO is best suited for Sales man in three or more dimension, Here the quantum rotation circuit is doing the peromene update and qubits based colony communicating all around the colony in complex space
  
[![Ant Colony Optimization 1](https://agatakycia.files.wordpress.com/2013/06/minimalpathmodule1.jpg)]()                                                                   
                                                                   
* [PDF1](http://ac.els-cdn.com/S2212667812001359/1-s2.0-S2212667812001359-main.pdf?_tid=42e0cd66-2f4a-11e7-920f-00000aacb361&acdnat=1493738345_8f536599e404c7588811ddd49c484688) - Good Concept                                                              
* [PDF2](http://www.sersc.org/journals/IJMUE/vol10_no11_2015/19.pdf) - Good Application
* [Matlab](https://github.com/krishnakumarsekar/) - Yet to come
* [Python1](https://github.com/krishnakumarsekar/) - Yet to come
* [Python2](https://github.com/krishnakumarsekar/) - Yet to come
                                                                   
<a name="quantumalgorithmsml-caautomata"></a>
#### Quantum Cellular Automata
                 
##### info : One of the very complex algorithm with various types specifically used for polynomial equations and to design the optimistic gates for a problem, Here the lattice is formed using the quatum states and time calculation is based on the change of the state between two qubits ,Best suited for nano electronics
  
[![Quantum Cellular Automata](https://github.com/krishnakumarsekar/awesome-quantum-machine-learning/blob/master/ta2-color_orig%20b.jpg)]()                                                                   
                                                                   
* [Wikipedia](https://en.wikipedia.org/wiki/Quantum_cellular_automaton) - Basic                                                              
* [PDF1](https://arxiv.org/pdf/0808.0679.pdf) - Just to get the keywords
* [PDF2](http://ieee-hpec.org/2013/index_htm_files/7-Improved-Eigensolver-Baldwin-2867489.pdf) - Nice Explanation and an easily understandable application                                                                   
* [Matlab](https://github.com/krishnakumarsekar/) - Yet to come
* [Python1](https://github.com/krishnakumarsekar/) - Yet to come
* [Python2](https://github.com/krishnakumarsekar/) - Yet to come
                                                                   
<a name="qpl"></a>
## QUANTUM PROGRAMMING LANGUAGES , TOOLs and SOFTWARES
                                                                   

<a name="qpl-all"></a>
#### All
                 
##### info : All Programming languages ,softwares and tools in alphabetical order 
                                                                                                                                    
* [Software](https://www.quantiki.org/wiki/list-qc-simulators) - Nice content of all
* [Python library](http://qutip.org/) - A python library
* [Matlab based python library](https://pypi.python.org/pypi/qit) - Matlab Python Library
* [Quantum Tensor Network Github](https://github.com/emstoudenmire/TNML) - Tensor Network 
* [Quantum Tensorflow](https://github.com/krishnakumarsekar/) - Yet to come soon
* [Quantum Spark](https://github.com/krishnakumarsekar/) - Yet to come soon
* [Quatum Map Reduce](https://github.com/krishnakumarsekar/) - Yet to come soon
* [Quantum Database](https://github.com/krishnakumarsekar/) - Yet to come soon
* [Quantum Server](https://github.com/krishnakumarsekar/) - Yet to come soon
* [Quantum Data Analytics](https://github.com/krishnakumarsekar/) - Yet to come soon
                                                                   
<a name="qmlvsdl"></a>
## Quantum Machine Learning vs Deep Learning
                                                                                    
##### Its fun to discuss about this , In recent days most of the employees from Product Based Companies Like google,microsoft etc using the word deep learning ,What actually Deep Learning ? and is it a new inventions ? how to learn this ? Is it replacing machine learning ? these question come to the mind of junior research scholars and mid level employees
                 
##### The one answer to all questions is deep learning = parallel "for" loops ,No more than that ,Its an effective way of executing multiple tasks repeatly and to reduce the computation cost, But it introduce a big cap between mathematics and computerscience , How ?  

##### All classical algorithms based on serial processing ,Its depends on the feedback of the first loop ,On applying a serial classical algorithm in multiple clusters wont give a good result ,but some light weight parallel classical algorithms(Deep learning) doing the job in multiple clusters and its not suitable for complex problems, What is the solution for then? 

##### As in the title Quantum Machine Learning ,The advantage behind is deep learning is doing the batch processing simply on the data ,but quantum machine learning designed to do batch processing as per the algorithm

##### The product companies realised this one and they started migrating to quantum machine learning and executing the classical algorithms on quantum concept gives better result than deep learning algorithms on classical computer and the target to merge both to give very wonderful result 

##### References
     
* [Quora](https://www.quora.com/How-will-quantum-computing-revolutionize-deep-learning) - Good Discussion
* [Quora](https://www.quora.com/Will-quantum-computing-change-machine-learning) - The Bridge Discussion
* [Pdf](http://www.scottaaronson.com/papers/qml.pdf) - Nice Discussion
* [Google](https://venturebeat.com/2015/11/11/google-researcher-quantum-computers-arent-perfect-for-deep-learning/) - Google Research Discussion
* [Microsoft](http://www.physics.usyd.edu.au/quantum/Coogee2015/Presentations/Svore.pdf) - Microsoft plan to merge both
* [IBM](https://www.rtinsights.com/ibm-quantum-computing-with-machine-learning-in-cloud/) - IBM plan to merge both
* [IBM Project](https://www.ibm.com/blogs/research/2017/03/quantum-algorithm-classifies-9500-handwritten-numbers/) - IBM Project idea
* [MIT and Google](https://www.technologyreview.com/s/544421/googles-quantum-dream-machine/) - Solutions for all questions

<a name="quantumdegrees"></a>
## QUANTUM BASED DEGREES

##### Plenty of courses around the world and many Universities Launching it day by day ,Instead of covering only Quantum ML , Covering all Quantum Related topics gives more idea in the order below
                                                                   
#### Available Courses

###### Quantum Mechanics for Science and Engineers

* Online
                                                                   
	* [Standford university](http://online.stanford.edu/course/qmse01-quantum-mechanics-scientists-and-engineers) - Nice Preparatory Course
	* [edx](https://courses.edx.org/courses/course-v1:GeorgetownX+PHYX-008-01x+1T2017/info) - Quantum Mechanics for Everyone
    * [NPTEL 1](http://nptel.ac.in/courses/115104096/) - Nice Series of Courses to understand basics and backbone of quantum mechanics
    * [NPTEL 2](http://nptel.ac.in/courses/115102023/)
    * [NPTEL 3](http://nptel.ac.in/courses/115106066/)
    * [NPTEL 4](http://nptel.ac.in/courses/115108074/)
   	* [NPTEL 5](http://nptel.ac.in/courses/115101010/)
                                                                   
* Class Based Course
                                                                   
	* UK

		* [Bristol](http://www.bristol.ac.uk/maths/study/undergraduate/units1617/levelh6units/quantum-mechanics-math35500/)
                                                                   
	* Australia
                                                                   
		* [Australian National University](http://programsandcourses.anu.edu.au/course/PHYS2013)
                                                                   
	* Europe
                                                                   
		* [Maxs Planks University](http://programsandcourses.anu.edu.au/course/PHYS2013)
                                                                   
###### Quantum Physics
                                                                   
* Online

	* [MIT](https://ocw.mit.edu/courses/physics/8-04-quantum-physics-i-spring-2013/lecture-videos/) - Super Explanation and well basics
    * [NPTEL](http://nptel.ac.in/courses/122106034/) - Nice Series of Courses to understand basics and backbone of quantum Physics

* Class Based Course
                                                                   
	* Europe

		* [University of Copenhagen](http://www.nbi.ku.dk/english/research/quantum-physics/)
                                                                   
###### Quantum Chemistry

* Online

    * [NPTEL 1](http://nptel.ac.in/courses/104108057/) - Nice Series of Courses to understand basics and backbone of quantum Chemistry
    * [NPTEL 2](http://nptel.ac.in/courses/104106083/) - 

* Class Based Course
                                                                   
	* Europe

		* [UGent Belgium](http://www.quantum.ugent.be/)
                                                                   
###### Quantum Computing

* Online

	* [MIT](https://ocw.mit.edu/courses/mathematics/18-435j-quantum-computation-fall-2003/index.htm) - Super Explanation and well basics
	* [edx](https://www.edx.org/course/quantum-mechanics-quantum-computation-uc-berkeleyx-cs-191x) - Nice Explanation
    * [NPTEL](http://nptel.ac.in/courses/104104082/) - Nice Series of Courses to understand basics and backbone of quantum Computing

* Class Based Course
                                                                   
	* Canada
                                                                   
		* [uwaterloo](https://uwaterloo.ca/institute-for-quantum-computing/)

	* Singapore
                                                                   
		* [National University Singapore](http://www.quantumlah.org/)

	* USA
                                                                   
		* [Berkley](http://www.quantumlah.org/)
                                                                                                                                                                                                         
###### Quantum Technology

* Class Based Course
                                                                   
	* Canada
                                                                   
		* [uwaterloo](https://uwaterloo.ca/institute-for-quantum-computing/)

	* Singapore
                                                                   
		* [National University Singapore](http://www.quantumlah.org/)

	* Europe
                                                                   
		* [Munich](http://www.munich-quantum-center.de/index.php?id=1)
                                                                   
                                                                   
###### Quantum Information Science

* External Links

	* [quantwiki](https://www.quantiki.org/wiki/courses-quantum-information-science)
                                                                   
* Online

	* [MIT](https://ocw.mit.edu/courses/media-arts-and-sciences/mas-865j-quantum-information-science-spring-2006/) - Super Explanation and well basics
	* [edx](https://www.edx.org/course/quantum-information-science-ii-mitx-8-371x) - Nice Explanation
    * [NPTEL](http://nptel.ac.in/courses/115101092/) - Nice Series of Courses to understand basics and backbone of quantum information and computing

* Class Based Course
                                                                   
	* USA
                                                                   
		* [MIT](http://qis.mit.edu/)
		* [Standford University](https://web.stanford.edu/group/yamamotogroup/)
                                                                   
	* Canada
                                                                   
		* [Perimeter Institute](https://perimeterinstitute.ca/research/research-areas/quantum-information)

	* Singapore
                                                                   
		* [National University Singapore](http://www.quantumlah.org/)

	* Europe
                                                                   
		* [ULB Belgium](http://quic.ulb.ac.be/teaching)
                                                                   
                                                                                                                                      
###### Quantum Electronics
                                                                   
* Online

    * [MIT](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-974-fundamentals-of-photonics-quantum-electronics-spring-2006/) - Wonderful Course
    * [NPTEL](http://nptel.ac.in/courses/115102022/) - Nice Series of Courses to understand basics and backbone of quantum Electronics

* Class Based Course
                                                                                                                                      
    * USA
                                                                   
		* [Texas](http://www.ece.utexas.edu/research/areas/plasma-quantum-electronics-and-optics)                                                               
    
	* Europe
                                                                   
		* [Zurich](http://www.iqe.phys.ethz.ch/utils/contact.html)                                                               
                                                                   
	* Asia
                                                                   
		* [Tata Institute](http://www.tifr.res.in/~quantro/index.html)
                                                                   
###### Quantum Field Theory

* Online
                                                                   
	* [Standford university](https://ocw.mit.edu/courses/physics/8-323-relativistic-quantum-field-theory-i-spring-2008/) - Nice Preparatory Course
    * [edx](https://www.edx.org/course/effective-field-theory-mitx-8-eftx) - Some QFT Concepts available
                                                                   
* Class Based Course
                                                                   
	* UK

		* [Imperial](http://www.imperial.ac.uk/theoretical-physics/postgraduate-study/msc-in-quantum-fields-and-fundamental-forces/)
                                                                                                                                      
	* Europe
                                                                   
		* [Vrije](http://www.vub.ac.be/en/study/fiches/56659/quantum-field-theory)
                                                                 
###### Quantum Computer Science
                                                                   
* Class Based Course
                                                                   
	* USA

		* [Oxford](https://www.cs.ox.ac.uk/teaching/courses/quantum/)
                                                                   
###### Quantum Artificial Intelligence and Machine Learning

* External Links

	* [Quora 1](https://www.quora.com/Quantum-Computing-vs-Artificial-Intelligence-for-a-PhD)
    * [Quora 1](https://www.quora.com/Where-can-you-get-a-PhD-in-quantum-machine-learning)
                                                                                                                                                                                                                                                                           	                                                                                                                 
### License

[![License](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://github.com/krishnakumarsekar/awesome-quantum-machine-learning/blob/master/LICENCE)

### Dedicated Opensources

[![Dedicated Opensources](http://livingintown.com/wp-content/uploads/sites/1112/2015/03/coming-soon-small.jpg)]()
                                                                  
* Source code of plenty of Algortihms in Image Processing , Data Mining ,etc in Matlab, Python ,Java and VC++ Scripts
* Good Explanations of Plenty of algorithms with flow chart etc
* Comparison Matrix of plenty of algorithms

### Contribution

<a href="https://github.com/krishnakumarsekar/awesome-quantum-machine-learning/blob/master/contribution.md"><img src="http://comps.canstockphoto.com/can-stock-photo_csp23653568.jpg" align="left" height="200" width="200"></a>
