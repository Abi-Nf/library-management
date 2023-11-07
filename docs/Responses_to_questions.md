# Response to questions mentioned in consigns

2] b]
    i. Pourquoi UpdateBookAuthor possède uniquement l’identifiant de 
    CrupdateBook et l’identifiant de Author, mais sans les autres propriétés 
    telles que bookName et authorName comme dans leur composant respectif ?

=> On utilise que les identifiants car ce sont les seuls éléments nécéssaire
   pour modifier l'autheur d'un livre dont les deux identifiants éxistent déjà

    ii. Dans quel cas, UpdateBookAuthor devrait avoir les propriétés 
    de CrupdateBook et de Author ?

=> On pourrait  envisager de mettre ces propriétés dans les réponses de la requête

3] a] Pourquoi les paginations sont-elles nécessaires ? 

=> Il est important de paginer certaines réponses de requête (les listes)
pour ne pas saturer le serveur pour une question de liste mais aussi à alléger
la taille des données une fois arrivé vers un client ou une interface

