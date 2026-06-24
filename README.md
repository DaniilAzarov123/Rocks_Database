# Rocks Database (Nosofsky et al., 2018)

A database of 480 rock images spanning 30 categories of 16 members each, originally compiled by Nosofsky et al. (2018). The dataset also includes an 8-dimensional Multidimensional Scaling (MDS) solution for all 480 images, as well as item-level average distinctiveness ratings from Meagher and Nosofsky (2023).

## Repository Structure

### `Rocks480/`

Contains all 480 rock images in `.png` format, named by category, subcategory, and subcategory member index (e.g., `I_Andesite_01.png`).

### `info/`

Contains metadata and derived data for the 480 images:

- **`Rocks480_general.csv`** — General information for each image, including its image ID, rock category, subcategory, subcategory member index, and filename.
- **`Rocks480_MDS8_solution.csv`** — The 8-dimensional MDS solution derived by Nosofsky et al. (2018). Each row corresponds to an image and contains its coordinates along 8 perceptual dimensions (`dim1`–`dim8`), reflecting the underlying similarity structure of the stimuli.
- **`Rocks480_distinctiveness.csv`** — Item-level average distinctiveness ratings for all 480 images, collected by Meagher and Nosofsky (2023). Each row contains an image ID and its corresponding distinctiveness rating.

## References

- Meagher, B. J., & Nosofsky, R. M. (2023). Testing formal cognitive models of classification and old-new recognition in a real-world high-dimensional category domain. *Cognitive Psychology*, *145*, 101596.
- Nosofsky, R. M., Sanders, C. A., Meagher, B. J., & Douglas, B. J. (2018). Toward the development of a feature-space representation for a complex natural category domain.  *Behavior research methods*, *50* (2), 530-556.
