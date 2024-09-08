# :earth_africa: :artificial_satellite: :motorway: Worldwide High-fidelity Road Extraction from Aerial and Satellite Imagery enabled by Low-fidelity OpenStreetMap Labels
Official repository for the supplementary materials of the GCPR24 conference paper *"Worldwide High-fidelity Road Extraction from Aerial and Satellite Imagery enabled by Low-fidelity OpenStreetMap Labels"*.

**GCPR24 proceedings:**
- paper: TBD
- supplementary materials: TBD

**arXiv pre-print:**
- paper: TBD
- supplementary materials: TBD

## Custom dataset splits

Due to the lack of public test or validation sets for some of the datasets we used in our experiement, we split the data ourselves into custom training, validation and test sets (cf. Section 3 in the paper). The images belonging to each set are given in `datasets_splits.json` for each dataset as an image ID. The image prefixes and suffixes may slightly differ from the original images due to modifications made for clarity on our end, but the unique IDs themselves remained as is.
