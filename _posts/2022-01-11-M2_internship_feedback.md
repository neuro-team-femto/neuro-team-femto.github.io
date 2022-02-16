---
title: Research internship (M2/école d'ingénieur.e.s)
categories: position
header-img: images/post/position/position.jpg
---

### Stage de M2: Conception et test d'un système de contrôle boucle-fermée de la voix humaine, en LabView

<hr>
<font color='red'> <b> Les candidatures pour ce stage sont closes. </b> </font> 
<hr>

<!-- *Deadline pour la candidature:* 15 Février 2022 <br>
*Start date:* Mars ou Avril 2022 <br>
*Durée:* 4-5 mois<br>-->

Le groupe [Neuro](https://neuro-team-femto.github.io) du Département d'[Automatique et Systèmes Micro-Mécatroniques](https://www.femto-st.fr/en/Research-departments/AS2M/Presentation), [Institut FEMTO-ST](https://www.femto-st.fr) à Besançon, France, propose un stage de recherche de type M2 Recherche / Ecole d'ingénieur.e.s à l'intersection de l'automatique, du traitement du signal vocal et des sciences cognitives.  

Le stage sera basé à l'Institut [FEMTO-ST](https://www.femto-st.fr) à Besançon et sera supervisé par [Patrick Nectoux](https://www.femto-st.fr/en/femto-people/patricknectoux) (Ingénieur de recherche CNRS) et [Jean-Julien Aucouturier](https://neuro-team-femto.github.io/people/jj_aucouturier/) (Directeur de recherche CNRS en informatique). Le stage sera conventionné et indemnisé par le CNRS (environ 570€ mensuel, [selon le volume horaire](https://www.service-public.fr/simulateur/calcul/gratification-stagiaire)). 

<hr>

#### Projet scientifique 

La parole chez l'homme est rendue possible par une boucle de rétroaction sensorimotrice ([auditory feedback](https://en.wikipedia.org/wiki/Auditory_feedback)) en trois partie dans laquelle les locuteurs parlent, entendent ce qu'ils viennent de prononcer, et enfin se corrigent si nécessaire. Ce système de feedback est très rapide et en grande partie automatique: par exemple, quand on s'entend parler avec un délai de quelques centaines de millisecondes, on ne peut s'empêcher de bégayer (Stuart et al., 2002); quand on modifie la voix du locuteur dans son casque de façon à en augmenter la hauteur (pitch), celui-ci ajuste automatiquement le pitch de sa voix vers le bas pour compenser, dans un délai d'environ 300 millisecondes (Burnett, Senner & Larson, 1997).  

<img class='img-responsive center-block' src="/images/post/position/vocal_feedback.jpg" width="70%" height="70%" />

Le groupe [Neuro](https://neuro-team-femto.github.io) développe depuis quelques années un paradigme de feedback vocal utilisant [un algorithme de traitement du signal vocal](https://link.springer.com/article/10.3758/s13428-017-0873-y) pour modifier la hauteur de voix d'un participant en temps-réel, afin que le participant s'entende avec une voix plus haute ou plus basse qu'en réalité. Avec ce système, nous avons pu montrer que, quand un participant s'entend parler en temps-réel avec un ton de voix rendu plus haut / joyeux, il devient lui-même plus joyeux, alors que quand il s'entend parler avec ton de voix rendu plus bas / triste, il devient plus triste, alors même qu'il n'a pas conscience de la transformation acoustique qui est appliquée à sa voix à son insu ([Aucouturier et al. PNAS 2016](https://www.pnas.org/content/113/4/948)). Dans ce type d'expérience, environ 1/3 des participants compensent acoustiquement la transformation, c'est-à-dire que quand on augmente la hauteur de leur entrée "en entrée du système", ils baissent la hauteur de leur voix "en sortie du système" ([Goupil et al., Consciousness & Cognition, 2021](https://www.sciencedirect.com/science/article/abs/pii/S1053810020305390?dgcid=coauthor)). 

Dans tous ces travaux, la modification de voix est faite *en boucle ouverte*, c'est-à-dire que l'on perturbe l'entrée du système (la voix perçue) et qu'on en étudie l'impact sur la sortie (la voix produite), mais où la transformation de voix en entrée est fixe et n'est pas calculée en fonction de la voix produite. 

Pour aller plus loin, le but de ce stage est de concevoir et de tester un dispositif de contrôle *en boucle fermée*, doté: 
- d'un module d'analyse en temps-réel du pitch de la voix du participant, à partir du micro (par exemple basé sur l'algorithme yin; [De Cheveigné & Kawahara, 2002](http://audition.ens.fr/adc/pdf/2002_JASA_YIN.pdf))
- d'un module de transformation en temps-réel du pitch de la voix du participant, en amont du casque (par exemple basé sur notre technologie DAVID; [Rachman et al. 2017](https://link.springer.com/article/10.3758/s13428-017-0873-y))
- et d'un module de contrôle (de type PID) permettant de construire un signal de commande en entrée (transformation) en fonction de la mesure du pitch en sortie (yin)

Ce dispositif sera conçu dans le langage de programmation temps-réel [LabView](https://www.ni.com/fr-fr/shop/labview.html) (National Instruments), d'une façon qui pourra s'inspirer de ce système existant: [Shen, Wang & Zhou, 2021](http://www.csroc.org.tw/journal/JOC32-2/JOC3202-19.pdf). 


Pour ce faire, le stage pourra s'appuyer sur un certain nombre de ressources déjà développées dans le groupe: 
- des implémentations temps-réel existantes des algorithmes d'analyse et de transformation de la voix, qu'il s'agira d'adapter et intégrer dans l'architecture LabView
- un environnement de développement pour LabView comprenant des licences logicielles, une plateforme matérielle haute-performance ([CompactRIO](https://www.ni.com/fr-fr/shop/compactrio.html)) pour le déploiement du code, et différents modules d'entrée/sortie pour l'acquisition de son du micro et la diffusion vers le casque du participant. 


<sub>
Burnett, T. A., Senner, J. E., & Larson, C. R. (1997). [Voice F0 responses to pitch-shifted auditory feedback: a preliminary study](https://www.sciencedirect.com/science/article/abs/pii/S0892199797800793). Journal of Voice, 11(2), 202-211. <br>
De Cheveigné, A., & Kawahara, H. (2002). YIN, a fundamental frequency estimator for speech and music. The Journal of the Acoustical Society of America, 111(4), 1917-1930.<br>
Parrell, B., Agnew, Z., Nagarajan, S., Houde, J., & Ivry, R. B. (2017). [Impaired feedforward control and enhanced feedback control of speech in patients with cerebellar degeneration](https://www.jneurosci.org/content/37/38/9249). Journal of Neuroscience, 37(38), 9249-9258.<br>
Shen, B. X., Wang, K. Y., & Zhou, J. H. (2021). Design of a Pitch Detection and Intonation Correction System Based on LabVIEW. Journal of Computers, 32(2), 222-232.<br>
Stuart, A., Kalinowski, J., Rastatter, M. P., & Lynch, K. (2002). [Effect of delayed auditory feedback on normal speakers at two speech rates](https://asa.scitation.org/doi/abs/10.1121/1.1466868). The Journal of the Acoustical Society of America, 111(5), 2237-2241. <br>
</sub>


<hr>

#### Environnement 

Le ou la stagiaire rejoindra le groupe [Neuro](https://neuro-team-femto.github.io/), un groupe de travail récemment constitué qui réunit 2 permanents, 1 chercheuse postdoctorale et 3 doctorantes, et dont les travaux de recherche explorent de nouvelles approches automaticiennes appliquées aux neurosciences ([plus de détails](https://neuro-team-femto.github.io/about/)). Le groupe Neuro fait partie de l'équipe *System Data Science*, un ensemble de 7 chercheurs titulaires travaillant sur les méthodes data-driven pour l'analyse, la prédiction et le health management de systèmes naturels, industriels et environnementaux (dir.: Prof. [Jean-Marc Nicod](https://www.femto-st.fr/en/femto-people/jmnicod)). Nous sommes basés au Département d'[Automatique et Systèmes Micro-Mécatroniques](https://www.femto-st.fr/en/Research-departments/AS2M/Presentation) de l'[Institut FEMTO-ST](https://www.femto-st.fr) à Besançon, France. 

Dans le groupe Neuro, le ou la stagiaire sera supervisé.e par [Patrick Nectoux](https://www.femto-st.fr/en/femto-people/patricknectoux) (Ingénieur de recherche CNRS; formateur LabView) et [Jean-Julien Aucouturier](https://neuro-team-femto.github.io/people/jj_aucouturier/) (Directeur de recherche CNRS en sciences cognitives). 

![Femto](/images/post/position/femto.jpg){:style="float: left;margin-right: 12px;margin-top: 7px;" width="30%"} Accueillant plus de 750 chercheurs, l'[Institut FEMTO-ST](https://www.femto-st.fr) (CNRS/Université de Bourgogne Franche-Comté) est le plus gros laboratoire CNRS d'ingénierie de la région, avec une expertise couvrant l'ensemble des sciences de l'ingénieur et des systèmes. Le groupe Neuro est basé dans son Département d'[Automatique et Systèmes Micro-Mécatroniques](https://www.femto-st.fr/en/Research-departments/AS2M/Presentation), qui accueille environ 80 chercheurs actifs dans les domaines de la robotique, de l'automatique, de la mécatronique et de l'intelligence artificielle. <br clear="left"/>

![Besancon](/images/post/position/besancon.jpg){:style="float: left;margin-right: 12px;margin-top: 7px;" width="30%"} Classée au patrimoine mondial UNESCO, située à proximité des montagnes franco-suisses du Jura, la ville de [Besançon](https://boosteurdebonheur.besancon.fr/) est une capitale régionale à taille humaine, régulièrement primée pour sa [qualité de vie](https://paris-jetequitte.com/partir-vivre-besancon/) et sa surface d'espace vert par habitant. Elle est également l'un des sites de l'université nouvellement fédérée [de Bourgogne Franche-Comté](https://www.ubfc.fr/en/)), qui accueille plus de 50 000 étudiants. 

<br clear="left"/>

<hr>

#### Candidats

Ce stage est adapté à des candidat.e.s ayant déjà une expérience de conception de systèmes de contrôle/commande en Labview, et une bonne connaissance des concepts de l'automatique, du traitement du signal et de la commande temps-réel.

Le ou la candidat.e idéal.e pour ce stage est un.e étudiant.e en M2 Recherche ou en école d'ingénieur.e.s avec une formation d'automaticien.ne (control engineering, mécatronique, traitement du signal) et un intérêt pour la recherche en sciences du langage, la cognition et les neurosciences. 

<hr>

#### Comment candidater

Envoyer (1) un CV, (2) une lettre de motivation (expliquant notamment vos expériences de programmation et d'analyse de données) et (3) le nom de 1 référent académique à même de vous recommander (pas besoin de lettre de recommandation au moment de la candidature) par email à [Patrick Nectoux](https://www.femto-st.fr/en/femto-people/patricknectoux) et Jean-Julien Aucouturier ([aucouturier@gmail.com](mailto:aucouturier@gmail.com)). <br>

<!-- **Deadline: 15 Février 2022** <br> -->
<hr>
<font color='red'> <b> Les candidatures pour ce stage sont closes. </b> </font> 
<hr>


