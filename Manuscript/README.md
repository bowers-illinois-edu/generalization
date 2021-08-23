
To compile:

```
pandoc --standalone --from=markdown+yaml_metadata_block --biblatex
--bibliography=../../Research-Group-Bibliography/big.bib -V date="Version of $(date
+%Y-%b-%d%n)" explanation_generalization_decision.md -o explanation_generalization_decision.tex; latexmk -pdf explanation_generalization_decision.tex
```
