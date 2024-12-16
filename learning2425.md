---
title: Learning & Dynamics 2024-2025
permalink: /learning2425/
---

<img style='float:left;position: relative; margin-right: 10px; ' height='200' src='/images/learning/learning.jpg'> 

## Learning & Dynamics Seminars
<br>


Together with our FEMTO colleagues [Prof. John Dudley](https://www.femto-st.fr/en/femto-people/johndudley), Professor of Optical Physics, and [Dr Rafael Teloli](https://www.femto-st.fr/fr/personnel-femto/rafaelteloli), Assistant Prof. in Mechanical Engineering, the [FEMTO Neuro group](https://neuro-team-femto.github.io/) is putting together a monthly series of invited seminars on the topic of machine learning for dynamical systems. 

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
| Fri. Jan 17, 2025 | 2pm | [Dr Zahra Monfared](https://scholar.google.pl/citations?user=OPUIwIoAAAAJ&hl=en) (Interdisciplinary Center for Scientific Computing, Heidelberg University) | tba | Amphi JJ Gagnepain |
| Thu. Feb 20, 2025 | 2pm | [Dr Karim Cherifi](https://scholar.google.com/citations?user=gE5RRyEAAAAJ&hl=en) (Centre for Industry and Science, TU Berlin) | tba | Amphi J. Haag |
| Thu. Mar 20, 2025 | 2pm | [Dr Lorenzo Fontolan](https://fontolanl.github.io/) (Turing Center for Living Systems, Aix-Marseille University) | tba | Amphi JJ. Gagnepain |
| Thu. Apr 17, 2025 | 2pm | [Dr Richard Gao](http://www.rdgao.com/) (Tübingen AI Center, University of Tübingen) | tba | Amphi J. Haag |
| Thu. May 15, 2025 | 2pm | tba | tba | Amphi J. Haag |
| Thu. June 19, 2025 | 2pm | tba | tba | Amphi J. Haag |

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




### Acknowledgements

<img style='float:right;position: relative; margin-right: 10px; ' height='200' src='/images/learning/logo_bfc.jpg'>  
The L&D seminar series is funded by generous support from [Région Bourgogne Franche-Comté](https://www.bourgognefranchecomte.fr/) (ANER ASPECT, 2022-2025, PI JJ Aucouturier). 