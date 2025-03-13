# Kiel Microbiome Center workshop

This is the repository for the [KMC 2024 Microbiome Workshop](https://ikmb.github.io/nfdi4microbiota_kmc_microbiome_workshop/).


# Development

Github actions are set to build the website automatically to every push to the `main` branch. To build website locally, follow the instructions in quarto's [documentation](https://quarto.org/docs/websites/). Do not change the branch `gh-pages` manually, it is updated automatically by the github actions.

# Structure

The website is built using [quarto](https://quarto.org/). The main files are:
- [_quarto.yml](_quarto.yml): Configuration file for the Quarto project.
- [index.qmd](index.qmd): Homepage of the workshop website.
- [the_workshop.qmd](the_workshop.qmd): Main content file for the workshop details.
- [fair_principles.qmd](fair_principles.qmd): Information on FAIR principles.
- [questions.qmd](questions.qmd): How to make questions and have answers.
- [resources.qmd](resources.qmd): Additional resources and references for the workshop.

Scripts are stored in the [scripts](scripts) folder. The file inputs are stored in the [inputs](inputs) folder.

# License

MIT License
