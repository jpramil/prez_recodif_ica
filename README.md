# Recodification NAF 2025 assistée par LLMs — présentation

Support de présentation (Quarto / reveal.js) sur la recodification des activités
économiques de la **NAF 2008 (NACE rév. 2)** vers la **NAF 2025 (NACE rév. 3)**
à l'aide de LLM, via l'approche **CAG** (*Context-Augmented Generation*).

Projet associé : [`InseeFrLab/codif-ape-nace-revision`](https://github.com/InseeFrLab/codif-ape-nace-revision).

## Rendu local

```bash
quarto render        # produit _output/index.html
quarto preview       # aperçu live
```

## Publication

Un GitHub Action (`.github/workflows/publish.yml`) rend le projet et le déploie
sur **GitHub Pages** à chaque `push` sur `main`.
