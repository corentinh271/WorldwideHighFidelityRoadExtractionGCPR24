# :earth_africa: :artificial_satellite: :motorway: Worldwide High-fidelity Road Extraction from Aerial and Satellite Imagery enabled by Low-fidelity OpenStreetMap Labels
Official repository for the GCPR24 conference paper *"Worldwide High-fidelity Road Extraction from Aerial and Satellite Imagery enabled by Low-fidelity OpenStreetMap Labels"*.

**GCPR24 proceedings:**
- Paper: [LInk](https://link.springer.com/chapter/10.1007/978-3-031-85187-2_19)
- Supplementary materials: [Link](https://static-content.springer.com/esm/chp%3A10.1007%2F978-3-031-85187-2_19/MediaObjects/626037_1_En_19_MOESM1_ESM.pdf)
- Poster: [Link](https://github.com/corentinh271/WorldwideHighFidelityRoadExtractionGCPR24/blob/main/henry_et_al_gcpr_2024_worldwide_hifi_road_extraction_aerial_satellite_imagery_poster.pdf)

## Custom dataset splits

Due to the lack of public test or validation sets for some of the datasets we used in our experiments, we split the data ourselves into custom training, validation and test sets (cf. Section 3 in the paper). The images belonging to each set are given in `datasets_splits.json` for each dataset as an image ID. The image prefixes and suffixes may slightly differ from the original images due to modifications made for clarity on our end, but each unique ID remains as distributed by the respective authors.

## Citation

If you use our research in your own study, please consider citing our paper:

```BibTeX
@InProceedings{henry_2025_worldwide_labels,
  author="Henry, Corentin
  and Fraundorfer, Friedrich",
  editor="Cremers, Daniel
  and L{\"a}hner, Zorah
  and Moeller, Michael
  and Nie{\ss}ner, Matthias
  and Ommer, Bj{\"o}rn
  and Triebel, Rudolph",
  title="Worldwide High-Fidelity Road Extraction from Aerial and Satellite Imagery Enabled by Low-Fidelity OpenStreetMap Labels",
  booktitle="Pattern Recognition",
  year="2025",
  publisher="Springer Nature Switzerland",
  address="Cham",
  pages="302--316",
  isbn="978-3-031-85187-2"
}
```
