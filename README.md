# JEE-Activite-Pratique-7
L'objectif de cette activité pratique est d'apprendre a utilisé Keycloak.

# Travail à faire
Partie 1 : 

  -Télécharger Keycloak 23;

  -Démarrer Keycloak;

  -Créer un compte Admin;

  -Créer une Realm;

  -Créer un client à sécuriser;

  -Créer des utilisateurs;

  -Créer des rôles;

  -Affecter les rôles aux utilisateurs;

  -Avec PostMan :

  -Tester l'authentification avec le mot de passe;

  -Analyser les contenus des deux JWT Access Token et Refresh Token;

  -Tester l'authentification avec le Refresh Token;

  -Tester l'authentification avec Client ID et Client Secret;

  -Changer les paramètres des Tokens Access Token et Refresh Token.

  -Ressource (Les 49 premières minutes de la vidéo) : 

      -https://www.youtube.com/watch?v=vNKVm2vTL2Q

Partie 2 : Développer et sécuriser une application basée sur les micro-services en utilsant Oauth 2, OIDC, Keycloak :

  -Invenroty-service;

  -Frontend Tymeleaf;

  -Frontend Angular.

  -Ressources :

      -https://www.youtube.com/watch?v=zI0Xr-O3sqM&authuser=0

      -https://www.youtube.com/watch?v=YbCooJDUtOM&authuser=0

      -https://www.youtube.com/watch?v=aSPWnRSteTk&authuser=0

      -https://www.youtube.com/watch?v=NnzoM08CvgA&authuser=0

      -https://www.youtube.com/watch?v=LrqRjokK5dY&authuser=0

![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/d1360f65-74f3-4b6f-b5d1-ec71573ea814)

Keycloak et OpenID Connect (OIDC) sont des technologies liées à l'authentification et à l'autorisation dans le domaine de la gestion des identités. 

Keycloak est une solution open source de gestion des identités et des accès (IAM). Elle offre des fonctionnalités telles que l'authentification unique (Single Sign-On ou SSO), la gestion des sessions, l'autorisation, la fédération d'identités, et bien plus encore.

Caractéristiques clés :

      -SSO : Permet à un utilisateur de s'authentifier une seule fois pour accéder à plusieurs applications sans avoir à se reconnecter.

      -Gestion des utilisateurs : Création, suppression, mise à jour des comptes utilisateur.

      -Fédération : Intégration avec d'autres systèmes d'authentification et d'autorisation.

      -OAuth 2.0 et OpenID Connect : Protocoles standard pour l'authentification et l'autorisation.

# Utilisation courante : Keycloak est souvent utilisé comme serveur d'authentification centralisé pour sécuriser les applications web, les services API et d'autres ressources.

OpenID Connect est une extension du protocole OAuth 2.0. Il fournit une couche d'authentification supplémentaire au-dessus d'Oauth 2.0, en ajoutant des fonctionnalités d'authentification pour les applications web et mobiles.

Caractéristiques clés :

      -Authentification sécurisée : Permet aux utilisateurs de s'authentifier de manière sécurisée sur différentes applications.

      -Fourniture d'informations utilisateur : Permet à une application d'obtenir des informations sur l'utilisateur authentifié.

      -Émission de tokens d'identité : Utilise des tokens JWT (JSON Web Tokens) pour transmettre des informations d'identité de manière sécurisée.

# Utilisation courante : OpenID Connect est largement utilisé dans le développement d'applications web et mobiles sécurisées où l'authentification des utilisateurs est cruciale.

# Partie 1:
Démarrer Keycloak
<img width="487" alt="711" src="https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/3953b87c-e645-4dbd-9cb7-270403a31b3d">

Création d'un compte admin
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/63b780ba-aa3f-4cdc-a1ce-1a9185e36cc5)
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/c142e940-78cd-4c18-8478-a6f2dee5d338)

Création d'une Realm
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/616482a6-e3e7-47e1-a700-c51112053ded)

Création d'un client à sécuriser
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/ddd4e2d9-1230-4ddb-836f-5ea44bd8b2a9)

Création des utilisateurs
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/4f0c7e00-8e13-4ad2-8e3a-8dba70a28be0)

Création des rôles
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/419e139b-e091-4cd8-95b3-2a8c4c74aca2)

Affectation des rôles aux utilisateurs
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/6f0428f8-58bf-45fc-8c9c-597d0f7f84a8)

Postman
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/f40a5991-c81f-4928-93ce-0219ebca9ebe)

Methode1: (avec LoginEtPassword)
<img width="960" alt="5" src="https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/bc9d5b24-d12e-44e2-b0a0-813112c2d0d8">
Methode2: (avec le refreshToken)
<img width="960" alt="6" src="https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/de4e9feb-3e5c-4aa3-8ab8-3eee02c23815">
Methode3: (avec ClientSecret)
<img width="960" alt="7" src="https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/245761e0-11d6-470e-9bd7-5711f2872b0d">
<img width="960" alt="8" src="https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/da23d4fe-1b47-4762-b50a-a54156789ac4">

# Partie 2:
# Frontend avec thymeleaf
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/5eec8bcf-f7cb-40d9-9ed6-1640f7aaff15)

Github
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/fc9f148c-c0dd-4f67-9856-10178e30de95)

Google
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/bfe2322b-1e4e-499c-83b2-4498f0908194)

![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/8d9b95dc-ddd1-456d-8ab2-640031a59587)

Login
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/260bbc12-9dbb-405f-b66a-250470835788)

Authentification avec github
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/f8c4a2f9-0ab6-4acb-8b50-663d5aba35b9)

Authentification avec google
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/e08084b9-1fe0-4fbe-aefe-1b6522904d74)

Authentification avec keycloak
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/f57878c6-a673-49e8-ab3a-f31eb7d8138b)

![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/75dbc3a2-e1f8-40cb-bd60-19f3c04724a9)

![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/a6ff87f6-f3b4-471c-97f2-9b7e598b0137)

Seuls les utilisateurs qui ont le role admin qui peuvent acceder
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/18abf42b-2974-45fe-a617-1473eae3d7b3)

# Frontend avec Angular
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/6241f34f-3b67-49b5-8427-9d27af91213f)

Login
![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/74b5db85-1ec0-498e-a6f4-cc98c5925adb)

![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/0627d821-969d-4161-bef2-a379064b4b71)

![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/d41efff3-2b1f-44c0-890a-20e764e0a728)

![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/b497d4ca-a94b-4f3a-a1e8-d461afb514d8)

![image](https://github.com/Moujoudrana/Atelier7_5JEE/assets/93864104/6ede7b9d-d2b5-4c1a-81cb-f98ace982443)

# Partie docker

![image](https://github.com/Moujoudrana/Atelier7_5JEEE/assets/93864104/b5f14c34-e295-4458-af27-be572b96782a)
