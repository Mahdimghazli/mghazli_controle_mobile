# mghazli_controle_mobile
Ce projet utilisant PokeAPI pour construire l’API RESTful.
PokeAPI fournit une interface API RESTful pour les objets très détaillés construits à partir de milliers de lignes de données liées à Pokémon.
Le développement du projet avec ViewBinding, ViewModel avec LiveData, Dagger2, Retrofit2 avec RxJava3, Room Database, MaterialCardView avec ShapeableOverlay Style et ProgressView basé sur l’architecture MVVM.
Architectures et composants : 
MVVM Architecture (Model - View - ViewModel)
Modèle de dépôt
ViewModel - Permet aux données de survivre aux modifications de configuration telles que les rotations d’écran.
LiveData - Une classe de titulaire de données observable.
ViewBinding - Une fonctionnalité qui vous permet d’écrire plus facilement du code qui interagit avec les vues.
SwipeRefreshLayout - Implémentez le balayage pour actualiser l’interface utilisateur.
The Room persistence - Fournit une couche d’abstraction sur SQLite pour permettre un accès plus robuste à la base de données tout en exploitant toute la puissance de SQLite
