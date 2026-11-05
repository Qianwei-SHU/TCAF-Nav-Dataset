# TCAF-Nav-Dataset
A multimodal construction robot navigation dataset featuring RGB-D images, LiDAR point clouds, robot poses, and task-oriented annotations for semantic-geometric grounding and task-conditioned navigation in real construction environments.

Data source URL for scene extraction：https://drive.google.com/drive/folders/1hKJnR0KDT_FAqUwofRv5xjQPbxLKdJD0?dmr=1&ec=wgc-drive-%5Bmodule%5D-goto
## Public Construction-Site Datasets

In addition to the self-collected multimodal data acquired using the ALC wall-panel installation robot, this repository provides references to four publicly available construction-site datasets relevant to visual perception and object recognition in complex construction environments. These datasets cover construction machinery, workers, personal protective equipment, and construction materials, providing complementary resources for developing and evaluating construction-oriented perception models.

| Dataset | Dataset Scale | Annotation Categories | Access and License |
|---|---|---|---|
| **MOCS (Moving Objects in Construction Sites)** | 41,668 images; 222,861 annotated instances | 13 categories of construction machinery and workers; bounding boxes and segmentation masks | Application-based access; CC BY-NC 4.0 |
| **ACID (Construction Site Object Detection Benchmark)** | 10,000 images; 15,767 annotated instances | 10 construction machinery categories | Application-based access; reported CC BY 4.0 |
| **SODA (Site Object Detection dAtaset)** | 19,846 images | 15 categories, including workers, helmets, safety vests, boards, wood, rebar, bricks, scaffolds, handcarts, and cutters | Baidu Netdisk; refer to the official dataset page for license terms |
| **Pictor-v3** | 1,472 images reported in the publication; 774 publicly released images with 2,496 worker instances | Worker, hard hat, and safety vest | Public Google Drive repository; no explicit license identified |

### Dataset Access

- **MOCS:** Access requires submitting the [dataset application form](https://www.wjx.cn/vm/wWGwSOc.aspx). The dataset is distributed subject to approval, and commercial use requires additional authorization.
- **ACID:** Access is provided through a dataset application process. For access inquiries, contact `dr.boxiao@gmail.com`. License and commercial-use conditions should be confirmed with the dataset provider.
- **SODA:** Distributed through Baidu Netdisk (extraction code: `9cnh`). Users should consult the official source for download instructions and licensing information.
- **Pictor-v3:** Distributed through a public Google Drive folder. Users should refer to the original publication and repository for the dataset and associated pretrained weights.

### Usage and Attribution

The datasets listed above are maintained by their respective authors and are not redistributed through this repository. Their inclusion is intended to document relevant public resources for construction-site visual perception.

The self-collected TCAF-Nav data and their associated annotations are described separately in this repository. Any use of external datasets for training or evaluation should be documented according to the actual experimental configuration.

Users are responsible for complying with the original datasets' licenses, access restrictions, and citation requirements. In particular, access to a publicly available dataset does not automatically grant permission for commercial use or redistribution.
