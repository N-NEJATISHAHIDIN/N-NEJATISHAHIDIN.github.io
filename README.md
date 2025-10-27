# About
AI Research Engineer with a Ph.D. in Computer Science (Computer Vision & Deep Learning) and 6+ years of experience developing and scaling deep learning architectures and generative models. Skilled in model training, large-scale synthetic data generation, and safety-aware evaluation for Vision-Language Models (VLMs), Large Language Models (LLMs), and 3D vision. Extensive research in 3D scene understanding and multimodal perception. Passionate about transforming research innovations into robust, high-impact AI systems.

[linkdin](https://www.linkedin.com/in/negar-nejati-65684182/), 
[scholar](https://scholar.google.com/citations?hl=en&user=QUdDLg8AAAAJ), 
[CV](/assets/Resume_NegarNejatishahidin.pdf)


    
## Work Experience

**Senior Computer Vision Engineer. @ [HP Inc.](https://www.hp.com/us-en/home.html) (Dec. 2024 - Present)**
Research engineer for HP AI Companion-V2, a generative AI assistant integrated into HP AI PCs.
- Fine-tuned and deployed VLMs, SLMs, and LLMs using PEFT, RLHF (Reinforcement Learning with Human Feedback), DPO,
and distillation with quantization for edge inference; improved performance by 26% on internal benchmarks.
- Built novel agentic GenAI-based evaluation frameworks leveraging chain-of-thought reasoning and LLMs as judges to benchmark
LLMs and VLMs on reasoning performance and scalability.
- Designed synthetic data pipelines with novel recursive safety checks and generative augmentation, transforming low-quality data
into high-fidelity reusable datasets across multiple teams.
- Research advisor for uncertainty-aware 3D room layout recovery pipeline from a single RGB image using Defusion and Gaussian
Splash modules for feature refinement and probabilistic estimation.

**Computer vision research intern. @ [Humane](https://humane.com/) (_May. 2023 - Aug. 2023_)**
- Enhanced on-device hand-tracking accuracy for the Humane AI Pin using semi-supervised learning on unlabeled datasets,
improving internal accuracy by 13%.
- Developed a cycle-accuracy metric for 3D hand pose evaluation in semi-supervised training, improving model calibration and
geometric consistency. Built automated evaluation and annotation pipelines, enabling scalable and repeatable benchmarking
cycles for 3D tracking and reconstruction models.
- Automated dataset creation and annotation pipelines, enabling scalable, repeatable evaluation cycles.
  
**Computer vision research intern. @ [Zillow Group](https://www.zillowgroup.com/) (_May. 2022 - Dec 2022_)**
- Developed the first end-to-end architecture for global camera localization and layout estimation with model parallelism, achieving
superior accuracy to SOTA baselines.
- Co-authored a Best Paper (CVPR OmniCV 2023) and a U.S. Patent (18/114,951) based on this research.
- Supervised by [Dr. Sing Bing Kang](https://scholar.google.com/citations?user=2rzyuRQAAAAJ&hl=en).


## Awards  
Best paper award 2023
Awarded by OmniCV workshop at IEEE / CVF Computer Vision and Pattern Recognition Conference (CVPR)
Awarded for the paper [Graph-CoVis: GNN-based Multi-view Panorama Global Pose Estimation](https://openaccess.thecvf.com/content/CVPR2023W/OmniCV/papers/Nejatishahidin_Graph-CoVis_GNN-Based_Multi-View_Panorama_Global_Pose_Estimation_CVPRW_2023_paper.pdf).

## Just for fun 
[medium](https://medium.com/@negarnejatiuni/how-to-start-research-in-pose-estimation-a-practical-road-map-3ed654130dee)

## Projects and Publications

### Structured Spatial Reasoning with Open Vocabulary Object Detectors
[Publication](https://arxiv.org/abs/2410.07394)
[Publication](https://openreview.net/pdf?id=f8ApFaFW3x)

Spatial reasoning is crucial for robotic tasks like fetch-and-delivery, object rearrangement, and search. Detecting and localizing objects accurately is key to success. Recent work leverages Vision-Language Models (VLMs) to improve this capability. We propose a structured probabilistic approach that combines rich 3D geometric features with open-vocabulary object detectors to enhance spatial reasoning. We evaluate our method against zero-shot VLM performance on spatial reasoning tasks using annotated clauses from the RGB-D Active Vision Dataset and the synthetic Semantic Abstraction dataset. Our method outperforms state-of-the-art open-source VLMs by over 20% in grounding spatial relations.


### Graph-CoVis
[Publication](https://openaccess.thecvf.com/content/CVPR2023W/OmniCV/papers/Nejatishahidin_Graph-CoVis_GNN-Based_Multi-View_Panorama_Global_Pose_Estimation_CVPRW_2023_paper.pdf)

In this paper, we address the problem of wide-baseline camera pose estimation from a group of 360deg panoramas under upright-camera assumption. To exploit the benefits of multi-view logic in a learning-based framework, we introduce Graph-CoVis, which nontrivially extends CoVisPose from relative two-view to global multi-view spherical camera pose estimation. Graph-CoVis is a novel Graph Neural Network based architecture that jointly learns the co-visible structure and global motion in an end-to-end and fully-supervised approach.

![EEG Band Discovery](/assets/projects/Graph_Covis.png)

### Object Pose Estimation
[Publication](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9981452)

This work proposes a novel pose estimation model for object categories that can be effectively transferred to previously unseen environments. In this work, we propose a model for pose estimation that can be trained with small amount of data and is built on the top of generic mid-level represen-tations (e.g. surface normal estimation and re-shading). In addition, we introduce a new pose estimation benchmark for commonly encountered furniture categories on challenging Active Vision Dataset.

![Bike Study](/assets/projects/object_pose.png)

### Fingerspelling PoseNet
[Publication](https://openaccess.thecvf.com/content/WACV2024W/WVLL/papers/Fayyazsanavi_Fingerspelling_PoseNet_Enhancing_Fingerspelling_Translation_With_Pose-Based_Transformer_Models_WACVW_2024_paper.pdf)

We address the task of American Sign Language fingerspelling translation using videos in the wild. We exploit advances in more accurate hand pose estimation and propose a novel architecture that leverages the transformer based encoder-decoder model enabling seamless contextual word translation. The translation model is augmented by a novel loss term that accurately predicts the length of the finger-spelled word, benefiting both training and inference. We also propose a novel two-stage inference approach that re-ranks the hypotheses using the language model capabilities of the decoder.

![Bike Study](/assets/projects/finger_speling.png)

### Review on 6D Object Pose Estimation
[Publication](https://www.oajaiml.com/uploads/archivepdf/24821141.pdf)

In this study, we will explore the available methods based on input modality, problem
formulation, and whether it is a category-level or instance-level approach. As a part of our
discussion, we will focus on how 6D object pose estimation can be used for understanding
3D scenes.

![Bike Study](/assets/projects/review.png)



## Education
- Ph.D., Computer Science | George Mason University (Sep. 2019, may.2025)								       		
- M.S., Computer Science | George Mason University (Sep. 2019 , May. 2022)	 			        		
- B.S., Computer Engneering | Iran University of Science and Technology (Sep. 2014, May 2019)



