---
title: Research internship (M1/M2/école d'ingénieur.e.s)
categories: position
header-img: images/post/position/position.jpg
---

### Stage de M1/M2: Développement d'une librairie Python open-source d'interfaçage avec un contrôleur LabVIEW CompactRIO, pour un dispositif de recherche en neurosciences. 

*Deadline pour la candidature:* 15 Décembre 2025 <br>
*Start date:* Mars ou Avril 2025 <br>
*Durée:* 4-5 mois<br>

Le groupe [Neuro](https://neuro-team-femto.github.io) du Département d'[Automatique et Systèmes Micro-Mécatroniques](https://www.femto-st.fr/en/Research-departments/AS2M/Presentation), [Institut FEMTO-ST](https://www.femto-st.fr) à Besançon, France, propose un stage de recherche de type M1/M2 Recherche / Ecole d'ingénieur.e.s à l'intersection entre l'instrumentation, les objects connectés et les neurosciences/sciences de la parole.  

Le stage sera basé à l'Institut [FEMTO-ST](https://www.femto-st.fr) à Besançon et sera supervisé par [Patrick Nectoux](https://www.femto-st.fr/en/femto-people/patricknectoux) (Ingénieur de recherche CNRS) et [Jean-Julien Aucouturier](https://neuro-team-femto.github.io/people/jj_aucouturier/) (Directeur de recherche CNRS en informatique). 

Le stage sera conventionné et indemnisé par SUPMICROTECH/ENSMM (environ 570€ mensuel, [selon le volume horaire](https://www.service-public.fr/simulateur/calcul/gratification-stagiaire)). 

<hr>

#### Projet scientifique 

La parole chez l'homme est rendue possible par une boucle de rétroaction sensorimotrice ([auditory feedback](https://en.wikipedia.org/wiki/Auditory_feedback)) dans laquelle les locuteurs parlent, entendent ce qu'ils viennent de prononcer, et se corrigent si nécessaire. Ce système de feedback est très rapide et en grande partie automatique: par exemple, quand on s'entend parler avec un délai de quelques centaines de millisecondes, on ne peut s'empêcher de bégayer (Stuart et al., 2002); quand on modifie la voix du locuteur dans son casque de façon à en augmenter la hauteur (pitch), celui-ci ajuste automatiquement le pitch de sa voix vers le bas pour compenser, dans un délai d'environ 300 millisecondes (Burnett, Senner & Larson, 1997).  

<img class='img-responsive center-block' src="/images/post/position/vocal_feedback.jpg" width="70%" height="70%" />

Le groupe [Neuro](https://neuro-team-femto.github.io) développe un dispositif de "feedback vocal" utilisant [un algorithme de traitement du signal](https://link.springer.com/article/10.3758/s13428-017-0873-y) pour modifier la hauteur de voix d'un participant en temps-réel, afin que le participant s'entende avec une voix plus haute ou plus basse qu'en réalité. Avec ce système, nous avons pu montrer par exemple que, quand un participant s'entend parler en temps-réel avec un ton de voix rendu plus haut / joyeux, il devient lui-même plus joyeux, alors que quand il s'entend parler avec ton de voix rendu plus bas / triste, il devient plus triste, alors même qu'il n'a pas conscience de la transformation acoustique qui est appliquée à sa voix à son insu ([Aucouturier et al. PNAS 2016](https://www.pnas.org/content/113/4/948)). 

Le dispositif est implémenté sur un contrôleur [CompactRio](https://www.ni.com/fr/shop/compactrio.html?srsltid=AfmBOooeEioLOtTlXThkgkavIojTUOL7yCYwKbpp46CshLfM9kYxK9-M) (cRIO-9053), et programmé en [LabView](https://www.ni.com/fr-fr/shop/labview.html) (National Instruments). Avant de pouvoir l'intégrer dans des expériences de neurosciences, soit dans notre [laboratoire local](https://neuro-team-femto.github.io/participate), soit dans les laboratoires de nos collaborateurs en Europe, nous avons besoin d'interfacer ce dispositif en Python afin, par exemple, de commander son déclenchement ou d'en modifier les paramètres à la volée, en cours d'expérience.  

#### But du stage 

Le but du stage est de développer les couches Python et LabVIEW permettant une communication entre un PC et le dispositif CompactRIO via un protocole à déterminer (typiquement, port série sur connectique USB ou RS-232). Côté Python, le but est de développer une librairie avec une API permettant de passer et recevoir plusieurs types de messages (a minima, se connecter au device, lui envoyer des changements de paramètres). La librairie sera diffusée de façon open-source sur le [github de l'équipe](https://github.com/neuro-team-femto/) et documentée sous le framework Materials for Mkdown (ex. [https://neuro-team-femto.github.io/cleese/](https://neuro-team-femto.github.io/cleese/)). Côté LabVIEW, le but est de développer une couche logicielle I/O au sein du code LabVIEW existant, et qui soit capable de recevoir, parser et interpréter ces messages, ainsi que d'envoyer des informations vers Python en retour. 

Pour ce faire, le/la stagiaire pourra s'appuyer sur un certain nombre de ressources déjà disponibles dans le groupe: 
- un dispositif LabVIEW fonctionnel, dans lequel il faudra ajouter une couche logicielle d'I/O
- un environnement de développement pour LabView comprenant des licences logicielles, une plateforme matérielle haute-performance ([CompactRIO](https://www.ni.com/fr-fr/shop/compactrio.html)) pour le déploiement du code, et différents modules d'entrée/sortie pour l'acquisition de son du micro et la diffusion vers le casque du participant. 
- une expertise en développement LabVIEW (encadrement de Patrick Nectoux) et en développement Python (encadrement de JJ Aucouturier).
- une expertise en diffusion open-source de code de recherche, et de l'environnement de développement git/github 

<hr>

#### Candidats

Le ou la candidat.e idéal.e pour ce stage est un.e étudiant.e en M1, M2 Recherche ou en école d'ingénieur.e.s avec une formation d'informatique, instrumentation embarquée ou objets connectés, et un intérêt pour l'expérimentation dans un contexte de neurosciences/sciences du langage. 

Ce stage est adapté à des candidat.e.s ayant déjà une expérience de conception de systèmes communiquants (objets connectés, protocole série), en programmation Python (interaction matérielle/OS en particulier) et en de programmation LabVIEW (instrumentation, interfaçage). Une connaissance de l'environnement cRIO ou d'autres systèmes embarqués (arduino, etc.) pourra également être mise à profit. Une expérience ou un intérêt pour le logiciel libre, et le partage et la documentation de code sous git/github seront également appréciés. Les profils ne réunissant pas tous ces éléments sont évidemment les bienvenus, du moment que les candidat.e.s peuvent démontrer leur appétit d'apprendre.  

Une expérience en neurosciences/sciences du langage n'est pas nécessaire, du moment que le sujet intrigue (les candidats pourront parcourir les articles [Aucouturier et al. 2016](https://neuro-team-femto.github.io/articles/2016/Aucouturier_PNAS_2016.pdf) et [Goupil et al. 2021](https://neuro-team-femto.github.io/articles/2021/Goupil_Consciousness_Cognition_2021.pdf) pour se faire une idée des applications envisagées). 

<hr>

#### Environnement 

Le ou la stagiaire rejoindra le groupe [Neuro](https://neuro-team-femto.github.io/), une équipe de recherche qui réunit 2 chercheurs permanents, 1 chercheur postdoctorant et 4 doctorants, et dont les travaux de recherche explorent de nouvelles approches automaticiennes appliquées aux neurosciences ([plus de détails](https://neuro-team-femto.github.io/about/)). Le groupe Neuro est basé au Département d'[Automatique et Systèmes Micro-Mécatroniques](https://www.femto-st.fr/en/Research-departments/AS2M/Presentation) de l'[Institut FEMTO-ST](https://www.femto-st.fr) à Besançon, France, dans les locaux de l'école [SUPMICROTECH/ENSMM](https://www.supmicrotech.fr/). 

Dans le groupe Neuro, le ou la stagiaire sera supervisé.e par [Patrick Nectoux](https://www.femto-st.fr/en/femto-people/patricknectoux) (Ingénieur de recherche CNRS) et [Jean-Julien Aucouturier](https://neuro-team-femto.github.io/people/jj_aucouturier/) (Directeur de recherche CNRS). 

![Femto](/images/post/position/femto.jpg){:style="float: left;margin-right: 12px;margin-top: 7px;" width="30%"} Accueillant plus de 750 chercheurs, l'[Institut FEMTO-ST](https://www.femto-st.fr) (CNRS/Université de Bourgogne Franche-Comté) est l'un des plus gros laboratoire CNRS de France en Sciences de l'Ingénieur, avec une expertise couvrant l'ensemble des sciences de l'ingénieur et des systèmes. Le groupe Neuro est basé dans son Département d'[Automatique et Systèmes Micro-Mécatroniques](https://www.femto-st.fr/en/Research-departments/AS2M/Presentation), qui accueille environ 80 chercheurs actifs dans les domaines de la robotique, de l'automatique, de la mécatronique et de l'intelligence artificielle. <br clear="left"/>

![Besancon](/images/post/position/besancon.jpg){:style="float: left;margin-right: 12px;margin-top: 7px;" width="30%"} Classée au patrimoine mondial UNESCO, située à proximité des montagnes franco-suisses du Jura, la ville de [Besançon](https://boosteurdebonheur.besancon.fr/) est une capitale régionale à taille humaine, régulièrement primée pour sa [qualité de vie](https://paris-jetequitte.com/partir-vivre-besancon/) et sa surface d'espace vert par habitant.  

<br clear="left"/>

<hr>

#### Comment candidater

Envoyer les élements suivants par email à Patrick Nectoux ([patrick.nectoux@femto-st.fr](mailto: patrick.nectoux@femto-st.fr)) et Jean-Julien Aucouturier ([aucouturier@gmail.com](mailto:aucouturier@gmail.com)): 

1. un CV, 
2. une lettre de motivation (détaillant obligatoirement vos expériences de conception de systèmes communiquants, en programmation Python et en programmation LabVIEW), 
3. le nom et le contact de 1 référent académique (professeur, tuteur de stage, etc.) à même de vous recommander (pas besoin de lettre de recommandation au moment de la candidature) 

**Date limite de candidature: 15 Décembre 2024**. Les candidat.e.s retenu.e.s sur la base de leur dossier seront convoqué.e.s pour un entretien. Les candidatures seront évaluées au fil de l'eau au cours de l'automne 2024, et le stage pourra être pourvu avant la deadline. 

**Dates du stage:** Printemps-Ete 2025 (ex. Mars - Août 2025), selon le calendrier de la formation du/de la candidat.e. Durée minimum souhaitée 4 mois.  



