# Slides Assets

Repo d'hébergement d'images pour slides et présentations HTML.

## Structure

```
images/
├── formations/     # Images par formation (IA, prompt, etc.)
├── clients/        # Images spécifiques clients/partenaires
├── icons/          # Icônes et pictogrammes
├── backgrounds/    # Fonds de slides
└── logos/          # Logos (4humens, partenaires, etc.)
```

## Utilisation

### URL brute d'une image

```
https://raw.githubusercontent.com/KirthiganV/slides-assets/main/images/{dossier}/{fichier}
```

### Exemple dans du HTML

```html
<img src="https://raw.githubusercontent.com/KirthiganV/slides-assets/main/images/logos/4humens.png" alt="Logo">
```

### Exemple en CSS background

```css
background-image: url('https://raw.githubusercontent.com/KirthiganV/slides-assets/main/images/backgrounds/gradient-blue.jpg');
```

## Ajouter une image

1. Placer l'image dans le dossier approprié
2. Commit et push
3. L'URL brute est immédiatement disponible

## Conventions de nommage

- Minuscules, tirets pour les espaces : `mon-image.png`
- Préfixer par le contexte si nécessaire : `formation-ia-slide1.jpg`
- Formats recommandés : PNG (transparence), JPG (photos), SVG (icônes)
