# Modifications effectuées

Ici sont consignés les modifications effectuées dans le projet, en suivant les étapes présentes dans le fichier [`plan.md`](./plan.md)

## Etape 1 
Image 'large.jpg' compressé puis convertie en webp dans le dossier './backend/static/'
Modification de la source de l'image dans le fichier App.tsx

## Etape 2
Retrait de classes dans le titre h1 de App.tsx, pour supprimer le clignotement .
Avant :
'<h1 className="text-6xl font-bold bg-gradient-to-r from-purple-400 via-pink-400 to-blue-400 bg-clip-text text-transparent mb-6 animate-pulse">
    EcoTraining Platform
</h1>'

Maintenant :
'<h1 className="text-6xl font-bold">
    EcoTraining Platform
</h1>'


## Etape 3 
Feuille de style big.css déplacé au même endroit que index.css et import depuis le backend supprimé (mis en commentaire)