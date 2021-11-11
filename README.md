# UniversalDomainAdaptation
This notebook compares the accuracy of pretrained Universal Adaptation Network and the accuracy from the network's latent feature space, and shows a problem in implementing universal domain adaptation paper.

- Framework: PyTorch
- Dataset: Office-Home dataset, link: https://www.hemanthdv.org/officeHomeDataset.html
- Code reference: https://github.com/thuml/Universal-Domain-Adaptation .Paper: https://openaccess.thecvf.com/content_CVPR_2019/papers/You_Universal_Domain_Adaptation_CVPR_2019_paper.pdf
- Metric: Average of per-class accuracy. For feature extractor vector classification, minimum euclidean distance between feature extractor output and feature centers is used to classify images.
