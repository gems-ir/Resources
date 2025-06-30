# Ressources

This is the Ressources repository for Collector

## Template

Example to only path artifact: 
```yaml
metadata: 
  name: "NameOfYourArtifactRessourcePath"
  description: "This is a description of my artifact path/file"
  date: "29/03/2024"
  category: "Artefact"
  source:
    - "https://exemple.com/exemple-of-collector-ressources"
artefact:
  path: 
    - 'exemple\of\path\to\artefact.atf'
```

Example to only collection:

```yaml
metadata: 
  name: "NameOfYourArtifactRessourceGroup"
  description: "This is a description of my group artifact path"
  date: "29/03/2024"
  category: "Collection"
  source:
    - "https://exemple.com/exemple-of-collector-ressources"
artefact:
  group:
    - 'NameOfYourArtifactRessourcePath'
```