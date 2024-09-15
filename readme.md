Ajouter le CSS dans css/tweaks.css

```css
main:only-child {
  // Pas trop large
  max-width: 1400px;
  // Centré
  margin: 0 auto;
}

// Colonne de texte plus étroite (pas plus de 90 signes par ligne)
main:only-child p, 
main:only-child ul,
main:only-child ol,
main:only-child h2 {
  max-width: 800px;
  // Centré, avec de l'espace après chaque objet
  margin: 0 auto 2rem;
}

main:only-child p {
  // Plus gros
  font-size: 1.1rem;
  // Plus d'interlignage
  line-height: 180%;
}

main:only-child h2 {
  // Pas mal d'espace avant les h2
  margin-top: 4rem;
}

main:only-child img {
  // Pas mal d'espace avant et après les images
  margin: 2rem auto 4rem;
}
```

![](sample.png)