# Daanmulck-Sub-spectrogram-InsectSet66
This repository contains the code and files used for the thesis of Daan Mulckhuijse, submitted in partial fulfillment of the requirements for the degree of Master of Science in Data Science & Society at the School of Humanities and Digital Sciences of Tilburg University.

The InsectSet66 necessary for running the code is publicly available online on Zenodo: https://zenodo.org/records/8252141

This study researches the improvement of bioacoustic insect classification, focusing on Orthoptera and Cicadidae, through the use of sub-spectrogram CNN architectures. While in the process, evaluating both mel and linear spectrograms to determine their efficacy in representing high-frequency insect sounds. This research was motivated by the global decline in insect populations, which threatens ecosystem functions that are essential for human health and survival. Two state-of-the-art models using the InsectSet66 dataset were adapted to incorporate a sub-spectrogram approach. Results have shown that use of linear instead of mel spectrograms did not substantially change performance, indicating that the mel scale compression of higher frequencies is not a constraining factor in this problem setting. Even though these signals are generally in the high frequency spectrum. No universally optimal number of sub-spectrograms could be determined by the models; however, both demonstrated performance improvement. Model 1 showed a 2.1 percentage point increase over its full-spectrogram baseline, achieving a macro F1 score of 90.3%. Model 2 showed a 8.2 percentage point increase over its full-spectrogram baseline, reaching a macro F1 score of 77.6%. The findings suggest that sub-spectrogram architectures are a viable method for enhancing bioacoustic insect classification, potentially contributing to better monitoring and conservation efforts.
