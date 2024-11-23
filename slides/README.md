# Slides

Originally tried to go with Jupyter, but gave up and switched to Quarto.

```
jupyter nbconvert \
    slides/dataframes-workshop.ipynb \
    --to slides \
    --output-dir=slides/html/;
```

Quarto:

```
quarto preview slides/slides.qmd 
```