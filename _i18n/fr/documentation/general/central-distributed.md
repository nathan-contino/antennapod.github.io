Il existe essentiellement deux façons de créer une application de podcast :

1. **Central** : Il y a un serveur central (géré par la société qui développe
l'application) qui vérifie les nouveaux épisodes et vous les propose ensuite.
1. **Distribué** : L'application elle-même vérifie les nouveaux épisodes,
directement auprès des éditeurs de podcasts.

AntennaPod utilise la méthode numéro 2. Elle a à la fois des avantages et des
inconvénients :

- Comme l’application recherche les nouveaux épisodes, les créateurs
d’applications (comme nous) n’ont pas besoin de maintenir un serveur central.
Cela permet d'économiser beaucoup de temps et d'efforts. Cela permet également
d’économiser beaucoup d’argent, ce qui signifie que nous n’avons pas besoin de
compter sur les publicités ou sur de grosses sommes de dons.
- Comme l'application ne dépend pas d'un serveur central pour collecter les
nouveaux épisodes, AntennaPod continuera à fonctionner indépendamment de ce
que nous faisons de notre côté. En utilisant la méthode centrale, si la société
ferme son serveur pour une raison quelconque, l'application cessera de
fonctionner.
- En tant que développeurs d'applications, nous ne pouvons pas savoir à quels
podcasts vous êtes abonné, quels épisodes vous écoutez, ni même à quelle heure
vous le faites. Les éditeurs d'applications disposant d'un serveur central
collectent ces données, au détriment de votre vie privée.
- Certains éditeurs proposent des flux privés, offrant un accès anticipé, un
contenu spécial ou des épisodes sans publicité. Ces flux nécessitent un nom
d'utilisateur et un mot de passe, qu'AntennaPod donne directement à l'hôte du
podcast lorsqu'il le demande. Souvent, les services centralisés ne permettent
tout simplement pas d'ajouter des flux privés. Et s'ils le font, cela peut
nécessiter l'envoi de vos informations d'identification aux fabricants de
l'application.
- Ne disposant pas d'un point d'accès central, qui permettrait aux développeurs
d'applications de supprimer les podcasts de leur serveur, il n'y a aucun
risque de censure.
- D'autre part, un modèle distribué signifie que vous ne recevrez de nouveaux
épisodes que lorsque vous actualiserez un podcast. Dans AntennaPod, cette
actualisation a lieu par défaut toutes les 12 heures, mais vous pouvez la
modifier pour qu'elle soit plus ou moins fréquente et vous pouvez toujours
vérifier manuellement la présence de nouveaux épisodes. Un serveur central peut
vérifier les nouveaux épisodes très fréquemment ou même être informé par les
hôtes de podcasts en temps réel. Ainsi, les applications peuvent également être
informées des nouveaux épisodes beaucoup plus rapidement, sans avoir à vérifier
régulièrement tous les podcasts auxquels vous êtes abonné.
- AntennaPod ne peut pas non plus vous proposer les épisodes qui ont été
supprimés par l'éditeur du podcast, par exemple parce qu'il ne conserve que
les 10 épisodes les plus récents en ligne. Les applications qui s'appuient sur
un serveur central pourraient recevoir les épisodes les plus anciens, même s'ils
ont disparu du flux RSS.
