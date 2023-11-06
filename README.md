# CAHIER DE CHARGE FONCTIONNEL
# Conception de Facebook : Réseau social global

Réalisé par : BOULAMAAT Amina  
              AAFIF Khawla  
Suivé par : Mr. Ayoub Charef  
Année Universitaire : 2023-2024

### 1.Problématique et description de l’existant :
La problématique consiste à créer une plateforme de médias sociaux permettant aux utilisateurs de se connecter,de partager des publications, de commenter, de gérer leurs paramètres, d'engager des conversations, 
de créer des groupes, des pages et d'interagir en aimant des publications.



### Cas d'Utilisation 1 : Profile
- **Description :** Les utilisateurs peuvent créer, modifier et visualiser leur profil.

**Scénarios d'Utilisation :**
1. L'utilisateur s'inscrit sur la plateforme en fournissant un nom d'utilisateur, une adresse e-mail et un mot de passe.
2. Une fois inscrit, l'utilisateur peut remplir son profil en ajoutant des informations telles que sa photo de profil, sa date de naissance, sa situation amoureuse, sa ville, etc.
3. L'utilisateur peut modifier son profil à tout moment pour mettre à jour ses informations personnelles.
4. Les autres utilisateurs peuvent consulter le profil d'un utilisateur pour voir ses informations publiques.

### Cas d'Utilisation 2 : Publication
- **Description :** Les utilisateurs peuvent créer et publier du contenu sur leur mur.

**Scénarios d'Utilisation :**
1. Un utilisateur peut rédiger un nouveau message ou publier une photo sur son propre mur.
2. L'utilisateur peut ajouter du texte, des images, des vidéos, des liens, etc., à sa publication.
3. Les publications peuvent être configurées pour être visibles par tout le monde, uniquement par les amis de l'utilisateur, ou de manière plus restreinte.
4. Les publications peuvent être commentées et "aimées" par d'autres utilisateurs.

### Cas d'Utilisation 3 : Commentaire
- **Description :** Les utilisateurs peuvent commenter les publications.

**Scénarios d'Utilisation :**
1. Les utilisateurs peuvent laisser des commentaires sur les publications d'autres utilisateurs.
2. Les commentaires peuvent également contenir des médias, comme des images ou des liens.
3. Les commentaires sont visibles par les autres utilisateurs qui consultent la publication.
4. Les utilisateurs peuvent "aimer" un commentaire.

### Cas d'Utilisation 4 : Paramètre
- **Description :** Les utilisateurs peuvent gérer les paramètres de leur compte.

**Scénarios d'Utilisation :**
1. Les utilisateurs peuvent gérer leurs préférences de confidentialité, définir qui peut voir leurs publications, commentaires, etc.
2. Ils peuvent changer leur mot de passe ou leur adresse e-mail associée au compte.
3. Les utilisateurs peuvent gérer les notifications, telles que les alertes par e-mail ou mobile.
4. Ils peuvent également choisir leurs préférences de notification pour les publications, les commentaires, les messages, etc.

### Cas d'Utilisation 5 : Conversation
- **Description :** Les utilisateurs peuvent échanger des messages privés.

**Scénarios d'Utilisation :**
1. Un utilisateur peut commencer une conversation privée avec un autre utilisateur en recherchant son nom d'utilisateur.
2. Les utilisateurs peuvent envoyer des messages texte, des images et des fichiers dans la conversation.
3. Les conversations peuvent être individuelles ou en groupe.
4. Les utilisateurs peuvent archiver ou supprimer des conversations.

### Cas d'Utilisation 6 : Groupe
- **Description :** Les utilisateurs peuvent créer et rejoindre des groupes.

**Scénarios d'Utilisation :**
1. Les utilisateurs peuvent créer un groupe sur un sujet d'intérêt particulier, définir la description du groupe, et inviter d'autres utilisateurs à le rejoindre.
2. Les membres d'un groupe peuvent publier du contenu spécifique au groupe, comme des discussions, des images et des liens.
3. Les groupes peuvent être publics, privés ou secrets, avec des niveaux d'accès différents.
4. Les administrateurs de groupe peuvent gérer les membres et le contenu du groupe.

### Cas d'Utilisation 7 : Page
- **Description :** Les entreprises et organisations peuvent créer des pages.

**Scénarios d'Utilisation :**
1. Les entreprises ou organisations peuvent créer une page pour représenter leur entité sur la plateforme.
2. Les pages peuvent inclure des informations telles que la description, l'emplacement, les coordonnées, des images, des vidéos, etc.
3. Les administrateurs de la page peuvent publier du contenu au nom de l'entreprise/organisation.
4. Les utilisateurs peuvent "aimer" une page pour recevoir des mises à jour de celle-ci.

### Cas d'Utilisation 8 : Like
- **Description :** Les utilisateurs peuvent exprimer leur appréciation en cliquant sur "J'aime" sur les publications.

**Scénarios d'Utilisation :**
1. Les utilisateurs peuvent appuyer sur le bouton "J'aime" sous une publication pour montrer leur appréciation.
2. Les "J'aime" sont visibles par d'autres utilisateurs et peuvent être utilisés pour mesurer la popularité d'une publication.
3. Les utilisateurs peuvent également voir la liste des personnes qui ont aimé une publication.
4. Ils peuvent annuler leur "J'aime" s'ils le souhaitent.


Dans le cadre de la conception de Facebook, nous avons défini des entités clés, chacune avec ses propres champs caractéristiques.
Pour le profil utilisateur, nous avons des champs tels que le nom d'utilisateur, la photo de profil, la date de naissance, la situation amoureuse, la ville, et d'autres informations personnelles.
Les publications sur la plateforme incluent du contenu, des paramètres de confidentialité, la date et l'heure de publication, ainsi que l'auteur. Les commentaires sur les publications ont leur propre contenu, une horodatage, et un lien vers la publication à laquelle ils sont associés. Les paramètres du compte de l'utilisateur englobent les préférences de confidentialité, le mot de passe, l'adresse e-mail, et les préférences de notification.

Pour une conception complète, il est tout aussi important d'établir des relations entre ces entités. Par exemple, les profils d'utilisateurs sont liés aux publications et aux commentaires, permettant ainsi à un profil d'avoir plusieurs publications et commentaires associés. De même, une publication est associée à un auteur et peut contenir plusieurs commentaires. Les paramètres du compte sont liés au profil de l'utilisateur, et les conversations impliquent plusieurs participants et messages. En outre, les groupes ont des membres et des publications spécifiques au groupe, tandis que les pages sont gérées par un administrateur avec des publications associées. Enfin, le module "J'aime" est associé aux publications "aimées" par les utilisateurs.
