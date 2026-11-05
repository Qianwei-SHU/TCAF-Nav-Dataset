# TCAF-Nav-Dataset
A multimodal construction robot navigation dataset featuring RGB-D images, LiDAR point clouds, robot poses, and task-oriented annotations for semantic-geometric grounding and task-conditioned navigation in real construction environments.

Data source URL for scene extraction：https://drive.google.com/drive/folders/1hKJnR0KDT_FAqUwofRv5xjQPbxLKdJD0?dmr=1&ec=wgc-drive-%5Bmodule%5D-goto
## Public Construction-Site Datasets

## Public Construction-Site Datasets

The TCAF-Nav training dataset integrates self-collected multimodal observations with selected samples from two publicly available construction-site datasets, MOCS and SODA. These datasets provide complementary visual information on construction machinery, workers, safety equipment, and construction materials.

| Dataset | Scale | Main Content | Reference |
|---|---|---|---|
| **MOCS** | 41,668 images; 222,861 annotated instances | 13 categories of moving construction objects, including machinery and workers | An et al., *Automation in Construction*, 2021 |
| **SODA** | 19,846 images | 15 categories of construction-site objects, including workers, safety equipment, and construction materials | Duan et al., *arXiv*, 2022 |

### Dataset Usage

MOCS and SODA are used as supplementary visual data sources, while the self-collected dataset provides RGB-D observations, LiDAR measurements, robot poses, and task-conditioned navigation annotations.

The original datasets remain the intellectual property of their respective authors and are not redistributed through this repository. Users should obtain them from their official sources and comply with the applicable licenses and citation requirements.

### References

1. An, X., Zhou, L., Liu, Z., Wang, C., Li, P., and Li, Z. (2021). Dataset and benchmark for detecting moving objects in construction sites. *Automation in Construction*, 122, 103482.
2. Duan, R., Deng, H., Tian, M., Deng, Y., and Lin, J. (2022). SODA: Site Object Detection dAtaset for Deep Learning in Construction. *arXiv preprint*, arXiv:2202.09554.
