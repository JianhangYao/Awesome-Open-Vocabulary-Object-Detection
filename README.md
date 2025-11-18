# Awesome-Open-Vocabulary-Object-Detection

**This project tracks classic and recent advances in open vocabulary object detection, including related areas like Open-Vocabulary aerial and 3D detection.**

**We hope it helps your research.**

**If you find this project useful, please give it a star ⭐.**

## Contents

* [Open-Vocabulary Object Detection](#Open-Vocabulary Object Detection)
* [Open-Vocabulary Aerial Object Detection](#Open-Vocabulary Aerial Object Detection)
* [Related Survey](#Related Survey)




### Open-Vocabulary Object Detection
1. <span id = "1001">**[ViLD]**</span> | **ICLR'22** | Open-vocabulary Object Detection via Vision and Language Knowledge Distillation | [`[pdf]`](https://arxiv.org/pdf/2104.13921 ) | [`[code]`](https://github.com/tensorflow/tpu/tree/master/models/official/detection/projects/vild )
2. <span id = "1008">**[GLIPv2]**</span> | **NeurIPS'22** | GLIPv2: Unifying Localization and Vision-Language Understanding | [`[pdf]`](https://arxiv.org/pdf/2206.05836 ) | [`[code]`](https://github.com/microsoft/GLIP )
3. <span id = "1003">**[Object-Centric OVD]**</span> | **NeurIPS'22** | Bridging the Gap between Object and Image-level Representations for Open-Vocabulary Detection | [`[pdf]`](https://arxiv.org/pdf/2207.03482 ) | [`[code]`](https://github.com/hanoonaR/object-centric-ovd )
4. <span id = "1020">**[DetPro]**</span> | **CVPR'22** | Learning to Prompt for Open-Vocabulary Object Detection with Vision-Language Model | [`[pdf]`](https://arxiv.org/pdf/2203.14940 ) | [`[code]`](https://github.com/dyabel/detpro )
4. <span id = "1005">**[HierKD]**</span> | **CVPR'22** | Open-Vocabulary One-Stage Detection with Hierarchical Visual-Language Knowledge Distillation | [`[pdf]`](https://arxiv.org/pdf/2203.10593 ) | [`[code]`](https://github.com/mengqiDyangge/HierKD )
5. <span id = "1015">**[OV-DETR]**</span> | **ECCV'22 Oral** | Open-Vocabulary DETR  with Conditional Matching | [`[pdf]`](https://arxiv.org/pdf/2203.11876 ) | [`[code]`](https://github.com/yuhangzang/OV-DETR )
6. <span id = "1020">**[PromptDet]**</span> | **ECCV'22** | PromptDet: Towards Open-vocabulary Detection using Uncurated Images | [`[pdf]`](https://arxiv.org/pdf/2203.16513 ) | [`[code]`](https://github.com/fcjian/PromptDet )
6. <span id = "1020">**[VL-PLM]**</span> | **ECCV'22** | Exploiting Unlabeled Data with Vision and Language Models for Object Detection | [`[pdf]`](https://arxiv.org/pdf/2207.08954 ) | [`[code]`](https://github.com/xiaofeng94/VL-PLM )
7. <span id = "1019">**[PB-OVD]**</span> | **ECCV'22** | Open Vocabulary Object Detection with Pseudo Bounding-Box Labels | [`[pdf]`](https://arxiv.org/pdf/2111.09452 ) | [`[code]`](https://github.com/salesforce/PB-OVD )
8. <span id = "1019">**[OWL-ST]**</span> | **NeurIPS'23 spotlight** | Scaling Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2306.09683 ) | [`[code]`](https://github.com/google-research/scenic/tree/main/scenic/projects/owl_vit )
9. <span id = "1011">**[CoDet]**</span> | **NeurIPS'23** | CoDet: Co-Occurrence Guided Region-Word Alignment for Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2310.16667 ) | [`[code]`](https://github.com/CVMI-Lab/CoDet )
10. <span id = "1018">**[RO-ViT]**</span> | **CVPR'23 highlight** | Region-Aware Pretraining for Open-Vocabulary Object Detection with Vision Transformers | [`[pdf]`](https://arxiv.org/pdf/2305.07011 ) | [`[code]`](https://github.com/mcahny/rovit )
11. <span id = "1009">**[BARON]**</span> | **CVPR'23** | Aligning Bag of Regions for Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2302.13996 ) | [`[code]`](https://github.com/wusize/ovdet )
11. <span id = "1012">**[DetCLIPv2]**</span> | **CVPR'23** | DetCLIPv2: Scalable Open-Vocabulary Object Detection Pre-training via Word-Region Alignment | [`[pdf]`](https://arxiv.org/pdf/2304.04514 ) 
12. <span id = "1016">**[CORA]**</span> | **CVPR'23** | CORA: Adapting CLIP for Open-Vocabulary Detection with Region Prompting and Anchor Pre-Matching | [`[pdf]`](https://arxiv.org/pdf/2303.13076 ) | [`[code]`](https://github.com/tgxs002/CORA )
13. <span id = "1020">**[UniDetector]**</span> | **CVPR'23** | Detecting Everything in the Open World: Towards Universal Object Detection | [`[pdf]`](https://arxiv.org/pdf/2303.11749 ) | [`[code]`](https://github.com/zhenyuw16/UniDetector )
14. <span id = "1020">**[CondHead]**</span> | **CVPR'23** | Learning to Detect and Segment for Open Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2212.12130 )
15. <span id = "1016">**[VLDet]**</span> | **ICLR'23** | Learning object-language alignments for open-vocabulary object detection | [`[pdf]`](https://arxiv.org/pdf/2211.14843 ) | [`[code]`](https://github.com/clin1223/VLDet )
16. <span id = "1014">**[F-VLM]**</span> | **ICLR'23** | F-VLM: Open-Vocabulary Object Detection Upon Frozen Vision and Language Models | [`[pdf]`](https://arxiv.org/pdf/2209.15639 ) | [`[code]`](https://sites.google.com/view/f-vlm/home )
17. <span id = "1020">**[OWL-ViT]**</span> | **ICML'23** | Multi-Modal Classifiers for Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2306.05493 ) | [`[code]`](https://github.com/prannaykaul/mm-ovod )
18. <span id = "1002">**[DK-DETR]**</span> | **ICCV'23** | Distilling DETR with Visual-Linguistic Knowledge for Open-Vocabulary  Object Detection | [`[pdf]`](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Distilling_DETR_with_Visual-Linguistic_Knowledge_for_Open-Vocabulary_Object_Detection_ICCV_2023_paper.pdf ) | [`[code]`](https://github.com/hikvision-research/opera )
19. <span id = "1013">**[EdaDet]**</span> | **ICCV'23** | EdaDet: Open-Vocabulary Object Detection Using Early Dense Alignment | [`[pdf]`](https://arxiv.org/pdf/2309.01151 ) | [`[code]`](https://chengshiest.github.io/edadet/ )
20. <span id = "1019">**[CFM-ViT]**</span> | **ICCV'23** | Contrastive Feature Masking Open-Vocabulary Vision Transformer | [`[pdf]`](https://arxiv.org/pdf/2309.00775 )
21. <span id = "1020">**[OpenSeeD]**</span> | **ICCV'23** | A Simple Framework for Open-Vocabulary Segmentation and Detection | [`[pdf]`](https://arxiv.org/pdf/2303.08131 ) | [`[code]`](https://github.com/IDEA-Research/OpenSeeD )
22. <span id = "1020">**[VTP-OVD]**</span> | **TNNLS'23** | Fine-Grained Visual–Text Prompt-Driven  Self-Training for Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2211.00849 )
24. <span id = "1004">**[LP-OVOD]**</span> | **WACV'24** | LP-OVOD: Open-Vocabulary Object Detection by Linear Probing | [`[pdf]`](https://arxiv.org/pdf/2310.17109 ) | [`[code]`](https://github.com/VinAIResearch/LP-OVOD )
26. <span id = "1006">**[YOLO-World]**</span> | **CVPR'24** | YOLO-World: Real-Time Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2401.17270v3 ) | [`[code]`](https://github.com/AILab-CVC/YOLO-World )
8. <span id = "1006">**[OV-DINO]**</span> | **CVPR'24** | OV-DINO: Unified Open-Vocabulary Detection with Language-Aware Selective Fusion | [`[pdf]`](https://arxiv.org/pdf/2407.07844 ) | [`[code]`](https://github.com/wanghao9610/OV-DINO )
9. <span id = "1007">**[Grounding-DINO]**</span> | **ECCV'24** | Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection | [`[pdf]`](https://arxiv.org/pdf/2303.05499 ) | [`[code]`](https://github.com/IDEA-Research/GroundingDINO )
12. <span id = "1010">**[CLIM]**</span> | **AAAI'24** | CLIM: Contrastive Language-Image Mosaic for Region Representation | [`[pdf]`](https://arxiv.org/pdf/2312.11376 ) | [`[code]`](https://github.com/wusize/CLIM )
17. <span id = "1015">**[GridCLIP]**</span> | **PR'25** | GridCLIP: One-Stage Object Detection by Grid-Level CLIP Representation Learning | [`[pdf]`](https://pdf.sciencedirectassets.com/272206/1-s2.0-S0031320325X00121/1-s2.0-S0031320325008489/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAEaCXVzLWVhc3QtMSJGMEQCIHje9QAiQ39P8PyC6IykRGYrhPUNuK4Svome9IuTtLbWAiApKZ5AfzMhDDxv9MD%2BRVf9xo4DPEDcgr88SsEou8E2riq8BQjJ%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAUaDDA1OTAwMzU0Njg2NSIMOSEShkQKgIhFUGMeKpAFv%2BMMsydb%2F%2FN5Tbd2Puyrf266Y%2BD9U1ySkq3pY5YQzRl6q6P0Pyis0GUqG4ckJlb8YjnSpbNSeWsQyacvhRASWSct0PkVJNTya2BW5WKvCesJ3esHvChI%2Bo0Dg3zlhR3buP6hJDcJFid6fX82R7eyiHb3bl9r3r9%2BQNKQLjMIRw5BwglK17xrSlkylEo0iw%2FkYjhKvM%2Ft7jv2RSU%2FWMV2qNCGWD2ggFOxHR%2FIUOewXmnPpfQittpno9tDEy5FU9mo85HjWeDXK16l7%2FLq%2BlG5oLoNMCNdeeRXiF4bgpalDRcvS8ZVIqHME0Ks96sMs4p5CGX7qH3%2F%2BsHOl%2BpD6QoxqVSe52PAFhpxgYe7ds0sfCSl00w1lDLU29oCTDvTgT7TKocEnkiFRzOuNRPNkOWCvMXY8k2jasc%2FP894pbgWy2VQVy%2FvMLBAI%2FGlwzjVmiZc0%2F1eKhz0bicsTG8zOqBDKYkHA0vwaJEIAm%2FKg9nclxKulAycpat17pJEp%2BnOxvAMBxbg0Q0MjQiNq7CNNNzuYC90YtVJltDU3WjpPoPJAYySMLT5gygg6SLNMpvnwT3q8ny8qiVuEM3wDNYPjEfER0kmyDXn6EhmePQxPpdckXUFR%2FaaVgZfLj5%2Bdahh7tIRosb2KSg7xqe3Dm0TPQnA%2F4TZl4zdIvSqObLK95ial%2FtWL%2FvO37dnWkGnXkXcW3jKCLLXHESoDWyjkbdY3tBLHadFxd6hhdvaammF669U7L5IqRQlfzPjYVBzHzRg72AdLD6GS4TvCnvHZPlhzAbRft2KCAnaHUlLpWx0JL8v3LtCZj6d4Ry9CAFK24LtphZrVrpWA%2BtidnfN30btiU%2FNZvV%2F8wx6ZfYfWqHTMVBLS5Yw3LfyyAY6sgGqVLfnUScwOT7WnC8dByCFzHYZ8rQz%2Fnd7yzZT0K49%2B%2Fbpu0j8w1WDK%2FbvLKWl45%2BP35uUhQtnbhEkoJB8ya93qZi9eqZJdZqq%2FwQkjyH%2BrkEHBlX94rzzpGRFN%2FFRCsMyJaI0BlSDyumE%2BpDcGA%2FMre529CS8kM5k7eCr1XbqMSD%2BCUeGkpcFxd87Ck4NPK%2FiA3kyqG631pTmpeFUKFP4nStiklh6%2FcbRKGxQ8G7YYikd&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20251118T164343Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY376GS5O6%2F20251118%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=fa222134b81863af10228928ce01f02a0d648063db7d75bf993386e9777b0ff9&hash=ef8ed6302083d6afb9c042992a7313cf40c2af6e52c389a9584c06403694419a&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0031320325008489&tid=spdf-466511d6-4f0f-404e-ab43-eacc53e57983&sid=4b8011019b7ac24d1b7bcdc8c548bcb942dfgxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=19085903505a0a040e0101&rr=9a08edaddf5f0ac6&cc=cn )
18. <span id = "1015">**[SIC-CADS]**</span> | **AAAI'24** | Simple Image-level Classification Improves Open-vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2312.10439 ) | [`[code]`](https://github.com/mala-lab/SIC-CADS )
23. <span id = "1017">**[Prompt-OVD]**</span> | **PR'24** | Prompt-guided DETR with RoI-pruned masked attention for open-vocabulary object detection | [`[pdf]`](https://arxiv.org/pdf/2303.14386 ) | [`[code]`](https://github.com/DISL-Lab/Prompt-OVD )
24. <span id = "1018">**[DITO]**</span> | **ECCV'24** | Region-centric Image-Language Pretraining for Open-Vocabulary Detection | [`[pdf]`](https://arxiv.org/pdf/2310.00161 ) | [`[code]`](https://github.com/google-research/google-research/tree/master/fvlm/dito )
27. <span id = "1019">**[SAS-Det]**</span> | **CVPR'24** | Taming Self-Training for Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2308.06412 ) | [`[code]`](https://github.com/xiaofeng94/SAS-Det )
29. <span id = "1019">**[ProxyDet]**</span> | **AAAI'24** | ProxyDet: Synthesizing Proxy Novel Classes via Classwise Mixup for Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2312.07266 ) | [`[code]`](https://github.com/clovaai/ProxyDet )
32. <span id = "1020">**[DECOLA]**</span> | **CVPR'24** | Language-conditioned Detection Transformer | [`[pdf]`](https://arxiv.org/pdf/2311.17902 ) | [`[code]`](https://github.com/janghyuncho/DECOLA )
34. <span id = "1020">**[WSOVOD]**</span> | **AAAI'24** | Weakly Supervised Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2312.12437 ) | [`[code]`](https://github.com/HunterJLin/WSOVOD )
39. <span id = "1020">**[MarvelOVD]**</span> | **ECCV'24** | MarvelOVD: Marrying Object Recognition and Vision-Language Models for Robust Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2407.21465 ) | [`[code]`](https://github.com/wkfdb/MarvelOVD )
40. <span id = "1020">**[RTGen]**</span> | **ECCV'24** | RTGen: Generating Region-Text Pairs for Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2405.19854 ) | [`[code]`](https://github.com/seermer/RTGen )
43. <span id = "1020">**[LBP]**</span> | **CVPR'24** | Learning Background Prompts to Discover Implicit Knowledge for Open  Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2406.00510 )
45. <span id = "1020">**[SHiNe]**</span> | **CVPR'24 highlight** | SHiNe: Semantic Hierarchy Nexus for Open-vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2405.10053 ) | [`[code]`](https://github.com/naver/shine )
46. <span id = "1020">**[DVDet]**</span> | **ICLR'24** | LLMs Meet VLMs: Boost Open Vocabulary Object Detection with Fine-grained Descriptors | [`[pdf]`](https://arxiv.org/pdf/2402.04630 )
47. <span id = "1020">**[LaMI-DETR]**</span> | **ECCV'24** | LaMI-DETR: Open-Vocabulary Detection  with Language Model Instruction | [`[pdf]`](https://arxiv.org/pdf/2407.11335 ) | [`[code]`](https://github.com/eternaldolphin/LaMI-DETR )
48. <span id = "1020">**[DetCLIPv3]**</span> | **CVPR'24** | DetCLIPv3: Towards Versatile Generative Open-vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2404.09216 )
49. <span id = "1020">**[RALF]**</span> | **CVPR'24** | Retrieval-Augmented Open-Vocabulary Object Detection | [`[pdf]`](https://arxiv.org/pdf/2404.05687 ) | [`[code]`](https://github.com/mlvlab/RALF )
50. <span id = "1020">**[Gen-Enhanced-Negs]**</span> | **CVPR'24** | Generating Enhanced Negatives for Training Language-Based Object Detectors | [`[pdf]`](https://arxiv.org/pdf/2401.00094 ) | [`[code]`](https://github.com/xiaofeng94/Gen-Enhanced-Negs )
51. <span id = "1020">**[Sambor]**</span> | **AAAI'25** | Boosting Segment Anything Model Towards Open-Vocabulary Learning | [`[pdf]`](https://arxiv.org/pdf/2312.03628 )
52. <span id = "1015">**[OV-DQUO]**</span> | **AAAI'25** | OV-DQUO: Open-Vocabulary DETR with Denoising Text Query Training and Open-World Unknown Objects Supervision | [`[pdf]`](https://arxiv.org/pdf/2405.17913 ) | [`[code]`](https://github.com/xiaomoguhz/OV-DQUO )




### Open-Vocabulary Aerial Object Detection
1. <span id = "3001">**[Castdet]**</span> | **ECCV'25** | Toward Open Vocabulary Aerial Object Detection with CLIP-Activated Student-Teacher Learning | [`[pdf]`](https://arxiv.org/pdf/2311.11646 ) | [`[code]`](https://github.com/VisionXLab/CastDet )
2. <span id = "3002">**[LAE-DINO]**</span> | **AAAI'25** | Locate Anything on Earth: Advancing Open-Vocabulary Object Detection for Remote Sensing Community | [`[pdf]`](https://arxiv.org/html/2408.09110v1 ) | [`[code]`](https://github.com/jaychempan/LAE-DINO )

### Related Survey
1. <span id = "4001">**Towards Open Vocabulary Learning: A Survey**</span> | **TAPMI'24** |  [`[pdf]`](https://arxiv.org/pdf/2306.15880 ) | [`[code]`](https://github.com/jianzongwu/Awesome-Open-Vocabulary )
2. <span id = "4002">**A Survey on Open-Vocabulary Detection and Segmentation: Past, Present, and Future** </span> | **TAPMI'24** | [`[pdf]`](https://arxiv.org/pdf/2307.09220 ) | [`[code]`](https://github.com/seanzhuh/awesome-open-vocabulary-detection-and-segmentation )