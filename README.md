# ExecutionExtraction-Uipath
Le projet consiste à développer une solution automatisée qui permet d’extraire les informations relatives aux exécutions depuis l’orchestrator. L’objectif de ce process est de collecter et de filtrer les données des éxecutions pour fournir une visibilité en temps réel sur l’état des processus en cours

# Description général du process:
Le but de ce robot est d’extracter les éxecutions de chaque process et filtrer les données extractés afin
d’avoir un rapport en détails avec le nombre total des cas « successful » et « Failed » que ça soit businees
ou System.
Le processus qui sera développé effectuera les actions suivantes :
• Récupérer le fichier input qui contient les files d’attente depuis de mail.
• Accéder à l’orchestrator et s’authetifier.
• Rechercher la file d’attente souhaitée.
• Exporter les transactions de chaque file d’attente.
• Filtrer les colonnes du fichier extracté selon les filtres demandés.
• Extraire le nombre des lignes trouvés après le filtrage
• Génération du rapport avec tous les détails pour chaque process
• Envoyer par mail le rapport généré.
