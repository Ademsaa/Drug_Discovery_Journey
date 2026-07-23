# Drug Discovery Journey — Based on Volkamer Lab's TeachOpenCADD

## About this project

This repository documents my personal journey learning and applying **Computer-Aided Drug Design (CADD)**, with a focus on kinase structure analysis. It is inspired by and builds upon the excellent [**TeachOpenCADD**](https://github.com/volkamerlab/teachopencadd) platform developed by the **Volkamer Lab**.

While the original talktorials provided the foundation and learning path, I have modified and extended several notebooks to fit my own environment and goals, including:

- Replacing the original `opencadd` / `nglview` dependencies with **direct KLIFS API calls** and **py3Dmol** for 3D molecular visualization
- Adapting protein structure and binding pocket volume visualization workflows
- Troubleshooting and resolving 3D molecular viewer rendering issues across different visualization backends
- Adjusting the code and environment setup to run reliably in my own development environment

## Acknowledgment & Attribution

This project is based on the **[TeachOpenCADD](https://github.com/volkamerlab/teachopencadd)** repository, developed by the **Volkamer Lab** (Charité – Universitätsmedizin Berlin / In Silico Toxicology and Structural Bioinformatics group).

> Sydow, D., Morger, A., Driller, M. et al. *TeachOpenCADD: a teaching platform for computer-aided drug design using open source packages and data.* J Cheminform 11, 29 (2019). https://doi.org/10.1186/s13321-019-0351-x

All credit for the original talktorial structure, teaching content, and core methodology goes to the Volkamer Lab. This repository is a personal, modified derivative created for learning purposes and is not an official Volkamer Lab or TeachOpenCADD product.

## What's different in this repository

| Aspect | Original TeachOpenCADD | This repository |
|---|---|---|
| Structure visualization | `nglview` | `py3Dmol` |
| Structure/pocket data access | `opencadd` | Direct KLIFS API calls |
| Environment | Original Volkamer Lab setup | Custom environment configuration |

## License

Please refer to the original [TeachOpenCADD license](https://github.com/volkamerlab/teachopencadd/blob/master/LICENSE) for terms covering the original content this project builds upon. Modifications in this repository are shared for educational purposes.

## Contact

Feel free to open an issue if you have questions about the modifications made in this repository.
