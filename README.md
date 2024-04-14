# Exoplanet Explorer
This repository contains an exploration and analysis of confirmed and candidate exoplanet data, as well as an interactive dashboard. The main code is included in [exoplanets.ipynb](https://github.com/ablythed/exoplanets/blob/main/exoplanets.ipynb). To run the notebook, first clone this repo, then navigate into it. Then create the environment using conda:

```
> conda create --name exoplanets --file requirements.txt
> conda activate exoplanets
> jupyter notebook exoplanets.ipynb
```

To view the dashboard on its own without opening the notebook, run `panel serve --show exoplanets.ipynb` in the command line.

I first created this project in 2021 as an intern at Anaconda, and updated it in 2024 to include more data analysis and newer data. An older version of this notebook exists on the [HoloViz site as an example](https://examples.holoviz.org/gallery/exoplanets/exoplanets.html). An older version of the dashboard lives there too.
