# Booki

Booki est une start-up qui souhaite développer un site Internet qui permette aux usagers de trouver des hébergements et des activités dans la ville de leur choix.

![image](https://user-images.githubusercontent.com/101063444/208477321-7822eb3c-2c19-4286-b880-0855857e2941.png)

## Compétences
<ul>
  <li>Implémenter une interface responsive</li>
  <li>Intégrer du contenu conformément à une maquette</li>
</ul>

### Spécifications fonctionnelles
<ul>
  <li>Les usagers pourront rechercher des hébergements dans la ville de
      leur choix. Le champ de recherche est un champ de saisie, le texte
      doit donc pouvoir être édité par l’utilisateur. Il faut englober ce
      champ dans un formulaire pour que ce dernier soit valide auprès du
      W3C. La partie recherche ne doit pas être fonctionnelle.
  </li>
  <li>Chaque carte d’hébergement ou d’activité devra être cliquable dans
      son intégralité (pas uniquement le titre). Pour l’instant, les liens sont
      vides. On peut utiliser un attribut `href=”#”` pour simuler la
      présence d’un lien.
  </li>
  <li>Les filtres doivent changer d’apparence au survol. Je te laisse décider
      de l’effet approprié, je n’ai pas encore eu le temps de me pencher
      dessus. Par contre, ils ne doivent pas être fonctionnels.
  </li>
  <li>Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont
      des liens. Ils doivent mener respectivement vers la section
      “Hébergements à Marseille” et “Activités à Marseille”.
</li>
</ul>

### Spécifications techniques
<ul>

  <li>Deux maquettes ont été réalisées : l’une desktop et l’autre mobile. Le
      site devra être également adapté aux formats tablette. Pour les
      tablettes, nous sommes libres de faire les adaptations nécessaires. Il
      est important qu’aucun élément ne soit coupé, et que le texte ait
      une taille suffisante.
  </li>
  
  <li>Concernant les breakpoints, nous avons convenu avec le designer UI
      d’utiliser 992 px et 768 px.
      992 px pour les écrans d’ordinateurs et 768 px pour les tablettes, et
      tout ce qui est en dessous de 768 pour les téléphones portables.
  </li>
  
  <li>Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement
      dit, en desktop first), puis les tablettes et enfin les téléphones.
      L’utilisation des Media Queries nous permettra de réaliser
      l’intégration pour les différents supports.
  </li>
      
  <li>Plusieurs formats et tailles d’images ont été exportés. Il faudra choisir
      le format le plus adapté par rapport à la résolution et au temps de
      chargement.
  </li>
  
  <li>Les icônes proviennent de la bibliothèque Font Awesome. Nous
      pouvons passer par <a href='https://www.bootstrapcdn.com/fontawesome'>un CDN</a> pour faciliter le chargement des icônes.
  </li>
  
  <li>Les couleurs de la charte sont le bleu (#0065FC), une version plus
      claire de ce bleu (#DEEBFF) et le gris pour le fond (#F2F2F2).
  </li>
      
  <li>La police du site est Raleway. Nous pouvons passer par Google Font
      pour importer facilement cette police dans le code :
      <a href='https://fonts.google.com/specimen/Raleway'>https://fonts.google.com/specimen/Raleway.</a>
  </li>
  
  <li>Il est important d’utiliser les pixels et les pourcentages plutôt que les
      REM et les EM.
  </li>
      
  <li>Il est important d’utiliser Flexbox plutôt que Grid car c’est la techno
      que l’équipe maîtrise le mieux.
  </li>
  
  <li>Aucun framework CSS (type BootStrap ou Tailwind CSS) ou
      préprocesseur CSS (type Sass ou Less) ne doit être utilisé.
  </li>
      
  <li>Il est important d’utiliser des balises sémantiques (type `main`,
      `header`, `nav`, etc.).
  </li>
      
  <li>Le code doit être valide aux validateurs W3C <a href='https://validator.w3.org/'>HTML</a> et <a href='https://jigsaw.w3.org/css-validator/'>CSS</a>.</li>
  
  <li>La maquette doit être compatible avec les dernières versions de
      Google Chrome et de Mozilla Firefox. Il faudra tester le prototype sur
      ces deux navigateurs.
  </li>
      
  <li>Il n’est pas nécessaire de versionner le code.</li>
</ul>


