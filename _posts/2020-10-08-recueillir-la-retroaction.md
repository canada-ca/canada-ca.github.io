---
layout: post
title:  "Recueillir la rétroaction, trouver les problèmes"
pubdate: "8 octobre 2020"
langpage: "https://blog.canada.ca/2020/10/08/collect-feedback.html"
date:   2020-10-08
published: true
draft: true
lang: fr
alt: "Recueillir la rétroaction, trouver les problèmes"
description: " "
---
En 2020, les interactions de la majorité des Canadiens avec leur gouvernement se font principalement en ligne. Les pages Web du gouvernement du Canada sont plus qu’un simple outil de communication. Elles sont un important point de prestation de services. 

Obtenir régulièrement de la rétroaction des Canadiens aide les équipes dans l’ensemble du gouvernement à améliorer continuellement la prestation des services sur le site Canada.ca. Lorsque les gens peuvent trouver les réponses à leurs questions en ligne, cela permet de réduire le nombre de courriels et d’appels aux centres d’appels. 

Et si nous pouvions être informés plus tôt lorsque les gens ne trouvent pas les réponses qu’ils cherchent en ligne?

## Étude pilote

En mai 2020, quelques équipes ont collaboré au lancement de l’étude pilote d’un widget pour obtenir la rétroaction des gens sur les pages Canada.ca. Le Bureau de la transformation numérique (BTN) a travaillé avec les acteurs suivants :  
* Santé Canada/Agence de la santé publique du Canada (ASPC);  
* Éditeur principal;
* Bureau du Conseil privé.  

Le widget de rétroaction sur la page est une simple question qui se trouve au bas de celle-ci, où se trouve habituellement le widget « Signaler un problème ». Il s’agit de, « Avez-vous trouvé ce que vous cherchiez? » Les utilisateurs peuvent répondre par oui ou par non. S’ils répondent non, ils ont la possibilité de fournir plus de détails.

Ce widget simple est un outil puissant pour les propriétaires de contenu. Il leur permet de surveiller passivement l’efficacité de leur contenu. Il offre en outre la possibilité de vérifier régulièrement si le contenu fonctionne comme prévu et, si ce n’est pas le cas, pourquoi. 

Le 11 mai, nous avons ajouté le widget au bas de deux pages liées à la COVID 19 :
* [Symptômes et traitement](https://www.canada.ca/fr/sante-publique/services/maladies/2019-nouveau-coronavirus/symptomes.html) 
* [Prévention et risques](https://www.canada.ca/fr/sante-publique/services/maladies/2019-nouveau-coronavirus/prevention-risques.html)  

Notre objectif pour cette étude pilote était ce qui suit :

* mettre à l’essai une nouvelle approche pour la recherche en conception et la mesure de la réussite des tâches;
* découvrir si nous recevrions plus de commentaires utilisables qu’avec le widget « Signaler un problème »;
* cerner les problèmes de convivialité; 
* éclairer les améliorations itératives du contenu;  
* faire des expériences avec l’apprentissage automatique et le traitement du langage naturel pour aider à trier les commentaires.

## Widget de rétroaction

Service Canada et l’éditeur principal ont conçu le widget. En l’intégrant dans les pages, les ministères peuvent recueillir les commentaires qualitatifs et quantitatifs des Canadiens.

<figure>
<img class="img-responsive border" alt="A long description can be found after the image."
src="/images/feedback-1.png" width="700">
</figure>
<details>
<summary>Page Feedback Widget</summary>
<p>Widget displays the question: "Did you find what you were looking for?" and offers yes and no options.</p>
</details>

<br><figure>
<img class="img-responsive border" alt="A long description can be found after the image."
src="/images/feedback-2.png" width="700">
</figure>
<details>
<summary>Next screen of Page Feedback Widget.</summary>
 <p>When users select "no," they are asked "What was wrong?" and given the following options:</p>
 <ul>
<li>The answer I need is missing</li>
<li>The information isn't clear</li>
<li>I'm not in the right place</li>
<li>Something is broken or incorrect</li>
<li>Other reason</li>
 </ul>
<p>Selecting "other reason" displays a free text field where they can provide more details, with direction not to include any personal information.</p>
</details>
<br>

## Traitement de la rétroaction

Adobe Analytics traite les données quantitatives, c’est-à-dire le nombre de « oui » par rapport au nombre de « non », et les réponses prédéfinies pour ce qui n’allait pas. Pour l’étude pilote, la rétroaction textuelle était envoyée à un compte de courriel générique de Santé Canada. Félicitations à Santé Canada et à l’ASPC pour avoir passé en revue la rétroaction et d’en avoir fait l’analyse.

Depuis ce projet pilote, nous avons mis au point un processus qui permet d’extraire la rétroaction textuelle directement vers une base de données. Nous avons fait des expériences avec l’apprentissage automatique pour la classer automatiquement. Nous avons également créé une interface Web pour aider les ministères à passer en revue la rétroaction afin d’en dégager des tendances et des idées.

L’examen de la rétroaction textuelle peut demander beaucoup de temps, si bien que plus nous pouvons compter sur l’automatisation des tâches manuelles associées à ce travail, plus il sera facile d’envisager un déploiement plus vaste du widget sur l’ensemble du site Canada.ca.

## Protection des renseignements personnels

Nous savions qu’il existait une possibilité que nous recevions des renseignements personnels non sollicités, même si le widget recommande aux gens de ne pas en inclure. Pour régler ce problème, nous avons demandé conseil aux organisations suivantes :
* Division de la gestion de la protection des renseignements personnels, Santé Canada;
* Division de la gestion de la sécurité nationale, Santé Canada;
* Sécurité de la TI, Santé Canada.
 
À la lumière des conseils que nous avons reçus, Santé Canada a créé un processus pour retirer les renseignements personnels présents dans la rétroaction. Il a été ainsi possible d’éviter un autre élément du traitement manuel. Plus le nombre d’étapes automatisées sera grand, plus les équipes auront le temps de se concentrer sur les améliorations.

## Ce que nous avons constaté

En date du 10 juin, il y avait 5083 réponses au widget que nous avions ajouté aux deux pages du projet pilote, soit une moyenne de 164 réponses par jour.

Lorsque les gens ont répondu qu’ils n’avaient pas trouvé ce qu’ils cherchaient, leurs réponses concernant ce qui n’allait pas nous ont donné une idée des principaux problèmes de convivialité sur les pages.

<br><figure>
<img class="img-responsive border" alt="A long description can be found after the image."
src="/images/Feedback-graph-1.png" width="700">
</figure>
<details>
<summary>Next screen of Page Feedback Widget.</summary>
 <p>When users select "no," they are asked "What was wrong?" and given the following options:</p>
 <ul>
<li>The answer I need is missing</li>
<li>The information isn't clear</li>
<li>I'm not in the right place</li>
<li>Something is broken or incorrect</li>
<li>Other reason</li>
 </ul>
<p>Selecting "other reason" displays a free text field where they can provide more details, with direction not to include any personal information.</p>
</details>
<br>

Sur les 1015 personnes qui ont répondu à « ce qui n’allait pas », 782 (77 %) ont utilisé la zone de texte pour fournir plus de détails dans leurs propres mots sur ce qui ne fonctionnait pas.

Grâce à cette rétroaction, nous avons commencé à avoir une meilleure idée des éléments qui causaient des problèmes aux gens pendant leur visite. Les spécialistes du contenu ont ensuite examiné la rétroaction pour en saisir l’intention et les causes détaillées de la frustration.

<br><figure>
<img class="img-responsive border" alt="A long description can be found after the image."
src="/images/feedback-graph-2.png" width="700">
</figure>
<details>
<summary>Next screen of Page Feedback Widget.</summary>
 <p>When users select "no," they are asked "What was wrong?" and given the following options:</p>
 <ul>
<li>The answer I need is missing</li>
<li>The information isn't clear</li>
<li>I'm not in the right place</li>
<li>Something is broken or incorrect</li>
<li>Other reason</li>
 </ul>
<p>Selecting "other reason" displays a free text field where they can provide more details, with direction not to include any personal information.</p>
</details>
<br>

Ce détail a permis à Santé Canada et à l’ASPC de réaliser ce qui suit : 
* répartir les efforts en fonction de la fréquence à laquelle des commentaires semblables revenaient;
* déterminer les principaux points à améliorer;
* cerner les lacunes potentielles dans le contenu;
* constater si une page contenait des problèmes généraux à évaluer.

Par exemple, nous avons remarqué un grand pourcentage de commentaires liés à des symptômes moins courants de la COVID 19 qui n’étaient pas énumérés sur la page des symptômes. Cet aperçu a fourni des données probantes à l’appui de l’ajout de ces symptômes à la liste.

## Leçons essentielles apprises

* La zone de texte permet d’obtenir une rétroaction significative des personnes qui est directement liée au contenu et à ce qu’elles cherchent.
* La rétroaction textuelle permet aux équipes Web de cerner les termes utilisés par les Canadiens afin d’appuyer l’utilisation d’un langage clair. 
* L’intégration du widget de rétroaction dans la page permet de créer une expérience harmonieuse pour les gens.
* Sur les pages très achalandées, deux semaines semblaient suffisantes pour déterminer les tendances et les points à améliorer.
* Le widget est une méthode rapide et rentable pour recueillir des observations sur le contenu.
* L’outil aide à normaliser la mesure de l’efficacité de votre contenu et la capacité d’y apporter des améliorations itératives après sa publication.
* La nature continue du widget permet aux équipes, grâce à la surveillance des changements dans le type de rétroaction qu’elles reçoivent, de constater immédiatement les effets des améliorations apportées.    

## Mot de la fin

Pour finir, le but de la rétroaction est d’améliorer les services Web afin que notre contenu puisse mieux répondre aux besoins des Canadiens. Le widget de rétroaction sur la page est un outil utile qui fournit aux équipes du Web, des programmes et des politiques des renseignements précieux pour la prestation de services. Les leçons apprises peuvent nous aider à appuyer l’orientation et les recommandations relatives au contenu.

### Prochaines étapes de ce projet pilote

* Mettre le widget à l’essai sur d’autres pages à l’intérieur et à l’extérieur de l’outil AEM (Adobe Experience Manager)
* Parfaire certaines fonctionnalités du widget
* Continuer d’améliorer nos processus d’apprentissage automatique
* Élaborer des « tableaux de bord » pour avoir un aperçu des tendances et des problèmes
* Travailler à un déploiement plus large de l’outil

Enfin, un grand merci à nos partenaires pour ce projet pilote.

## Pour en savoir davantage

* [Increase the feedback - Gerry McGovern](https://medium.com/@gerrymcgovern/increase-the-feedback-3a0d4c904762) (en anglais seulement)

## Communiquez avec le Bureau de la transformation numérique du Secrétariat du Conseil du Trésor 
* Courriel : [dto.btn@tbs-sct.gc.ca](mailto:dto.btn@tbs-sct.gc.ca)
* Twitter :  #Canadapointca (français) / #Canadadotca (anglais)
* Slack : [http://design-GC-conception.slack.com](https://design-gc-conception.slack.com/join/shared_invite/enQtODE1OTc5Mzg5NzQ4LWQ3MjZjMTdjMjk2ZTZmMTJjYWQ3ZmRiNDYwYjRmN2NjYzQyNjFlNDBlY2FkNWE1ODg2YjExY2QwZmVjN2MwMGM)
