---
title: Learning & Dynamics 2024-2025
permalink: /learning2425/
---

<img style='float:left;position: relative; margin-right: 10px; ' height='200' src='/images/learning/learning.jpg'> 

## Learning & Dynamics Seminars
<br>


Together with our FEMTO colleagues [Prof. John Dudley](https://www.femto-st.fr/en/femto-people/johndudley), Professor of Optical Physics, [Dr Rafael Teloli](https://www.femto-st.fr/fr/personnel-femto/rafaelteloli), Assistant Prof. in Mechanical Engineering and [Dr Manaoj Aravind](https://man-aravind.github.io/), the [FEMTO Neuro group](https://neuro-team-femto.github.io/) is putting together a monthly series of invited seminars on the topic of machine learning for dynamical systems. 

The "Learning & Dynamics" Seminar Series wishes to address - roughly defined - *how one may analyse & discover physically-interpretable models of dynamical systems on the basis of observed temporal data, rather than attempt to study them in a purely analytical manner*. Our seminar aims to address interdisciplinary applications across complex physical or physiological systems, such as neuroscience, non-linear optics or fluid mechanics.

For our inaugural 2024-2025 series, we have assembled a program with a fantastic list of early-career EU researchers who have made recent notable contributions to this emerging field. As a kick-off event on Tuesday 17th 2024, we are also honored to host an invited talk by [Prof. J. Nathan Kutz](http://faculty.washington.edu/kutz/), Director of the NSF [AI Institute in Dynamic Systems](https://dynamicsai.org/) at the University of Washington, USA. Title, abtracts and speaker bios come below.  

### 2024-2025 Program
<br>

|------|------|-------| 
| Date | Hour | Speaker | Title | Location |
|------|------|-------| 
| <span style="color:red">Tue.</span> Sept 17, 2024 (<span style="color:red">Note unusual day</span>)| 2pm | [Prof. J. Nathan Kutz](http://faculty.washington.edu/kutz/) (Dept. Applied Mathematics, University of Washington) | Modern Sensing and Learning with Machine Learning | Amphi JJ. Gagnepain |
| Thu. Oct 17, 2024 | 2pm | [Dr Nicolas Boullé](https://nboulle.github.io/) (Dept. Applied Mathematics, Imperial College London) | An overview of operator learning | Amphi J. Haag |
| Thu. Nov 21, 2024 | 2pm | [Dr Lou Zonca](https://lou-zonca.webflow.io/) (Center for Brain & Cognition, University Pompeu Fabra, Barcelona) | Modeling disorders of consciousness at the patient level reveals the network's influence on the diagnosis vs the local node parameters role in prognosis | Amphi JJ. Gagnepain |
| <del>Thu. Dec 19, 2024</del>del> | <del>2pm</del> | <span style="color:red">Cancelled </span> <del> [Dr Emmanuel De Bezenac](https://scholar.google.fr/citations?user=KvZw5gYAAAAJ&hl=en) (Dept of Mathematics, UTH Zurich)</del> | <del>tba</del> | <del>Amphi J. Haag</del> |
| Wed. Jan 15 + Thu. Jan 16, 2025 | 9:45-17:00 | Satellite workshop ([program & free registration](https://sites.google.com/unipv.it/sciml-errorcontrolanalysis)) | Scientific Machine Learning: error control and analysis | [Laboratoire de Mathématiques de Besançon](https://lmb.univ-fcomte.fr/acces/) | 
| Thu. Feb 20, 2025 | 2pm | [Dr Karim Cherifi](https://scholar.google.com/citations?user=gE5RRyEAAAAJ&hl=en) (Centre for Industry and Science, TU Berlin) | Learning and data-driven modeling of port-Hamiltonian systems | Amphi J. Haag |
| Thu. Mar 20, 2025 | 2pm | [Dr Zahra Monfared](https://scholar.google.pl/citations?user=OPUIwIoAAAAJ&hl=en) (Interdisciplinary Center for Scientific Computing, Heidelberg University) | Learning dynamics with RNNs: from training difficulties to gradient-free solutions | Amphi JJ Gagnepain |
| Thu. Apr 17, 2025 | 2pm | [Dr Richard Gao](http://www.rdgao.com/) (Tübingen AI Center, University of Tübingen) | Accelerating discovery of data-driven models and theories of neural dynamics | Amphi J. Haag |


#### Time & Place

L&D seminars are held in-person, monthly (typically the 3rd Thursday of the month, 2pm), and alternate every other month between 2 locations in the FEMTO premises in Besançon, France (Amphithéatre *Jean-Jacques Gagnepain*, [FEMTO TEMIS Building, 15B avenue des Montboucons](https://maps.app.goo.gl/zt9eBHZ1CmZDoJnB6) & Amphithéatre *Jules Haag*, [FEMTO SUPMICROTECH Building, 26 rue de l'Epitaphe](https://maps.app.goo.gl/GuZa8Ztsu8GmXg1y7)). 

Attendance is free, in the limit of available seats (no reservation taken). For non-FEMTO personnel, please be prepared to identify yourself with a mandatory ID document at the entrance counter in each location. 

*Information, contact:* [JJ Aucouturier](https://www.femto-st.fr/fr/personnel-femto/jeanaucouturier), FEMTO Neuro Group

### Title and abstracts
<br>

#### Inaugural Seminar: Tue. Sept. 17th, 2024 

<img style='float:left;position: relative; margin-right: 10px; ' height='200' src='/images/learning/nathan_kutz.jpg'>  

**Speaker:** Prof. Nathan Kutz, University of Washington

**Title:** Modern Sensing and Learning with Machine Learning

**Abstract:** Sensing is a universal task in science and engineering. Downstream tasks from sensing include learning dynamical models, inferring full state estimates of a system (system identification), control decisions, and forecasting. These tasks are exceptionally challenging to achieve with limited sensors, noisy measurements, and corrupt or missing data. Existing techniques typically use current (static) sensor measurements to perform such tasks and require principled sensor placement or an abundance of randomly placed sensors. In contrast, we propose a SHallow REcurrent Decoder (SHRED) neural network structure which incorporates (i) a recurrent neural network (LSTM) to learn a latent representation of the temporal dynamics of the sensors, and (ii) a shallow decoder that learns a mapping between this latent representation and the high-dimensional state space. By explicitly accounting for the time-history, or trajectory, of the sensor measurements, SHRED enables accurate reconstructions with far fewer sensors, outperforms existing techniques when more measurements are available, and is agnostic towards sensor placement. In addition, a compressed representation of the high-dimensional state is directly obtained from sensor measurements, which provides an on-the-fly compression for modeling physical and engineering systems. Forecasting is also achieved from the sensor time-series data alone, producing an efficient paradigm for predicting temporal evolution with an exceptionally limited number of sensors.

**Bio:**  Nathan Kutz is the Yasuko Endo and Robert Bolles Professor of Applied Mathematics and Electrical and Computer Engineering and Director of the AI Institute in Dynamic Systems at the University of Washington, having served as chair of applied mathematics from 2007-2015.  He received the BS degree in physics and mathematics from the University of Washington in 1990 and the Phd in applied mathematics from Northwestern University in 1994.  He was a postdoc in the applied and computational mathematics program at Princeton University before taking his faculty position.  He has a wide range of interests, including neuroscience to fluid dynamics where he integrates machine learning with dynamical systems and control. 

**Web:**  [http://faculty.washington.edu/kutz/](http://faculty.washington.edu/kutz/)

<br>

#### October Seminar: Thur. Oct. 17th, 2024 

<img style='float:left;position: relative; margin-right: 10px; ' height='200' src='/images/learning/nicolas_boulle.jpg'>  

**Speaker:** Dr. Nicolas Boullé, Imperial College London

**Title:** An overview of operator learning

**Abstract:** Operator learning is an emerging field at the intersection of machine learning, physics, and mathematics, that aims to discover properties of unknown physical systems from experimental data. Popular techniques exploit the approximation power of deep learning to learn solution operators, which map source terms to solutions of the underlying PDE. Solution operators can then produce surrogate data for data-intensive machine learning approaches such as learning reduced order models for design optimization in engineering and PDE recovery. In this talk, we will provide a brief overview of the growing field of operator learning and see how numerical linear algebra algorithms, such as the randomized singular value decomposition, can be exploited to gain theoretical and mechanistic understanding of operator learning architectures.

**Bio:**  Nicolas Boullé is an Assistant Professor in Applied Mathematics at Imperial College London. He obtained a PhD in numerical analysis at the University of Oxford in 2022 and was a postdoc at the University of Cambridge from 2022-2024. His research focuses on the intersection between numerical analysis and deep learning, with a specific emphasis on learning physical models from data, particularly in the context of partial differential equations learning. He was awarded a Leslie Fox Prize in 2021 and a SIAM Best Paper Prize in Linear Algebra in 2024 for his work on operator learning .

**Web:**  [https://nboulle.github.io](https://nboulle.github.io/)

#### November Seminar: Thur. Nov. 21st, 2024 

<img style='float:left;position: relative; margin-right: 10px; ' height='200' src='/images/learning/lou_zonca.jpg'>  

**Speaker:** Dr. Lou Zonca, Pompeu Fabra University (Barcelona),

**Title:** Modeling disorders of consciousness at the patient level reveals the network's influence on the diagnosis vs the local node parameters role in prognosis

**Abstract:** Disorders of Consciousness (DoC) regroup a wide spectrum of conditions ranging from coma to more aware (awake) states of consciousness but for patients which remain largely unable to communicate. Although there are universal clinical procedures, to assess the level of consciousness of a DoC patient, precise diagnosis and prognosis remains a challenge. In this talk, I will discuss my current work regarding the development of DoC mathematical models calibrated at the single-patient level. The ultimate goal is to use these models as digital twins to propose better biomarkers, enhance prognosis, and test potential therapeutic approaches using numerical simulations.
I will present my latest results regarding the construction of a modeling pipeline that takes DoC patients' fMRI resting state data as an input and provides automatically fitted mathematical models for each patient. The pipeline is decomposed as follows: first, the data is first projected, using Auto-Encoders, into a latent-space of optimal reduced dimension that I will describe. Second, in this latent-space, I implement an automatic parameter fitting procedure that can be applied to different mathematical models. I will present and describe two models: (1) the Hopf model, which can be seen as a network of noisy oscillators, which is known to provide good results for fMRI modeling but whose biological interpretation is limited. (2) A new model that indirectly accounts for the regulatory role of astrocytes (a type of glial cells) on neuronal activity: the main advantage of this model, despite its higher complexity, is its more straightforward biological interpretation.  Finally, the fitted parameters of the models provide us with two types of biomarkers: (1) The connectivity matrices, revealing the network interactions at the global brain scale, tend to give us information regarding the diagnosis of the patients, i.e. the severity of their condition. (2) On the other hand, the local node parameters tend to correlate to other relevant clinical information such as age, etiology and prognosis. 

**Bio:**  Lou Zonca is an applied mathematician working in computational neuroscience. Her work combines theoretical mathematics (non-linear dynamical systems, stochastic processes), development of mathematical models and algorithms, numerical simulations (in Matlab and Python), computational and machine learning tools (auto-encoders, classification algorithms) to study concrete applications in neurosciences at different scales with a particular focus on neuron-glia interactions from molecular to population level and up to whole-brain dynamics. She is currently a postdoctoral researcher at the Center for Brain and Cognition (CBC) at Pompeu Fabra University (UPF) in Barcelona, where she develops whole-brain models to study Disorders of Consciousness (DoC) with Prof. G. Deco. In particular, her goal is to propose individually calibrated models to propose novel markers aiming to capture the heterogeneity of the DoC patients, in order to help diagnosis/prognosis and to investigate therapeutic approaches. During her PhD, in Ecole Normale Supérieure in Paris, she developed new models accounting for astrocyte regulation of neuronal bursting that allowed us to decipher and predict the mechanisms underlying such regulation. She further studied these models mathematically, which led to the description of a new type of escape process for stochastic trajectories trapped in a basin of attraction, for a class of nonlinear stochastic dynamical systems.

**Web:**  [https://lou-zonca.webflow.io](https://lou-zonca.webflow.io)

#### January satellite workshop: Jan 15th - 16th, 2025

<img style='float:left;position: relative; margin-right: 10px; ' height='200' src='/images/learning/workshop.jpg'>  Our colleagues [Geneviève Dusson](https://gdusson.perso.math.cnrs.fr/) (CNRS, Université de Franche-Comté Besançon) & [Carlo Marcati](https://mate.unipv.it/marcati/) (Università di Pavia) are organizing a 2-day internation workshop on Scientific Machine Learning. Topics include neural networks and neural operators for PDEs, nonlinear reduced order modeling, low-rank approximation, operator learning and interactions between model order reduction and SciML. 

The workshop will be held at the Laboratoire de Mathématiques de Besançon ([access map](https://lmb.univ-fcomte.fr/acces/)).

Program and link for (mandatory) free registration: [https://sites.google.com/unipv.it/sciml-errorcontrolanalysis](https://sites.google.com/unipv.it/sciml-errorcontrolanalysis)


#### February Seminar: Thu. Feb 20, 2025

<img style='float:left;position: relative; margin-right: 10px; ' height='200' src='/images/learning/karim_cherifi.jpg'>  

**Speaker:** Dr. Karim Cherifi, University of Wuppertal (Germany).

**Title:** Learning and data-driven modeling of port-Hamiltonian systems

**Abstract:** Port-Hamiltonian systems have received a lot of attention in recent years because of their interesting properties in modeling and control. They are especially useful for system interconnection because they retain their port-Hamiltonian structure. These structured systems, which are also close to physics, allow for a more generic understanding of the underlying dynamics of physical systems. However, data-driven modeling of port-Hamiltonian systems remains an open problem, particularly for nonlinear systems. In this talk, we look at the recent emergence of scientific machine learning techniques for learning port-Hamiltonian systems. More specifically, we compare between different architectures for learning port Hamiltonian systems from data and discuss different strategies to enable a more efficient training. Finally, we illustrate our results with different examples of physical systems.

**Bio:**  Karim Cherifi is a researcher at the University of Wuppertal (Germany) in the field of control theory with a focus on model reduction and data-driven modeling. In recent years, his main focus has been on modeling port-Hamiltonian systems. He is part of the newly established institute for port-Hamiltonian systems in Wuppertal. He obtained his PhD in Control theory in 2019 from the Institute of Electrical and Electronic Engineering in Boumerdes (Algeria). Afterwards, he was a postdoctoral researcher at the Max Planck Institute (MPI) for Dynamics of Complex Technical Systems in Magdeburg (Germany) and later at the Technical University of Berlin (Germany) where he was involved in the design of digital twins for Large Drive Applications within the project ’Elektrische Antriebe 2.0’ as part of the Werner-von-Siemens Centre for Industry and Science in Berlin. In terms of applications, Karim is involved in multiple industrial projects with a focus on modeling for digital twins. He is co-editor of a book on "physics based and data driven modeling for digital twins" that is about to appear. He obtained his PhD in Control theory in 2019. His expertise ranges from physical systems modeling, model reduction, data-driven modeling with a special focus on industrial applications.

**Web:**  [https://scholar.google.com/citations?user=gE5RRyEAAAAJ&hl=en](https://scholar.google.com/citations?user=gE5RRyEAAAAJ)

#### March Seminar: Thu. Mar 20, 2025

<img style='float:left;position: relative; margin-right: 10px; ' height='200' src='/images/learning/zahra_monfared.jpg'>  

**Speaker:** Dr. Zahra Monfared, Heidelberg University (Germany).

**Title:** Learning dynamics with RNNs: from training difficulties to gradient-free solutions

**Abstract:** Recurrent neural networks (RNNs) are a successful neural architecture for many time-dependent problems, including time series analysis, forecasting, and modeling of dynamical systems (DS). Training such networks with Backpropagation Through Time (BPTT) is a notoriously difficult problem because their loss gradients tend to saturate or diverge during training, referred to as the Exploding and Vanishing Gradient Problem (EVGP). For all major types of RNNs, including LSTMs and GRUs, the dynamics and loss gradients of RNNs are closely linked. If the RNN is “well behaved”, i.e. its dynamics converge to a stable fixed point or cycle, loss gradients will remain bounded, but they may vanish. Yet, established remedies can be used to effectively prevent their gradients from vanishing. However, in chaotic dynamics, gradients invariably explode, posing a challenge that cannot be mitigated through RNN architectural adjustments, regularization, or constraints; instead, it necessitates addressing the problem during the training process. Bifurcations may also contribute to sudden jumps in loss observed during RNN training, potentially hindering the training process severely. Therefore, to harness the full potential of RNNs, the training algorithm needs careful design to tackle challenges posed by bifurcations and chaos. Recently, we introduced a computational approach to construct all RNN weights and biases without using gradient-based methods, employing random feature networks and Koopman operator theory. This drastically reduces computational time while maintaining competitive performance, as demonstrated on several well-known DS—both uncontrolled and controlled. The connection to Koopman operator theory also allows us to start using results in this area to analyze RNNs. Through experiments, we observed very short training times—typically just seconds—and our method does not necessitate large amounts of data. Moreover, by sampling the hidden layers, we avoided BPTT which alleviates the problems with BPTT, such as EVGP.

**Bio:**  I am an independent BMBF Research Group Leader in Dynamical Systems and AI at Heidelberg University. Before that, I was a postdoc at the Technical University of Munich in Physics-Enhanced Machine Learning and at Heidelberg University in Scientific Machine Learning and Computational Neuroscience. I obtained a PhD in Applied Mathematics (Dynamical Systems) and an MSc in Pure Mathematics (Geometry and Differential Equations). I am interested in the Mathematical Foundations of AI, Scientific Machine Learning, and Complex Dynamical Systems, with applications in Neuroscience, Weather and Climate, Engineering, and Economics. Specifically, my work mainly focuses on two research directions: 1) Dynamical Systems for AI; and 2) AI for Dynamical Systems. I was awarded prestigious BMBF research funding to establish my independent research group in 2024 and the NeurIPS Outstanding Reviewer Award in 2021.

**Web:** [https://zmonfared.github.io/DSAIlab/](https://zmonfared.github.io/DSAIlab/)

#### April Seminar: Thu. April 17, 2025

<img style='float:left;position: relative; margin-right: 10px; ' height='200' src='/images/learning/richard_gao.jpg'>  

**Speaker:** Dr. Richard Gao, Tübingen University (Germany).

**Title:** Accelerating discovery of data-driven models and theories of neural dynamics

**Abstract:** How does cognition emerge from the complex interaction of biological elements in the brain? Neural dynamics offers a potential bridge between structure and function, where population activity is shaped by a variety of circuit properties and harnessed for computations at multiple timescales. In dissecting these relationships, we are now amassing brain measurements at an unprecedented scale. But while artificial intelligence excels at uncovering associations in large datasets, how AI can complement and advance mechanistic theories of neural dynamics remains an open question. In this talk, I outline how recent developments in AI—in particular, probabilistic generative models and sequence models—can help link neural dynamics with structure and function. To illustrate the opportunities and challenges of integrating heterogeneous multimodal datasets, I present a motivating example focused on neural timescales. Then, I will highlight two distinct approaches where AI can accelerate theoretical research in a data-driven manner: First, I discuss how simulation-based inference enables estimation of circuit properties from experimental recordings using a mechanistic model of network dynamics with interpretable parameters. Leveraging these tools, we discover many dynamic-consistent spiking neural network configurations and explore implications of invariance structures in parameter space. Second, I detail our recent works using state space models and diffusion models to synthesize realistic field potential and spiking data. Such models not only have practical applications like data imputation, they learn high-fidelity latent representations of neural dynamics and enable counterfactual experiments in silico, with further potential for equation-distillation. To close, I share my vision of how these approaches can be integrated for building tractable multi-scale models of brain dynamics to bridge neurobiology and neural computation, with the goal of translational applications in the long term. 

**Bio:**  Richard Gao earned a Bachelor’s in Engineering Science at the University of Toronto, specializing in electrical and bioengineering. During that time, he completed a one-year research internship at a neurotech startup developing consumer EEG technology for neurofeedback applications. He then pursued a PhD in the Department of Cognitive Science at UC San Diego with Bradley Voytek, where he received an NSERC Graduate Fellowship and the Chancellor’s Dissertation Medal for his work on modeling and analysis of neural signals. Since 2021, he has been in the Machine Learning in Science Group at the Tübingen AI Center, where he was a Marie Curie Postdoctoral Fellow working with Jakob Macke to develop mechanistic and generative models of brain dynamics.

**Web:** [https://www.rdgao.com/](https://www.rdgao.com/)







### Acknowledgements

<img style='float:right;position: relative; margin-right: 10px; ' height='200' src='/images/learning/logo_bfc.jpg'>  
The L&D seminar series is funded by generous support from [Région Bourgogne Franche-Comté](https://www.bourgognefranchecomte.fr/) (ANER ASPECT, 2022-2025, PI JJ Aucouturier). 