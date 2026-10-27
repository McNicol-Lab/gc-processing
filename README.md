# GC Data to GHG Fluxes Workflow

1. Organize GC output .txt/.csv files by GC run date in `data/gc-raw`
2. For each experimental/observation unit (e.g. a field sampling day) create a new `code/sampling-unit` folder with peak_to_ppm.Rmd and ppm_to_fluxes.Rmd. Add to this directory the min_elapsed, chamber_temps, and chamber_vols.
3. Data are output to the `data/tidy` folders
