---
title: Research internship (M1/M2/école d'ingénieur.e.s)
categories: position
header-img: images/post/position/position.jpg
---

### Stage de M1/M2: Analyse data-driven du couplage dynamique entre 2 musiciens. 

*Deadline pour la candidature:* 15 Janvier 2026 <br>
*Start date:* Mars ou Avril 2026 <br>
*Durée:* 4-6 mois<br>

Le groupe [Neuro](https://neuro-team-femto.github.io) du Département d'[Automatique et Systèmes Micro-Mécatroniques](https://www.femto-st.fr/en/Research-departments/AS2M/Presentation), [Institut FEMTO-ST](https://www.femto-st.fr) à Besançon, France, en collaboration avec l'équipe [Analyse des Pratiques Musicales](https://www.stms-lab.fr/team/analyse-des-pratiques-musicales) du laboratoire [Sciences et Technologies de la Musique et du Son](https://www.stms-lab.fr) à Paris propose un stage de recherche de type M1/M2 Recherche / Ecole d'ingénieur.e.s à l'intersection entre les systèmes dynamiques, la modélisation du comportement et la musique.  

Le stage sera basé à l'Institut [FEMTO-ST](https://www.femto-st.fr) à Besançon et sera supervisé, en local, par [Jean-Julien Aucouturier](https://neuro-team-femto.github.io/people/jj_aucouturier/) (Directeur de recherche CNRS, FEMTO-ST) et, à distance, par [Clément Canonne](https://www.stms-lab.fr/person/clement-canonne) (Directeur de recherche CNRS, STMS). 

Le stage sera conventionné et indemnisé par le CNRS (environ 570€ mensuel, [selon le volume horaire](https://www.service-public.fr/simulateur/calcul/gratification-stagiaire)). 

<hr>

#### Projet scientifique 

Lorsque des humains agissent ensemble, ils manifestent souvent une tendance irrésistible à synchroniser leurs mouvements. L'explication dominante, développée ces vingt dernières années, est que cette synchronisation ne résulte pas d'un traitement explicite de l’information, mais de mécanismes sensorimoteurs émergents appelés en anglais _entrainment_ [(Repp & Su, 2013)](https://link.springer.com/article/10.3758/s13423-012-0371-2), où un oscillateur adapte son rythme à un stimulus externe. Cependant, ces modèles permettent de comprendre comment un individu s'aligne sur une source extérieure, mais négligent les situations où deux personnes cherchent à éviter cette mise en phase. En effet, si l'_entrainment_ favorise la coordination, certaines interactions exigent au contraire d'empêcher ou de limiter la synchronisation.

Pour mieux comprendre les processus à l'oeuvre dans ces cas de désynchronisation intentionnelle, un vaste ensemble de données expérimentales (environ 1000 extraits de 30 secondes) a été recueilli en 2025. Des duos et trios de percussionnistes experts (jouant sur des batteries MIDI) y étaient invités à résister à une synchronisation involontaire les uns avec les autres (par ex. l'un jouer à tempo 100bpm, et l'autre à tempo 102bpm), ou à se désynchroniser volontairement. 

<p float='center'>
	<iframe width='40%' src='/images/post/position/rtrain.mp4' frameborder='0'></iframe> 
	<img src='/images/post/position/rtrain.png' width='60%' /> 
	<i>Exemple de données enregistrées avec 2 percussionnistes (rouge, noir). A t=0, le musicien "noir" reçoit l'instruction de ralentir pendant 20s (son inter-beat-interval IBI augmente)the black player is instructed to slow down (i.e. increase inter-beat-interval, IBI), et le musicien "rouge" doit résister à se synchroniser involontairement et maintenir son propre tempo. </i>
</p>


#### But du stage 

Le but du stage est d'utiliser des techniques d'analyse de données inspirées de la théorie des systèmes dynamiques pour caractériser le degré de couplage, ou d'indépendance, entre les signaux des musiciens enregistrés - cad comment quantifier si 2 musiciens arrivent, ou non, à résister à la synchronisation. Ce travail pourra s'inspirer, dans un premier temps, d'un certain nombre de mesures proposées pour quantifier les interactions [(Cliff et al., 2023)](https://arxiv.org/pdf/2201.11941), comme la causalité de Granger ou la méthode _convergent cross mapping_ [(Sugihara et al, 2012)](https://deepeco.ucsd.edu/wp-content/uploads/2019/10/causalityCCM.pdf). Dans un second temps, le travail pourra utiliser une approche de modélisation, pour directement identifier un système dynamique capable de simuler les données, soit en utilisant des modèles de la litérature sensorimotrice [(Van De Steen & Keller, 2013)](https://www.frontiersin.org/journals/human-neuroscience/articles/10.3389/fnhum.2013.00253/full), soit des approches de découverte de modèle comme la méthode SINDY [(Brunton et al., 2016)](https://www.pnas.org/doi/abs/10.1073/pnas.1517384113). 

Pour ce faire, le/la stagiaire pourra s'appuyer sur un certain nombre de ressources déjà disponibles dans le groupe: 
- un large corpus de données d'interaction de musiciens, enregistrées en MIDI et directement convertibles en séries temporelles de IBIs
- une expertise en analyse et modélisation de systèmes dynamiques appliquées à la cognition et aux neurosciences ([Aucouturier & Canonne, 2017](https://www.sciencedirect.com/science/article/pii/S0010027717300276);[Hu et al., 2025](https://www.biorxiv.org/content/10.1101/2025.07.17.665340.abstract))
- une expertise en cognition musicale et en synchronisation sensorimotrice ([Sinat-Germier et al., 2024](https://link.springer.com/article/10.1007/s11097-021-09789-0); [Wolf, Goupil & Canonne, 2023](https://psycnet.apa.org/record/2023-79616-001))

<hr>

#### Candidats

Le ou la candidat.e idéal.e pour ce stage est un.e étudiant.e en M1, M2 Recherche ou en école d'ingénieur.e.s avec: 
- soit une formation en maths appliqués, physique computationnelle (systèmes dynamiques) ou informatique (traitement du signal, automatique, machine learning), et un intérêt pour l'expérimentation dans un contexte de la cognition musicale, de l'action conjointe ou des sciences du mouvement. 
- soit une formation en psychologie expérimentale, action conjointe ou sciences du mouvement, et une appétance pour l'analyse et la modélisation mathématique, physique ou informatique de données expérimentale. 

Quelque soit la formation, ce stage est adapté à des candidat.e.s ayant déjà une expérience d'analyse de données expérimentale, et de programmation Python, Matlab ou R. 

<hr>

#### Environnement 

Le ou la stagiaire rejoindra le groupe [Neuro](https://neuro-team-femto.github.io/), une équipe de recherche qui réunit 2 chercheurs permanents, 1 chercheur postdoctorant et 4 doctorants, et dont les travaux de recherche explorent de nouvelles approches automaticiennes appliquées aux neurosciences ([plus de détails](https://neuro-team-femto.github.io/about/)). Le groupe Neuro est basé au Département d'[Automatique et Systèmes Micro-Mécatroniques](https://www.femto-st.fr/en/Research-departments/AS2M/Presentation) de l'[Institut FEMTO-ST](https://www.femto-st.fr) à Besançon, France, dans les locaux de l'école [SUPMICROTECH/ENSMM](https://www.supmicrotech.fr/). Dans le groupe Neuro, le ou la stagiaire sera supervisé.e par [Jean-Julien Aucouturier](https://neuro-team-femto.github.io/people/jj_aucouturier/) (Directeur de recherche CNRS). 

Le stage se déroulera également en interaction avec l'équipe [Analyse des Pratiques Musicales](https://www.stms-lab.fr/team/analyse-des-pratiques-musicales) du laboratoire [Sciences et Technologies de la Musique et du Son](https://www.stms-lab.fr) à Paris. Le stagiaire bénéficiera de la co-supervision à distance de [Clément Canonne](https://www.stms-lab.fr/person/clement-canonne) (Directeur de recherche CNRS, STMS), avec la possibilité de réaliser quelques déplacements possibles à Paris si besoin. 

Le stage est financé dans le cadre du projet R.TRAIN (Resisting entrainment: a dynamical systems approach), financé par l'appel _Interactions complexes et comportements collectifs_ de la MITI CNRS. Des échanges ponctuels seront organisés avec [Thomas Wolf](https://cognitivescience.ceu.edu/people/thomas-wolf-0), chercheur postdoctoral en sciences cognitives à Central European University, également partenaire du projet. 

![Femto](/images/post/position/femto.jpg){:style="float: left;margin-right: 12px;margin-top: 7px;" width="30%"} Accueillant plus de 750 chercheurs, l'[Institut FEMTO-ST](https://www.femto-st.fr) (CNRS/Université de Bourgogne Franche-Comté) est l'un des plus gros laboratoire CNRS de France en Sciences de l'Ingénieur, avec une expertise couvrant l'ensemble des sciences de l'ingénieur et des systèmes. Le groupe Neuro est basé dans son Département d'[Automatique et Systèmes Micro-Mécatroniques](https://www.femto-st.fr/en/Research-departments/AS2M/Presentation), qui accueille environ 80 chercheurs actifs dans les domaines de la robotique, de l'automatique, de la mécatronique et de l'intelligence artificielle. <br clear="left"/>

![Besancon](/images/post/position/besancon.jpg){:style="float: left;margin-right: 12px;margin-top: 7px;" width="30%"} Classée au patrimoine mondial UNESCO, située à proximité des montagnes franco-suisses du Jura, la ville de [Besançon](https://boosteurdebonheur.besancon.fr/) est une capitale régionale à taille humaine, régulièrement primée pour sa [qualité de vie](https://paris-jetequitte.com/partir-vivre-besancon/) et sa surface d'espace vert par habitant.  

<br clear="left"/>

<hr>

#### Comment candidater

Envoyer les élements suivants par email à Jean-Julien Aucouturier ([jj.aucouturier@pm.me](mailto: jj.aucouturier@pm.me)) et Clément Canonne  ([clement.canonne@ircam.fr](mailto:clement.canonne@ircam.fr)): 

1. un CV, 
2. une lettre de motivation (détaillant obligatoirement votre background théorique en rapport avec le sujet, vos expériences de analyse de données expérimentale, et en programmation Python/Matlab/R), 
3. le nom et le contact de 1 référent académique (professeur, tuteur de stage, etc.) susceptible de vous recommander (pas besoin de lettre de recommandation au moment de la candidature) 

**Date limite de candidature: 15 Janvier 2026**. Les candidat.e.s retenu.e.s sur la base de leur dossier seront convoqué.e.s pour un entretien en visio. 

**Dates du stage:** Printemps-Ete 2026 (ex. Mars - Août 2026), selon le calendrier de la formation du/de la candidat.e. Durée minimum souhaitée 4 mois, maximum 6 mois.  



