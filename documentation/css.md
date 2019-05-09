
# CSS


Cascading Style Sheets (CSS) indiquent au navigateur comment afficher le texte et les autres contenus que vous écrivez en HTML.

### Modifier la couleur du texte
  _Exemple:_
  
 `<h2 style="color: blue;">CatPhotoApp</h2>`
  
  
### Utiliser une classe CSS pour styliser un élément
     
Les sélecteurs de classe CSS permettent de cibler des éléments d'un document en fonction du contenu de l'attribut class de chaque élément.


`/* Cible tous les éléments ayant la classe "spacious" */
.spacious {
  margin: 2em;
}`

### Style Éléments multiples avec une classe CSS
    
  _Exemple_
    
 `div, p { color: #f00; }`   
     
     
 ### Change the Font Size of an Element
     
 la propriété font-size définit la taille de fonte utilisée pour le texte. La modification de cette taille peut entraîner la modification de la taille d'autres éléments car elle est utilisée pour calculer les valeurs des longueurs relatives (type <length>) (par exemple exprimées avec les unités em ou ex).
     
   _Exemple_ 
 `font-size: 1.2em;`
 
    
### Ajouter une marge négative à un élément
  
 La marge d'un élément contrôle la quantité d'espace entre la bordure d'un élément et les éléments environnants.
 
 _Exemple_
 
 `<style>
   .injected-text {
     margin-bottom: -25px;
     text-align: center;
   }`
   