# Dashboard-Covid19

# Tableau de bord COVID-19 

Tableau de bord interactif retraçant l'évolution de la pandémie de COVID-19 
à l'échelle mondiale, construit avec R, Shiny et flexdashboard.

##  Démo en direct
 **[Ouvrir le tableau de bord](https://elvaaaa.shinyapps.io/covid19-dashboard/)**
 

##  Fonctionnalités
- **Vaccination** — évolution de la couverture vaccinale au Canada, par province.
- **Décès** — comparaison de la mortalité entre pays.
- **Carte mondiale interactive** — cliquez sur un pays pour l'afficher en 
  surbrillance et voir ses statistiques détaillées, avec animation dans le temps.

##  Technologies
`R` · `Shiny` · `flexdashboard` · `plotly` · `ggplot2` · `dplyr` · `maps` · `gganimate`

##  Lancer l'application localement
```r
# Installer les dépendances
install.packages(c("flexdashboard", "shiny", "plotly", "ggplot2",
                   "dplyr", "maps", "gganimate", "here"))

# Lancer le tableau de bord
rmarkdown::run("projet_test.Rmd")
```

##  Données
- [Our World in Data](https://ourworldindata.org/coronavirus) — cas et décès mondiaux (licence CC BY).
- Santé InfoBase Canada — données de vaccination.

