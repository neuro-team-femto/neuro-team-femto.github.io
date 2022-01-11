---
title: Research internship (M2/école d'ingénieur.e.s)
categories: position
header-img: images/post/position/position.jpg
---

### Stage de M2: Identification de systèmes data-driven à partir de données humaines collectées en ligne, et application à la perception du sourire dans la voix  

*Deadline pour la candidature:* 15 Février 2022 <br>
*Start date:* Mars ou Avril 2022 <br>
*Durée:* 4-5 mois<br>

L'équipe [Neuro](https://neuro-team-femto.github.io) du Département d'[Automatique et Systèmes Micro-Mécatroniques](https://www.femto-st.fr/en/Research-departments/AS2M/Presentation), [Institut FEMTO-ST](https://www.femto-st.fr) à Besançon, France, propose un stage de recherche de type M2 Recherche / Ecole d'ingénieur.e.s à l'intersection entre l'informatique/data-science et les sciences cognitives.  

Le stage sera basé à l'Institut [FEMTO-ST](https://www.femto-st.fr) à Besançon et sera supervisé par [Jean-Julien Aucouturier](https://neuro-team-femto.github.io/people/jj_aucouturier/) (Directeur de recherche CNRS en informatique) et [Coralie Joucla](https://neuro-team-femto.github.io/people/coralie_joucla) (Chercheuse postdoctorante en neurosciences). Le stage sera conventionné et indemnisé par le CNRS (environ 570€ mensuel, [selon le volume horaire](https://www.service-public.fr/simulateur/calcul/gratification-stagiaire)). 

<hr>

#### Projet scientifique 

L'équipe [Neuro](https://neuro-team-femto.github.io) développe depuis quelques années une technique d'identification de système data-driven, dite par "reverse-correlation", qui permet de mettre en évidence la représentation mentale qu'a un auditeur de certaines caractéristiques acoustique de la parole, comme le fait de reconnaitre un "bonjour" dominant ou digne de confiance ([Ponsot et al., PNAS 2018](https://www.pnas.org/content/115/15/3972)) ou de savoir si votre interlocuteur vous ment ou dit la vérité ([Goupil et al. Nature Communications 2021](https://www.nature.com/articles/s41467-020-20649-4)). Cette méthode fonctionne en présentant à des participants d'expérience un grand nombre de stimuli générés aléatoirement, de façon à échantillonner l'espace des sons possibles, puis à regresser les réponses des participants sur les caractéristiques acoustiques des stimuli qu'ils ont jugés. L'équipe développe notamment pour cette méthode une toolbox open-source, le projet [CLEESE](https://neuro-team-femto.github.io/resources/).  

Ce type d'expérience de reverse correlation est généralement réalisé en laboratoire sur une 20aine de participants, en cabines audiométriques, écoutant chacun plusieurs centaines voire milliers de sons. Cela limite le nombre d'expériences différentes que l'on peut réaliser, et le nombre de participants que l'on peut interroger. Cette situation est évidemment accrue en période de restrictions sanitaires comme nous le vivons depuis 2 ans.  

Le but de ce stage est donc de développer et déployer une version en ligne de ce type d'expérience de reverse-correlation, permettant de collecter des données de plusieurs centaines de participants, et de mener l'analyse des données collectées en prenant en compte les spécificités d'une collecte en ligne (moins de données par un plus grand nombre de participants, filtrage des données de moindre qualité, etc.)

Plus spécifiquement, le stage prendra comme cas d'étude la généralisation en ligne d'une expérience que nous avons récemment menée sur la perception des indices acoustiques du sourire dans la voix ([Ponsot, Arias et Aucouturier, JASA 2018](https://asa.scitation.org/doi/10.1121/1.5020989)). Cette expérience faite en laboratoire a porté uniquement sur le son /a/. Le but de l'expérience à réaliser en ligne sera par exemple de la généraliser à tout l'inventaire phonémique du français (/a/, /i/, /u/, etc.) et de tester la significativité de corrélation faites entre les représentations mentales des participants et leurs caractéristiques individuelles, comme l'empathie ou le [quotient autistique](https://psychology-tools.com/test/autism-spectrum-quotient). 

Pour ce faire, le stage pourra s'appuyer sur un certain nombre de resources déjà développées dans l'équipe: 
- d'une part, une [version minimale](https://github.com/creamlab/revcor) d'expérience de reverse corrélation en ligne, développée en Javascript/[jspsych](https://www.jspsych.org/) et [Go](https://golang.org/), qu'il s'agira de prendre en main, d'étendre pour y inclure des questionnaire d'empathie, et de déployer sur un serveur hebergé à FEMTO-ST 
- d'autre part, notre toolbox Python [CLEESE](https://github.com/neuro-team-femto/cleese) permettant la génération de stimuli sonores aléatoires et l'analyse des données
- enfin, le pool de participants de notre partenaire le [Centre Multidisciplinaire des Sciences Comportementales INSEAD-Sorbonne](https://www.insead.edu/centres/insead-sorbonne-universite-lab-fr) (Paris) qui nous permettra de collecter les données en ligne. 

<hr>

#### Environnement 

Le ou la stagiaire rejoindra l'équipe [Neuro](https://neuro-team-femto.github.io/), un groupe de travail récemment constitué qui réunit 2 permanents, 1 chercheuse postdoctorale et 3 doctorantes, et dont les travaux de recherche explorent de nouvelles approches automaticiennes appliquées aux neurosciences ([plus de détails](https://neuro-team-femto.github.io/about/)). L'équipe Neuro fait partie du groupe *System Data Science*, un groupe de 7 chercheurs titulaires travaillant sur les méthodes data-driven pour l'analyse, la prédiction et le health management de systèmes naturels, industriels et environnementaux (dir.: Prof. [Jean-Marc Nicod](https://www.femto-st.fr/en/femto-people/jmnicod)). Nous sommes basés au Département d'[Automatique et Systèmes Micro-Mécatroniques](https://www.femto-st.fr/en/Research-departments/AS2M/Presentation) de l'[Institut FEMTO-ST](https://www.femto-st.fr) à Besançon, France. 

Dans l'équipe Neuro, le ou la stagiaire sera supervisée par [Jean-Julien Aucouturier](https://neuro-team-femto.github.io/people/jj_aucouturier/) (Directeur de recherche CNRS en informatique) et [Coralie Joucla](https://neuro-team-femto.github.io/people/coralie_joucla) (Chercheuse postdoctorante en neurosciences), et aura également l'opportunité d'interagir avec notre collaboratrice [Marie Gomot](https://ibrain.univ-tours.fr/marie-gomot) (Chercheuse INSERM, Université de Tours). 

![Femto](/images/post/position/femto.jpg){:style="float: left;margin-right: 12px;margin-top: 7px;" width="30%"} Accueillant plus de 750 chercheurs, l'[Institut FEMTO-ST](https://www.femto-st.fr) (CNRS/Université de Bourgogne Franche-Comté) est le plus gros laboratoire CNRS d'ingénierie de la région, avec une expertise couvrant l'ensemble des sciences de l'ingénieur et des systèmes. L'équipe Neuro est basée dans son Département d'[Automatique et Systèmes Micro-Mécatroniques](https://www.femto-st.fr/en/Research-departments/AS2M/Presentation), qui accueille environ 80 chercheurs actifs dans les domaines de la robotique, de l'automatique, de la mécatronique et de l'intelligence artificielle. <br clear="left"/>

![Besancon](/images/post/position/besancon.jpg){:style="float: left;margin-right: 12px;margin-top: 7px;" width="30%"} Classée au patrimoine mondial UNESCO, située à proximité des montagnes franco-suisses du Jura, la ville de [Besançon](https://boosteurdebonheur.besancon.fr/) est une capitale régionale à taille humaine, régulièrement primée pour sa [qualité de vie](https://paris-jetequitte.com/partir-vivre-besancon/) et sa surface d'espace vert par habitant. Elle est également l'un des sites de l'université nouvellement fédérée [de Bourgogne Franche-Comté](https://www.ubfc.fr/en/)), qui accueille plus de 50 000 étudiants. 

<br clear="left"/>

<hr>

#### Candidats

Le ou la candidat.e idéal.e pour ce stage est un.e étudiant.e en M2 Recherche ou en école d'ingénieur.e.s, 
- soit avec une formation computationnelle (data science, informatique, automatique, mathématiques appliquées, statistiques) et un intérêt pour les sciences cognitives et les neurosciences; 
- soit avec une formation psychologie/neuroscience et de solides compétences d'analyse de données et de programmation (neurosciences computationnelles, modélisation psychophysique)

Ce stage est adapté à des candidat.e.s ayant déja une expérience d'analyse de données et de solides compétences de programmation en Python ou R. Une connaissance supplémentaires des langages et technologies du web, comme Javascript ou Go, sera un plus appréciable, mais non nécessaire. Pour profiter au mieux de ce stage, le ou la candidat.e aura aussi sans doute un intérêt pour le milieu de la recherche fondamentale, les sciences du langage ou de l'audition et les neurosciences.  

<hr>

#### Comment candidater

Envoyer (1) un CV, (2) une lettre de motivation (expliquant notamment vos expériences de programmation et d'analyse de données) et (3) le nom de 1 référent académique à même de vous recommander (pas besoin de lettre de recommendation au moment de la candidature) par email à Jean-Julien Aucouturier ([aucouturier@gmail.com](mailto:aucouturier@gmail.com)) et Coralie Joucla  ([coralie.joucla.pro@gmail.com](mailto:coralie.joucla.pro@gmail.com)). <br>

**Deadline: 15 Février 2022** <br>

