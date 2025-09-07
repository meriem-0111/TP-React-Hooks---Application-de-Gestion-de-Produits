# Exercice 1 :
Objectif probable : Gérer l'état des produits (par exemple, une liste de produits, un formulaire d'ajout/modification) et utiliser useEffect pour des effets de bord (par exemple, charger les produits depuis une API au montage du composant).
Pistes :
useState : Pour stocker la liste des produits, les valeurs des champs d'un formulaire, etc.
useEffect : Pour faire un appel à une API (fetch ou Axios) pour récupérer les données des produits. Gérer le chargement (état de chargement) et les erreurs

Capture Code Source 
![image](https://github.com/user-attachments/assets/1b4a481e-458f-4f04-89a9-0adc78972789)

Exercice 2 :

Context et Internationalisation (useContext)

Objectif probable : Utiliser le Context pour partager des données entre plusieurs composants sans avoir à les passer manuellement via les props. Gérer l'internationalisation (par exemple, afficher le nom des produits dans différentes langues).
Pistes :
createContext : Pour créer un contexte (par exemple, un contexte pour la langue).
useContext : Pour accéder à la valeur du contexte dans les composants.
Créer un objet contenant les traductions pour chaque langue.

Capture Code Source
![image](https://github.com/user-attachments/assets/c6b25c4e-1f60-41fa-890f-1dd63a8cd71c)

Exercice 3 :
Objectif probable : Créer des hooks réutilisables pour encapsuler une logique spécifique (par exemple, la gestion d'un formulaire, la récupération de données depuis une API).
Pistes :
Créer une fonction commençant par use (ex : useFetch, useForm).
Utiliser les hooks natifs (useState, useEffect, etc.) à l'intérieur du hook personnalisé

Capture Code source
![image](https://github.com/user-attachments/assets/8e1957f9-f09b-4bd5-ac57-0641d1a3166a)

Exercice 4 :

Gestion Asynchrone et Pagination

Objectif probable : Gérer les requêtes asynchrones avec une gestion du chargement et des erreurs, et implémenter la pagination pour afficher les produits par pages.
Pistes :
Utiliser async/await ou des promesses pour les requêtes.
Gérer l'état de chargement et les erreurs.
Utiliser des paramètres de requête pour la pagination (par exemple, page, limit).

Capture Code Source : 
![image](https://github.com/user-attachments/assets/754047a2-2b38-48ce-90ff-cd7874c6580a)



