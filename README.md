# OptBio Paper Case Studies

This repository contains the **input data** used in the case studies presented in the paper:

**Integrated Investment and Operational Planning for Sugarcane-Based Biofuels and Bioelectricity under Market Uncertainty**

The data provided here allows researchers and practitioners to reproduce the case studies of the paper using [OptBio](https://github.com/psrenergy/OptBio), an open-source optimization package developed in Julia for analyzing the sugarcane biomass supply chain and derived products.

The repository provides:
- A `.optbio` file (SQLite database) with all model input data.
- A set of `.csv` files with scenario data (e.g., prices, availability).

## ⚙️ How to use

1. **Install OptBio**  
   Follow the [installation instructions in the official documentation](https://psrenergy.github.io/OptBio/dev/tutorial.html#Installation).

2. **Clone this data repository**  
   Clone this repository (e.g., in your working directory or inside the OptBio folder):
   ```bash
   git clone https://github.com/psrenergy/OptBio-case-studies.git
   ```

3. **Run the case studies**  
    From the OptBio environment, run:

    ```julia
    using OptBio

    OptBio.main(["OptBioPaperCaseStudies/case1/case1.optbio"])
    ```
    The above command runs the first case study. You can replace the path with the path to other case studies (e.g., `case2`, `case3`, etc.). The results folder will be created in the same directory as the `.optbio` file.

## 📚 References

11. OECD. *OECD Data Explorer*. OECD, 2024. Available at: [https://www.oecd.org/en/data/datasets/oecd-DE.html](https://www.oecd.org/en/data/datasets/oecd-DE.html).  
2. Horta, L.; Kang, S.; Skeer, J. *Sugarcane Bioenergy in Southern Africa: Economic potential for sustainable scale-up*. 2019. Available at: [https://www.researchgate.net/publication/333102787_SUGARCANE_BIOENERGY_IN_SOUTHERN_AFRICA_Economic_potential_for_sustainable_scale-up](https://www.researchgate.net/publication/333102787_SUGARCANE_BIOENERGY_IN_SOUTHERN_AFRICA_Economic_potential_for_sustainable_scale-up).  
3. Junqueira, T. L. et al. *Techno-economic analysis and climate change impacts of sugarcane biorefineries considering different time horizons*. 2017. Available at: [https://biotechnologyforbiofuels.biomedcentral.com/articles/10.1186/s13068-017-0722-3](https://biotechnologyforbiofuels.biomedcentral.com/articles/10.1186/s13068-017-0722-3).  
4. Cheng, H. H. B. S. D.; Cheng, V. S. M.-H. *The Costs of Sugar Production from Different Feedstocks and Processing Technologies*. 2019. Available at: [https://www.osti.gov/servlets/purl/1495027](https://www.osti.gov/servlets/purl/1495027).  
5. U.S. Department of Agriculture, Farm Service Agency. *The Economic Feasibility of Ethanol Production from Sugar in the United States*. 2006. Available at: [https://www.fsa.usda.gov/Internet/FSA_File/ethanol_fromsugar_july06.pdf](https://www.fsa.usda.gov/Internet/FSA_File/ethanol_fromsugar_july06.pdf).  
6. Wang, L.; Quiceno, R.; Price, C.; Malpas, R.; Woods, J. *Economic and GHG emissions analyses for sugarcane ethanol in Brazil*. 2014. Available at: [https://www.sciencedirect.com/science/article/abs/pii/S1364032114006728](https://www.sciencedirect.com/science/article/abs/pii/S1364032114006728).  
7. Instituto 17. *Biogas in Brazil: Economic feasibility analysis and investment potential*. 2022. Available at: [https://i17.eco.br/wp-content/uploads/2022/11/RT02-2022.pdf](https://i17.eco.br/wp-content/uploads/2022/11/RT02-2022.pdf).  
8. Khamhaeng, P.; Laosiripojana, N.; Assabumrungrat, S.; Kim-Lohsoontorn, P. *Techno-economic analysis of hydrogen production from dehydrogenation and steam reforming of ethanol*. 2021. Available at: [https://www.sciencedirect.com/science/article/abs/pii/S0360319921013537](https://www.sciencedirect.com/science/article/abs/pii/S0360319921013537).  
9. Lee, G. K. S. K.; Lee, J. S. Y. *Development of Conceptual Cost Estimation Model for an Economic Analysis of Steam Methane Reforming*. 2022. Available at: [https://www.researchgate.net/publication/360359772_Development_of_Conceptual_Cost_Estimation_Model_for_an_Economic_Analysis_of_Steam_Methane_Reforming_based_Hydrogen_Production](https://www.researchgate.net/publication/360359772_Development_of_Conceptual_Cost_Estimation_Model_for_an_Economic_Analysis_of_Steam_Methane_Reforming_based_Hydrogen_Production).  
10. Alves, S. C. *Steam reforming of methane for hydrogen production*. 2005. Available at: [https://repositorio.ufu.br/bitstream/123456789/15269/1/SCAlvesDISSPRT.pdf](https://repositorio.ufu.br/bitstream/123456789/15269/1/SCAlvesDISSPRT.pdf).  
11. Ramirez, J. A.; Rainey, T. J. *Comparative techno-economic analysis of biofuel production through gasification, liquefaction, and pyrolysis*. 2019. Available at: [https://www.sciencedirect.com/science/article/abs/pii/S0959652619315331](https://www.sciencedirect.com/science/article/abs/pii/S0959652619315331).  
12. RSB. *Feedstock Availability for Sustainable Aviation Fuels in Brazil*. 2021. Available at: [https://rsb.org/wp-content/uploads/2021/04/RSB-SAF-Feedstock-availability-in-Brazil.pdf](https://rsb.org/wp-content/uploads/2021/04/RSB-SAF-Feedstock-availability-in-Brazil.pdf).  
13. Geleynse, S.; Brandt, K.; Garcia‐Perez, M.; Wolcott, M.; Zhang, X. *The Alcohol-to-Jet Conversion Pathway for Drop-in Biofuels: A Techno-Economic Evaluation*. 2018. Available at: [https://chemistry-europe.onlinelibrary.wiley.com/doi/abs/10.1002/cssc.201801690](https://chemistry-europe.onlinelibrary.wiley.com/doi/abs/10.1002/cssc.201801690).  
14. Pavlenko, S. S.; Pavlenko, A. C. N. *The cost of supporting alternative jet fuels in the European Union*. 2019. Available at: [https://theicct.org/sites/default/files/publications/Alternative_jet_fuels_cost_EU_20190320.pdf](https://theicct.org/sites/default/files/publications/Alternative_jet_fuels_cost_EU_20190320.pdf).  
15. Renó, M. L. G.; Lora, E. E. S.; Palacio, J. C. E.; Venturini, O. J.; Buchgeister, J. *A life cycle assessment of methanol production from sugarcane bagasse*. 2011. Available at: [https://www.sciencedirect.com/science/article/abs/pii/S0360544210007000](https://www.sciencedirect.com/science/article/abs/pii/S0360544210007000).  
16. Albarelli, J. Q. et al. *Multi-objective optimization of a sugarcane biorefinery for integrated ethanol and methanol production*. 2017. Available at: [https://www.sciencedirect.com/science/article/abs/pii/S0360544215008609](https://www.sciencedirect.com/science/article/abs/pii/S0360544215008609).  
17. BNDES. *Sugarcane-based bioethanol: Energy for sustainable development*. 2008. Available at: [https://web.bndes.gov.br/bib/jspui/handle/1408/6305](https://web.bndes.gov.br/bib/jspui/handle/1408/6305).  
18. Sampaio, I. L. M. et al. *Electricity production from sugarcane straw recovered through bale system: Assessment of retrofit projects*. 2019. Available at: [https://link.springer.com/article/10.1007/s12155-019-10014-9](https://link.springer.com/article/10.1007/s12155-019-10014-9).  
19. Pratschner, S.; Radosits, F.; Ajanovic, A.; Winter, F. *Techno-economic assessment of a power-to-green methanol plant*. 2023. Available at: [https://www.sciencedirect.com/science/article/pii/S2212982023001749](https://www.sciencedirect.com/science/article/pii/S2212982023001749).  
20. Michaga, M. F. R. et al. *Sustainable aviation fuel (SAF) production through power-to-liquid (PtL): A combined techno-economic and life cycle assessment*. 2023. Available at: [https://www.sciencedirect.com/science/article/pii/S0196890423007732](https://www.sciencedirect.com/science/article/pii/S0196890423007732).  
21. EPE. *Investments and Operational and Maintenance Costs in the Biofuels Sector: 2024–2033*. 2023. Available at: [https://www.epe.gov.br/sites-pt/publicacoes-dados-abertos/publicacoes/PublicacoesArquivos/publicacao-343/topico-699/NT-EPE-DPG-SDB-2023-05_Investimentos_Custos_O_e_M_Bios_2024-2033.pdf](https://www.epe.gov.br/sites-pt/publicacoes-dados-abertos/publicacoes/PublicacoesArquivos/publicacao-343/topico-699/NT-EPE-DPG-SDB-2023-05_Investimentos_Custos_O_e_M_Bios_2024-2033.pdf).  
22. NPCT. *Filter cake density*. 2014. Available at: [https://npct.com.br/npctweb/npct.nsf/e0f085ed5f091b1b852579000057902e/716ec96288a9ea4383257cb0006f9ad8/$FILE/Palestra%20Raffaella%20Rossetto.pdf](https://npct.com.br/npctweb/npct.nsf/e0f085ed5f091b1b852579000057902e/716ec96288a9ea4383257cb0006f9ad8/$FILE/Palestra%20Raffaella%20Rossetto.pdf).  
23. Oni, A. O.; Anaya, K.; Giwa, T.; Di Lullo, G.; Kumar, A. *Comparative assessment of blue hydrogen from steam methane reforming, autothermal reforming, and natural gas decomposition technologies for natural gas-producing regions*. 2022. Available at: [https://www.sciencedirect.com/science/article/pii/S0196890422000413](https://www.sciencedirect.com/science/article/pii/S0196890422000413).  
24. EPE. *Ten-Year Energy Expansion Plan 2034 – Biofuels Supply*. 2024. Available at: [https://www.epe.gov.br/sites-pt/publicacoes-dados-abertos/publicacoes/PublicacoesArquivos/publicacao-804/topico-709/PDE2034_Caderno%20de%20Oferta%20de%20Biocombust%C3%ADveis_2024-09-24.pdf](https://www.epe.gov.br/sites-pt/publicacoes-dados-abertos/publicacoes/PublicacoesArquivos/publicacao-804/topico-709/PDE2034_Caderno%20de%20Oferta%20de%20Biocombust%C3%ADveis_2024-09-24.pdf).  
25. Virtual Chemistry Journal. *Sugarcane vinasse as an alternative fuel: Vinasse density*. 2021. Available at: [https://rvq.sbq.org.br/pdf/v14n1a17](https://rvq.sbq.org.br/pdf/v14n1a17).  
26. UNICA. *Historical index of kg of filter cake and vinasse*. 2024. Available at: [https://ctc.com.br/](https://ctc.com.br/).  
27. Publications Office of the European Union. *Definition of input data to assess GHG default emissions from biofuels in EU legislation*. 2019. Available at: [https://op.europa.eu/en/publication-detail/-/publication/7d6dd4ba-720a-11e9-9f05-01aa75ed71a1](https://op.europa.eu/en/publication-detail/-/publication/7d6dd4ba-720a-11e9-9f05-01aa75ed71a1).  
28. Methanol Group. *Biomethanol, natural gas and biomethane plant*. 2023. Available at: [https://oci-global.com/storage/2023/02/oci-methanol-group.pdf](https://oci-global.com/storage/2023/02/oci-methanol-group.pdf).  
29. Folha de Pernambuco. *Biogenic CO₂ production can generate extra revenue for ethanol distilleries*. 2023. Available at: [https://tnpetroleo.com.br/clipping/producao-de-co2-biogenico-pode-gerar-receita-extra-as-destilarias-de-etanol/](https://tnpetroleo.com.br/clipping/producao-de-co2-biogenico-pode-gerar-receita-extra-as-destilarias-de-etanol/).  