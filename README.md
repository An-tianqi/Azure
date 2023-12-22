# Azure

Créer une Machine Virtuelle (VM) :

Si vous deviez héberger un site Web ou exécuter une application spécifique nécessitant un environnement Windows/Linux. La création d'une machine virtuelle dans Azure peut vous fournir l'environnement requis sans avoir besoin de matériel physique.

Vous pouvez commencer à créer et configurer votre VM sur le lien ci-dessous : https://portal.azure.com/#create/Microsoft.VirtualMachine-ARM


image


Par défaut, le paiement sera mensuel, vous pouvez aussi choisir de payer par heures en cochant cette case dans l'onglet De base.
J'ai choisi de développer mon application sur HTTP et HTTPS.



Configurer le stockage Blob :

Un scénario dans lequel votre application génère un grand nombre de fichiers journaux ou d’images qui doivent être stockés et accessibles en toute sécurité. Azure Blob Storage peut être utilisé pour stocker de telles données non structurées.

Pour ce faire, accédez au lien ci-dessous https://portal.azure.com/#view/HubsExtension/BrowseResource/resourceType/Microsoft.Stor age%2FStorageAccounts


image



Déployer une application Web :

Supposons que vous ayez développé une application Web et que vous ayez besoin d’une plateforme pour l’héberger. Azure App Services peut fournir une plateforme gérée pour déployer des applications Web sans gérer l'infrastructure sous-jacente.

Nous pouvons simplement le faire en utilisant l'extension Azure Tool sur vs code et cliquer sur le bouton + puis choisir votre configuration



Créer une base de données SQL :
   
Vous devez aussi développer une application qui nécessite un backend de base de données relationnelle. La création d'une base de données Azure SQL vous permet de disposer d'un service de base de données évolutif et géré.

Pour créer n'importe quel serveur MySQL sur Azure, vous pouvez simplement aller sur
https://portal.azure.com/#create/Microsoft.MySQLServer

Et puis sélectionnez la configuration que vous souhaitez, dans ce cas, j'utilise un serveur flexible


image


Implémentez un Azure Functions simple :

Vous avez un scénario dans lequel vous devez traiter des données ou répondre à des événements sans serveur dédié. Azure Functions vous permet d'écrire des fonctions basées sur des événements qui peuvent être déclenchées à la demande.

Pour créer une fonction simple, vous pouvez simplement aller dans la barre de recherche et taper Azure Function, cela vous dirigera vers cette page.



image



Mettre en place une ressource de réseautage :

Supposons que vous disposiez de plusieurs machines virtuelles ou services qui doivent communiquer en toute sécurité. La création d'un réseau virtuel dans Azure vous permet d'isoler et de gérer le trafic réseau entre les ressources.

Vous pouvez aller dans cet onglet et choisir d'ouvrir le port de votre application, choisir https http


image


Configurer la surveillance et la journalisation :

Imaginez avoir besoin d’informations sur les performances et la santé de vos ressources. Azure Monitor fournit une télémétrie et des journaux détaillés pour vous aider à diagnostiquer les problèmes et à optimiser les performances.

Pour vérifier l'état de votre application afin de vous aider à diagnostiquer les problèmes, vous pouvez simplement utiliser la fonction de surveillance du portail Azure pour les applications Web en direct et choisir votre application.


image



Kubernetes : 

Il pourrait automatise les tâches opérationnelles de gestion des conteneurs, avec des commandes intégrées pour déployer des applications, modifier des applications, faire évoluer les applications en fonction de l'évolution des besoins, surveiller les applications, etc., facilitant ainsi la gestion des applications.



image



Créez un groupe de ressources personnalisé :

Imaginez devoir organiser et gérer les ressources Azure associées. Les groupes de ressources dans Azure permettent de regrouper les ressources en fonction du cycle de vie, des autorisations ou d'autres critères.


image


