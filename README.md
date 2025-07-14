# Resources

This is the resources repository for Collector

## Template

Example to artifact resource: 
```yaml
metadata:
  name: "NameOfYourArtifactResource"
  description: "This is a description of my artifact"
  date: "17/07/2024"
  target: "Windows"
  source:
    - "https://exemple.com/exemple-of-collector-resources"
artifact:
  path:
    - "example\of\path\to\artifact.atf"
```

Example to group resource:
```yaml
metadata:
  name: "Required"
  description: "Required"
  date: "Optional"
  category: "Optional"
  target: "Required"
  source:
    - "Optional"
artifact:
  group:
    - "Required"
```

## Docs

```yaml
metadata:
  name: "Required"
  description: "Required"
  date: "Optional"
  category: "Optional"
  target: "Required"
  source: 
    - "Optional"
artifact:
  path:
    - "Required"
```