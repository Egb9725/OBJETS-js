#Contexte
Vous avez été engagé comme développeur de logiciels dans une bibliothèque locale. Votre première tâche consiste à créer un système de catalogue simple pour garder une trace de tous les livres.

Chaque livre de la bibliothèque possède :

un titre,
un auteur,
une année de publication
et une valeur booléenne indiquant s'il est actuellement emprunté ou non.

#Challenge

Créez un objet JavaScript pour représenter un livre.

L'objet doit avoir des propriétés pour le titre, l'auteur, l'année de publication et isCheckedOut.

Écrivez une fonction createBook qui prend en argument le titre, l'auteur et l'année de publication d'un livre et renvoie un nouvel objet livre.

createBook(title, author, publicationYear){}

Écrire une fonction checkoutBook qui prend un objet livre en argument et change sa propriété isCheckedOut en true.

checkoutBook(book)

Écrire une fonction returnBook qui prend un objet livre en argument et qui modifie sa propriété isCheckedOut en false.

returnBook(book)

Écrivez une fonction getBookInfo(book) qui prend un objet livre en argument et renvoie une chaîne avec les informations du livre dans le format suivant : "Titre de l'auteur, publié en l'année".

L'alchimiste, Paulo Coelho, publié en 1988
