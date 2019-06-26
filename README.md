## Short Description

This repository serves as the online appendix for Evert & Klint (2019) Master Thesis-project. The project investigates how the level of education and work experience has evolved among danish electives since 1849. This repository mainly contains the code for collecting and tidying data from the Danish Parliament's open data source "Folketingets Åbne Data" and from the Danish Parliament website.. In the future, this repository will also serve as a platform to share out data and results. 


## Dependencies

The code depends solely on R, version 3.4.1. Packages to supply Base-R are installed in the code. 

## Files

The project contains the following files

### Code
bilag_a_introduction:
1. forklaring

bilag_b_forskningsdesign_I: 
1. 01_indhentning_medlemslister_wiki.Rmd
2. 02_indhentning_API.Rmd
3. 03_merge_medlemslister_og_API.Rmd
4. 04_MF_indvalg_alder.Rmd
5. 05_rensning_MF_uddannelse.Rmd
6. 06_rensning_MF_stilling.Rmd
7. 07_indhentning_MF_aar_erhverv.Rmd
8. 08_antal_aar_erhverv_erf.Rmd
9. 09_rensning_historiske_data.Rmd
10. 10_merge_historisk_og_digitalt_data.Rmd
11. 11_sammenkodning_historisk_og_digitalt_data.Rmd
12. 12_rensning_uddannelsesdata_valgundersoelgelsen.Rmd

bilag_c_forskningsdesign_II:
1. 01_soegestreng_kvant_indhold
2. 02_infomedia_kildedaekning_premium_kilder.pdf

bilag_d_analyse_I:
1. 01_udvikling_MF_udd.Rmd
2. 02_ekstrapolering.Rmd
3. 03_repraesentationsmaal.Rmd
4. 04_udvikling_udd_partierne.Rmd

bilag_e_analyse_II:
1. 01_conjointanalyser_plot.Rmd
2. 02_robusthedstest.Rmd
3. 03_primingeksperiment.Rmd
4. 04_kendskab_partiformaend.Rmd
5. 05_kendskab_signifikanstest.Rmd
6. 06_kendskab_overestimation_egen_formand.Rmd

bilag_f_diskussion:
1. 01_folketingets_sammensaetning.pdf

### Data
*Is to come*

### Results
analyse_1:
1. 01_udd_2_kategorier.pdf
2. 02_udd_4_kategorier.pdf
3. 03_parti_udd_2015.pdf
4. 04_fire_partier_boglig.pdf
5. 05_fire_parti_kandidat.pdf
6. 06_alle_parti_boglig.pdf
7. 07_udd_pol_befo.pdf
8. 08_udd_pol_befo_ekstrapol.pdf
9. 09_plot_gap_og_indeks.pdf
10. 10_plot_erhverv_samlet.pdf
11. 11_erhv_erf_alder.pdf
12. 12_erhv_erf_parti.pdf

analyse_2: 
1. 01_MM_plot.pdf
2. 02_MM_erhvervserfaring.pdf
3. 03_MMs_for_beskaef_paa_tvaers_af_sektor.pdf
4. 04_AMCE_leder_vs_ansat.pdf
5. 05_AMCE_samf_vs_ikkesamf.pdf
6. 06_AMCE_Statskundskab_vs_andre.pdf
7. 07_MM_alle_uddannelser.pdf
8. 08_MMs_for_udd_paa_tvaers_af_resp_udd.pdf
9. 09_sandsynlige_profiler.pdf
10. 10_priming_1
11. 11_priming_2
13. 12_priming_3

## Preregistration
The preregistration of this project can be found here: https://bit.ly/2X3qwOB.

## More Information
Some of the scraper functions has been set to eval=F, as they may be outdated at one point and as we hope to apply less pressure on the Danish Parliament Website. We strongly suggest to rely mainly on the API-function.
