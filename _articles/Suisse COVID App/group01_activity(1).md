---
layout: activity
key: Suisse_COVID_app
title: Se faire vacciner Covid-19
tags: []
toc:
- "Situation actuelle"
- "Analyse des données"
- "Recommandations"
- "Bibliographie"
---

### Situation actuelle
La vaccination est actuellement ouverte aux personnes âgées de plus 16 ans résidant à Genève ou frontalier souscrivant une assurance maladie. Les personnes âgées de plus de 44 ans sont prioritaires dans l’obtention d’un rendez-vous, puis c’est le système de « premier inscrit – premier servi ». Ce service est gratuit (prise en charge par l’assurance maladie).

La prise de rendez-vous pour tous les centres se fait par le site web de l’état de Genève : ge.ch.
 
Les vaccinations se font dans des centres spécialisés. Il y a actuellement 12 centres à Genève dont deux centres pilotes en collaboration avec des pharmacies. Il y a actuellement 10 centres à Genève et deux centres pilotes en collaboration avec des pharmacies qui est réservé pour les personnes les plus vulnérable en priorité.

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td> 
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td> 
    <td>94</td>
  </tr>
</table>

#### Règles de gouvernance
#### Responsables et autres acteurs
**Office fédéral de la santé publique**
- Gestion des statistiques Covid-19 pour toute la Suisse
- Gestion des statistiques SwissCovid
- Gestion des statistiques Vaccinations pour toute la Suisse


**Ge.ch (Site web cantonal)**
- Gestion des statistiques Vaccinations pour le canton de Genève
- Prise de rendez-vous pour se faire vacciner pour le canton de Genève

**Centres de vaccination**
- Vaccine les personnes

**Pharmacie cantonale**
- Commande les doses de vaccins

#### Résultats et utilisation
Les données qui sont collectées par l’OFSP sont entièrement anonymisés. Elles vont ensuite être affiché sur le Dashboard (Source 2). Les statistiques de Genève sont disponibles sur le site (Source 4).
Ses données constituent une base pour prendre des décisions, mais il s’agit seulement d’un élément parmi d’autres.

### Analyse des données

#### Source
Les données sont collectées par les centres de vaccinations et enregistrées sur ge.ch (Pour le canton de Genève) avec le web application One Doc. Il s’agit d’un site web pour prendre des rendez-vous avec des professionnels de la santé en Suisse. Elle est directement intégrée à ge.ch. 

La base logistique de l’armée (BLA), qui s’occupe du domaine de la santé lors de situation extraordinaire d’ampleur national (pandémie et évènements majeurs), qui fournit des informations à l’OFSP.

Lorsque l’OFSP récupère les données, il n’y a pas uniquement une personne qui traite les données, mais un groupe de travail qui gèrent l’ensemble des données liées à la pandémie. Les analyses qui sont effectuées avec les données de vaccination sont réalisées avec le logiciel R. 

#### Type
<table>
  <tr>
    <th>Responsable</th>
    <th>Données</th> 
  </tr>
  <tr>
    <td>Office fédéral de la santé publique (OSPF)</td>
    <td>
Vaccination effectuée :
<br />
- Âge 
<br />
- Canton de résidence 
<br />
- Motif de vaccination
<br />
- Type d’institution administrant le vaccin
<br />
- Type de vaccin
<br />
- Date d’administration
<br />
- Nombre de doses
    </td> 
  </tr>
  <tr>
    <td>Ge.ch, One Doc </td>
    <td>
Rendez-vous Vaccination :
<br />
-	Prénom
<br />
-	Nom
<br />
-	Date de Naissance
<br />
-	Numéro d’assurance
<br />
-	Risque de santé
<br />
-	Centres de vaccinations de préférence
<br />
-	Genre
<br />
-	Adresse électronique
<br />
-	Numéro de téléphone
    </td> 
    <tr>
    <td>Centres de vaccinations</td>
    <td>
Rendez-vous Vaccination
<br />
-	Prénom
<br />
-	Nom
<br />
-	Date de Naissance
    </td>
    </tr>
    <tr>
    <td>Pharmacie cantonale</td>
    <td>
Nombre de doses administrées par chaque centre de vaccination
    </td>
    </tr>
</table>

#### Raison
C’est le rôle du conseil fédéral, pendant cette période de crise, de prendre les meilleures décisions pour protéger la population Suisse. Pour ce faire, le conseil fédéral s’aide d’avis d’expert et des données sur général sur la situation du Covid-19 (nombre de cas, nombre de personnes vaccinées, etc.). Les décisions prises sont transmises à la population lors de conférences de presse hebdomadaires. 

#### Règles et dispositon
One doc est d’un logiciel privé, les données sont confidentielles et sont partagées uniquement entre le patient et le professionnel de la santé (Source 5). L’ensemble de leurs solutions sont hébergées en suisse, ils sont donc soumis à la RGPD. Le site possède aussi le label « Swiss made software » qui certifie la qualité du service (Source 8).

Le logiciel R est sous licence GNU GPL. C’est-à-dire qu’il est libre à la modification et le code source est disponible, mais toutes modifications doivent être partagé à la communauté (Source 7).

### Recommandations
Le travail effectué par l’OSPF est très important pour tenir la population Suisse informée de la progression de la pandémie. Cela permet aussi aux personnes en charge des décisions de s’aiguiller. La présentation et la transformation des données est de qualité et détaillée. Nous ne savons pas comment l’épidémie évoluera, mais les nouvelles souches pourraient présenter un défi majeur pour la vaccination.
La prise en charge pour la vaccination est simple et efficace (ge.ch). Le fait qu’elle soit gratuite est un avantage considérable. Nous recommandons à tous de prendre rendez-vous à tous car il y a un temps d’attente.

### Bibliographie
1.	ge.ch. « Se faire vacciner ». Consulté le 31 mai 2021. https://www.ge.ch/node/23333.
2.	« COVID-⁠19 Suisse | Coronavirus | Dashboard ». Consulté le 1 juin 2021. https://www.covid19.admin.ch/fr/overview.
3.	OFSP, Office fédéral de la santé publique. « Coronavirus : vaccin ». Consulté le 1 juin 2021. https://www.bag.admin.ch/bag/fr/home/krankheiten/ausbrueche-epidemien-pandemien/aktuelle-ausbrueche-epidemien/novel-cov/impfen.html.
4.	« COVID19 à Genève. Données cantonales ». Consulté le 2 juin 2021. https://infocovid.smc.unige.ch/.
5.	OneDoc. « Terms and Conditions ». Consulté le 7 juin 2021. https://www.onedoc.ch.
6.	« Base logistique de l’armée BLA ». Consulté le 7 juin 2021. https://www.vtg.admin.ch/fr/organisation/bla.html.
7.	« Licence publique générale GNU ». In Wikipédia, 14 avril 2021. https://fr.wikipedia.org/w/index.php?title=Licence_publique_g%C3%A9n%C3%A9rale_GNU&oldid=181899893.
8.	OneDoc. « La technologie au service du système de santé Suisse ». Consulté le 7 juin 2021. https://about.onedoc.ch/fr/.
9.	Interview Grégoire Gogniat, porte-parole OFSP, réalisé le 9 mai 2021 [en annexe]
10.	Interview Responsable centre vaccination, réalisé le 23 mai 2021 [en annexe]

