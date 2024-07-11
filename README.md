# Mission - Segmentez des clients d'un site e-commerce
## Comment allez vous procéder ?
Cette mission suit un scénario de projet professionnel.

Vous pouvez suivre les étapes pour vous aider à réaliser vos livrables. 

Avant de démarrer, nous vous conseillons de :
- lire toute la mission et ses documents liés ;
- prendre des notes sur ce que vous avez compris ;
- consulter les étapes pour vous guider ; 
- préparer une liste de questions pour votre première session de mentorat.

## Prêt à mener la mission ?
Vous êtes consultant pour [Olist](https://olist.com/), une entreprise brésilienne qui propose une solution de vente sur les marketplaces en ligne.

Votre rôle est d’accompagner Olist dans leur projet de monter une équipe Data et leur premier cas d’usage Data Science autour de la segmentation client.

Vous venez de rejoindre Olist dans un contexte de recrutement intensif afin de monter leur équipe Data. En effet, ils font d’abord appel à des consultants comme vous en renfort sur les sujets les plus critiques en attendant d'internaliser les compétences. Avant de réaliser la segmentation client, on vous attribue une première mission pour aider Fernanda, Lead Data Analyst chez Olist. 

>**De :** Fernanda
>**A :** Moi
>**Objet :** dashboard Customer Experience
>
>Bonjour,
>
>Bienvenue chez Olist ! Nous sommes ravis d’avoir du soutien en cette période de mise en place de notre écosystème Data.
>
>A ce sujet d’ailleurs, l’un de nos projets Data phares du moment est la construction et la maintenance de notre Dashboard au service des équipes Customer Experience. Nous y exposons les KPIs essentiels pour que les équipes puissent avoir de la visibilité sur les états, les villes, ou les vendeurs qui nécessitent un suivi de près de la part de notre service client.
>
>Nous sommes en train d’alimenter les résultats de ce Dashboard avec des requêtes qui interrogent la base de données SQL à laquelle tu as accès.
>
>C’est sur l’implémentation de certaines requêtes urgentes que tu peux nous donner un coup de main le temps qu’un nouveau Data Analyst rejoigne l’équipe pour prendre le relais.
>
>Je mets en PJ la liste de requêtes SQL que nous avons besoin d’intégrer au Dashboard. 
>
>Cordialement,
>Fernanda
>Lead Data Analyst chez Olist
>
>Pieces jointes:
>[Liste de requêtes SQL](https://course.oc-static.com/projects/DS_P5/Liste+de+requetes+SQL+pour+le+dashboard.pdf)

Après avoir étudié les éléments partagés par Fernanda vous vous mettez au travail.

## Quelques jours plus tard
Cette urgence résolue, vous pouvez enfin passer à votre mission principale : Olist souhaite que vous fournissiez à ses équipes d'e-commerce une segmentation des clients qu’elles pourront utiliser au quotidien pour leurs campagnes de communication.

Votre objectif est de comprendre les différents types d’utilisateurs grâce à leur comportement et à leurs données personnelles.

Vous devrez fournir à l’équipe Marketing une description actionable de votre segmentation et de sa logique sous-jacente pour une utilisation optimale, ainsi qu’une proposition de contrat de maintenance basée sur une analyse de la stabilité des segments au cours du temps.

### Les données
Pour cette mission, Olist vous fournit une [base de données](https://course.oc-static.com/projects/olist.db) anonymisée comportant des informations sur l’historique des commandes, les produits achetés, les commentaires de satisfaction, et la localisation des clients depuis janvier 2017.

Vous devez aider les équipes d’Olist à comprendre les différents types d'utilisateurs. Vous utiliserez donc des méthodes non supervisées pour regrouper des clients de profils similaires. Ces catégories pourront être utilisées par l’équipe Marketing pour mieux communiquer.

Vous créez donc un notebook et démarrez votre travail d’analyse exploratoire.

## 3 jours plus tard
Après quelques premières analyses, vous vous rendez compte qu'Olist ne vous a pas fourni beaucoup de données ; vous enquêtez donc auprès de l'entreprise pour obtenir quelques informations complémentaires, et vérifier que vous avez bien compris la mission. 

Voici sa réponse :
>**De :** João
>**A :** Moi
>**Objet :** re : segmentation des clients
>
>Bonjour, 
>
>Nous sommes confiants sur le fait que les données à disposition suffiront pour réaliser un premier clustering. Cela a déjà été fait par d’autres prestataires par le passé, avec encore moins de données.
>
>La segmentation proposée doit être exploitable et facile d’utilisation par notre équipe Marketing. Elle doit au minimum pouvoir différencier les bons et moins bons clients en termes de commandes et de satisfaction. Nous attendons bien sûr une segmentation sur l’ensemble des clients.
>
>Dans un deuxième temps, une fois le modèle de segmentation choisi, nous souhaiterions que vous nous fassiez une recommandation de fréquence à laquelle la segmentation doit être mise à jour pour rester pertinente, afin de pouvoir effectuer un devis de contrat de maintenance.
>
>Pour information, le code fourni doit respecter la convention PEP8, pour être utilisable par Olist. 
>
>À titre d'exemple, je joins à cet e-mail la segmentation RFM réalisée par votre prédécesseur il y a quelques années. Mais c’est uniquement à titre d’exemple, j'attends un travail plus approfondi de votre part dans le cadre de ce projet (i.e. RFM, satisfaction et autres possibilités).
>
>Bien à vous,
>João de l’équipe Marketing
>
>Pièce-jointe :
>![RFM chart](https://user.oc-static.com/upload/2023/03/21/16793895608947_Screenshot%202023-03-21%20at%2010.05.50.png "RFM chart")

Vous réalisez trois autres documents afin de préparer une réponse à Olist : 
- Un notebook avec des essais des différentes approches de modélisation 
- Un notebook de simulation pour déterminer la fréquence nécessaire de mise à jour du modèle de segmentation, afin que celui-ci reste pertinent 
- Une présentation pour un collègue afin d’obtenir ses retours sur votre approche

C’est parti pour cette dernière ligne droite ! 
