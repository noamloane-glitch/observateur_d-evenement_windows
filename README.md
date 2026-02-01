# Observateur_d-Evenement_Windows

Depuis un Windows Server j'ai créé une vue personnalisée avec Event Viewer

Cette vue s'appelle **DNS_surveillance**

Dans la fenêtre de la création d'une vue personnalisée :

- Logged : **Anytime**
- By log : **Applications and Services Logs**
- Event Level : Cocher : **Critical,Error,Warning,Information**
- By source : **DNS-Server-Service,DNS Client Events**
- EventID : **2,4,409,501,502,6001,6002**

On enregistre la vue et ensuite on l'exporte en format .xml 

Le fichier DNS_surveillance est en PJ