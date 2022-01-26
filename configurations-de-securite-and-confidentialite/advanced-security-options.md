# Options de sécurité avancées

Wasabi Wallet offre plusieurs options avancées qui amélioreront grandement la sécurité de vos fonds et de votre confidentialité.

### Privacy Mode (mode confidentiel)

Une fois activé, les informations sensibles sur les transactions et les portefeuilles sont cachées des observateurs physiques. Vous pouvez activer ou désactiver cette fonction en cliquant sur l'icône en forme d'œil dans l'en-tête de l'explorateur de portefeuille dans le coin supérieur droit.

* Le portefeuille demeure fonctionnel.
* Toute information que vous développez dans le portefeuille sera révélée, le privacy mode n'offre qu'une protection de surface.

### Lock Screen (écran de verrouillage)

Cette fonction vous permet de verrouiller votre portefeuille lorsqu'il est en cours d'exécution ou de l'empêcher d'être consulté. Il est déverrouillé à l'aide d'un NIP que vous spécifiez lors de l'activation de la fonctionnalité :

1. Dans l'onglet Settings, accédez à la section Lock Screen.
2. Choisissez et entrez un NIP numérique d'une longueur maximale de 10 chiffres dans la zone PIN, puis cliquez sur Set.

#### **Il existe deux façons de verrouiller votre écran :**

1. Appuyez sur Ctrl+L sur votre clavier.
2. Dans la barre de menu en haut à gauche, cliquez sur File, puis sur Lock Screen.

Cette fonctionnalité ne verrouille que l'interface, ce n'est pas un verrou à sécurité intégrée sur votre portefeuille. Toute personne connaissant le NIP ou les rouages de Wasabi peut contourner cette fonctionnalité.

### Connexion à votre propre **nœud**

La connexion à votre propre nœud vous permet d'en extraire des informations que Wasabi récupérerait normalement à partir de sources externes.  Utiliser Wasabi de cette façon devrait vous procurer une confidentialité accrue, puisque cela simplifie certains mécanismes complexes. C'est aussi votre moyen d'effectuer des transactions sans restrictions et d'éviter d'être fraudé. Il est important de noter que l'intégration des nœuds de Wasabi est encore à l'état expérimental.

#### **Dans le menu principal, allez dans Tools, puis Settings.**

Il existe trois manières différentes d'utiliser votre nœud Bitcoin avec Wasabi :

1. Si vous avez déjà un nœud complet sur votre ordinateur, Wasabi le détectera.
2. Vous pouvez vous connecter à un nœud à distance en spécifiant l'adresse IP du réseau local ou Tor onion.
   * Entrez l'adresse IP du nœud sous « Alternative Block Source for Main »
3. Vous pouvez démarrer Bitcoin Knots dans Wasabi Wallet pour commencer le téléchargement et faire tourner votre propre nœud sur votre ordinateur. Alors que les alternatives précédentes ne récupèrent que des blocs à partir de votre nœud complet, ce mode va bien au-delà de cela. Il utilise le nœud pour de multiples services, comme l'obtention des frais de réseau et l'utilisation de son bassin de transactions comme source de vérité pour recevoir des transactions non confirmées et détecter les doubles dépenses.
