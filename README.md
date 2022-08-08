# awesome-image-alignment-and-stitching

A curated list of awesome resources for image alignment and stitching, etc. The list will be updated continuously.

❗ An up-to-date paper list can be found [here](https://github.com/visionxiang/awesome-computational-photography).





## Tutorials

- **Repo**: [Image registration](https://github.com/youngfish42/awesome-image-registration)

  A resource list about image registration related to natural/remote sensing/medical image and point cloud.

- **MICCAI2019 Tutorial: Learn2Reg: Tutorial on Deep Learning in Medical Image Registration**   [[Homepage]](https://github.com/learn2reg/tutorials2019)

  Three hands-on sessions guiding participants to understand and implement published algorithms using clinical imaging data, including *unsupervised registration, label-supervised registration, and discrete deep learning registration*.

- **A Practical Review on Medical Image Registration: from Rigid to Deep Learning based Approaches** [[PDF&Slides]]( https://github.com/natandrade/Tutorial-Medical-Image-Registration)

  A tutorial for anyone who wants to learn Medical Image Registration, by Natan Andrade, Fabio Augusto Faria, Fábio Augusto Menocci Cappabianco, SIBGRAPI2018

- [Blog] **Image Registration: From SIFT to Deep Learning** [[Homepage]](https://www.sicara.ai/blog/2019-07-16-image-registration-deep-learning) [[Notes/Chinese]](https://zhuanlan.zhihu.com/p/75784915)

  It presents OpenCV feature-based methods before diving into Deep Learning, including example codes.

- [Book] **Image Descriptor: Modern Approaches**, Bin Fan, Zhenhua Wang, and Fuchao Wang. Springer, 2015.

- [Report] 刘帅成：图像对齐技术及其应用 [[Video]](https://www.bilibili.com/video/av79797993/)

- [OpenCV Stitching Tutorial](https://github.com/lukasalexanderweber/stitching_tutorial)



## <font color=#159>Review</font>

**Matching/Registration/Alignment**

- [**2017CVPR**] HPatches: A Benchmark and Evaluation of Handcrafted and Learned Local Descriptors [[Homepage]](https://hpatches.github.io/)

**Stitching/Mosaicking**

- [2019GRSM] Remote Sensing Image Mosaicking: Achievements and Challenges
- [**2019IVC**] Image mosaicing: A deeper insight
- [ **2006Szeliski**] Image Alignment and Stitching: A Tutorial

**Remote Sensing**

- [**2018ISPRSJ**] A deep learning framework for remote sensing image registration

**Medical Registration**

- Deep Learning in Medical Image Registration: A Survey, 2019
- Learning image-based spatial transformations via convolutional neural networks: A review, Magnetic Resonance Imaging, December 2019
- Deformable Medical Image Registration: A Survey, TMI2013

  

## Geometric Pre-processing

- [**2019TCSVT**] DR-GAN: Automatic Radial Distortion Rectification Using Conditional GAN in Real-Time
- [**2019CVPR**] Learning to Calibrate Straight Lines for Fisheye Image Rectification
- [2019CVPR] Deep Single Image Camera Calibration with Radial Distortion [[Proj]](https://research.mapillary.com/publication/cvpr19d/)
- [2015CVPR] Line-Based Multi-Label Energy Optimization for Fisheye Image Rectification and Calibration [[Proj]](http://cvrs.whu.edu.cn/projects/FIRC/)
- 
- [2019IJCV] Superpixel-Guided Two-View Deterministic Geometric Model Fitting [Guobao Xiao]



## Image Matching

### Feature Detection

#### - Key Point

- GLAMpoints: Greedily Learned Accurate Match points, arXiv2019.8 

- [**2018NeurIPS**] LF-Net: Learning Local Features from Images [[github]](https://github.com/vcg-uvic/lf-net-release)
- [**2017CVPR**] Comparative Evaluation of Hand-Crafted and Learned Local Features
- [**2016ECCV**] LIFT: Learned Invariant Feature Transform [[Theano]](https://github.com/cvlab-epfl/LIFT) [[TF]](https://github.com/cvlab-epfl/tf-lift) [[Eduard Trulls]](https://etrulls.github.io/)



#### - Line Detection

- Line as object: datasets and framework for semantic line segment detection, arXiv2019.9
- [**2020PAMI**] Learning Regional Attraction for Line Segment Detection
- [**2019CVPR**] Learning Attraction Field Representation for Robust Line Segment Detection [[github]](https://github.com/cherubicXN/afm_cvpr2019)
- [**2019CVPR**] PPGNet: Learning Point-Pair Graph for Line Segment Detection [[github]](https://github.com/svip-lab/PPGNet)
- [**2018CVPR**] [Wireframe] Learning to Parse Wireframes in Images of Man-Made Environments [[github]](https://github.com/huangkuns/wireframe)

- [**2017ICCV**] Semantic Line Detection and Its Applications
- [**2017PAMI**] A Novel Linelet-based Representation for Line Segment Detection [[Code]](https://github.com/NamgyuCho/Linelet-code-and-YorkUrban-LineSegment-DB)

- [2017CVPR] MCMLSD: A Dynamic Programming Approach to Line Segment Detection [[Code]](http://www.elderlab.yorku.ca/resources/) 

- Edge Drawing/EDLines/LBD Descriptors/LSD [[Code]](https://github.com/mtamburrano/LBD_Descriptor) [[Code2]](https://github.com/Vincentqyw/LineSegmentsDetection)



#### - Edge Detection

- Semantic Edge Detection with Diverse Deep Supervision, arXiv2018.12
- [**2017CVPR**] CASENet: Deep Category-Aware Semantic Edge Detection



#### - Ellipse detection

- Dense Extreme Inception Network: Towards a Robust CNN Model for Edge Detection, arXiv2019.9
- [**2018TIP**] Arc-support Line Segments Revisited: An Efficient and High-quality Ellipse Detection [[github]](https://github.com/AlanLuSun/High-quality-ellipse-detection)
- [**2017IJCV**] Holistically-Nested Edge Detection
- [**2017TIP**] A Fast Ellipse Detector Using Projective Invariant Pruning [[Code]](https://github.com/dlut-dimt/ellipse-detector)

- [**2012ECCV**] [**ELSD**] A parameterless line segment and elliptical arc detector with enhanced ellipse fitting [[Homepage&Code]](http://ubee.enseeiht.fr/vision/ELSD/)



### Feature Description

- Single and Cross-Dimensional Feature Detection and Description: An Evaluation, arXiv2019.10
- [**2020AAAI**] LCD: Learned Cross-domain Descriptors for 2D-3D Matching
- [**2019ICCV**] Beyond Cartesian Representations for Local Descriptors

- [**2016CVPR**] Accumulated Stability Voting: A Robust Descriptor from Descriptors of Multiple Scales [[Proj]](http://shamangary.logdown.com/posts/587520) [[Code]](https://github.com/shamangary/ASV)

- [**2015ICCV**] Discriminative learning of deep convolutional feature point descriptors



### Image Matching

#### - Feature Matching

- GLMNet: Graph Learning-Matching Networks for Feature Matching, arXiv2019.11

- SuperGlue: Learning Feature Matching with Graph Neural Networks, arXiv2019.11

- [**2019IJCV**] Locality Preserving Matching

- [2019TIP] Robust Feature Matching Using Spatial Clustering With Heavy Outliers

- [**2019CVPR**] RF-Net: An End-to-End Image Matching Network based on Receptive Field [[Code]](https://github.com/Xylon-Sean/rfnet)

- [**2019ICCV**] Learning Two-View Correspondences and Geometry Using Order-Aware Network [[Codes]](https://github.com/zjhthu/OANet)

- [**2018PAMI**] CODE: Coherence based Decision Boundaries for Feature Matching [[Code]](https://github.com/seravee08/WideBaselineFeatureMatcher_PAMI)

- [**2018PAMI**] Best-buddies similarity-robust template matching using mutual nearest neighbors

  > [**2015CVPR**] Best-Buddies Similarity for Robust Template Matching [[Proj&Code]](https://people.csail.mit.edu/talidekel/Best-Buddies%20Similarity.html)

- [2018CVIU] Deep Spectral Correspondence for Matching Disparate Image Pairs 

- [2017MM] Deep Matching and Validation Network: An End-to-End Solution to Constrained Image Splicing Localization and Detection [[Codes]](https://github.com/maroofmf/image_splicing_ICT)

- [2017ICMR] Panorama to panorama matching for location recognition

- [**2016IJCV**] DeepMatching: Hierarchical Deformable Dense Matching [[Code]](http://lear.inrialpes.fr/src/deepmatching/)

- [2016BMVC] Fully-Trainable Deep Matching

- [**2016NeurIPS**] Universal Correspondence Network

- [**2015CVPR**] MatchNet: Unifying Feature and Metric Learning for Patch-Based Matching

- [**2013CVPR**] Joint Spectral Correspondence for Disparate Image Matching [[Code]](https://github.com/chaitanya100100/Spectral-Analysis-for-Image-Matching)

- [2013HPCS] Gpu-asift: A fast fully affine-invariant feature extraction algorithm [[Homepage]](http://www.kind-of-works.com/WANGFAN_site_data/GPU-ASIFT.html) [[Code]]()

- [**2012CVPR**] Aligning Images in the Wild [[Homepage]](https://sites.google.com/site/adscsfm/home/aligning-images-in-the-wild/code)

- [**2012CVPR**] Image Matching using Local Symmetry Features [[Proj&Code]](http://www.cs.cornell.edu/projects/symfeat/index.html)



#### - Line Matching

- [2012PR] [LPI] Robust Line Matching through Line-point Invariants, [[Code]](http://www.nlpr.ia.ac.cn/fanbin/code/TestLMDll.rar)

  > [2010CVPR] Line Matching Leveraged By Point Correspondences [[Proj]](http://vision.ia.ac.cn/Students/bfan/lm.htm)



#### - OutlierRemoval

- [**2019ICCV**] Neural-Guided RANSAC: Learning Where to Sample Model Hypotheses [[github]](https://github.com/vislearn/ngransac) [[Proj]](https://hci.iwr.uni-heidelberg.de/vislearn/research/neural-guided-ransac/)
- [**2019CVPR**] MAGSAC: marginalizing sample consensus (no in-outlier threshold) [[Code]](https://github.com/danini/magsac)

- [**2018CVPR**] Latent RANSAC [[Code]](https://github.com/rlit/LatentRANSAC)
- [**2017CVPR**] GMS: Grid-based Motion Statistics for Fast, Ultra-robust Feature Correspondence [[Code]](https://github.com/JiawangBian/GMS-Feature-Matcher) [[Talk]](https://www.bilibili.com/video/av11450426/)



#### - Cross-View Matching

- [2019ICCV] Bridging the Domain Gap for Ground-to-Aerial Image Matching [[Code]](https://github.com/kregmi/cross-view-image-matching)
- [2019ICCV] Ground-to-Aerial Image Geo-Localization With a Hard Exemplar Reweighting Triplet Loss
- [2018CVPR] CVM-Net: Cross-View Matching Network for Image-Based Ground-to-Aerial Geo-Localization
- [2017CVPR] Cross-View Image Matching for Geo-Localization in Urban Environments
- [2016CVPR] Learning to Match Aerial Images With Deep Attentive Architectures
- [2016CVPR] Regularity-Driven Facade Matching Between Aerial and Street Views
- [2015ICCV] Wide-Area Image Geolocalization With Aerial Reference Imagery
- [2015CVPR] Learning Deep Representations for Ground-to-Aerial Geolocalization
- [2013CVPR] Cross-View Image Geolocalization



## Image Registration

- Report: Deep Learning: Image Registration, Steven Chen and Ty Nguyen, 2017 [[Slides]](Docs/CIS581Fall17-DeepLearningRegistration.pdf)

### Homography

- [Homography-Estimation-List_pwc](https://paperswithcode.com/task/homography-estimation/latest)

- Content-Aware Unsupervised Deep Homography Estimation, arXiv2019.9 [[Code]](https://github.com/JirongZhang/DeepHomography)

- [2019Acce] Combining Convolutional Neural Network and Photometric Refinement for Accurate Homography Estimation

- [**2019ICCV**] Homography from two orientation- and scale-covariant features [[Code]](https://github.com/danini/homography-from-sift-features)
- [2019AppSci] STN-Homography: Direct Estimation of Homography Parameters for Image Pairs, AppliedScience
- [2018ACCV] Rethinking Planar Homography Estimation Using Perspective Fields [[Code]](https://github.com/ruizengalways/PFNet)
- [2018RAL] Unsupervised Deep Homography: A Fast and Robust Homography Estimation Model, IEEE RAL [[Code]](https://github.com/tynguyen/unsupervisedDeepHomographyRAL2018)
- [**2018ECCV**] GridFace: Face Rectification via Learning Local Homography Transformations
- [**2017CVPR**] CLKN: Cascaded Lucas-Kanade Networks for Image Alignment
- [2017ICCVW] Homography Estimation from Image Pairs with Hierarchical Convolutional Networks [[Code]](https://github.com/erlikn/tf_dh_py) 
- [2016RSSW] [HomographyNet] Deep Image Homography Estimation, RSSW2016 [[Note]](https://mez.github.io/2017/07/21/homographynet-deep-image-homography-estimation/) [[Note2]](https://blog.csdn.net/miracle0_0/article/details/79640016) [[unofficial1-tf]](https://github.com/alexhagiopol/deep_homography_estimation) [[unofficial2-tf]](https://github.com/yishiliuhuasheng/deep_image_homography_estimation) [[unofficial3]](https://github.com/mez/deep_homography_estimation) [[unofficial4-pytorch]](https://github.com/mazenmel/Deep-homography-estimation-Pytorch) [[unofficial5-keras]](https://github.com/richard-guinto/homographynet) [[unofficial6-keras]](https://github.com/fjbriones/deep-homography)

- **Auxiliary**

- Convolutional Neural Network Optimization for Homography Estimation, thesis2018
- Homography Estimation using Deep Learning for Registering All-22 Football Video Frames, TechReport2017 [[PDF]](https://pdfs.semanticscholar.org/0c86/050845c714e7ad26b7614e61012bec95f86c.pdf)



### Registration

#### - Natural Scene

- [**2017PAMI**] Transformations Based on Continuous Piecewise-Affine Velocity Fields

  > [2015ICCV] Highly-Expressive Spaces of Well-Behaved Transformations: Keeping It Simple [[Code-Python+CUDA]](https://github.com/freifeld/cpabDiffeo) [[Code-CPU+Julia]](https://github.com/angel8yu/cpab-diffeo-julia) [[Proj]](http://groups.csail.mit.edu/vision/sli/projects.php?name=cpab)

- [**2015CVPR**] Robust Image Alignment with Multiple Feature Descriptors and Matching-Guided Neighborhoods [[Proj/Code]](http://cvlab.citi.sinica.edu.tw/publications?id=79)
- [**2014ECCV**] Multi-modal and Multi-spectral Registration for Natural Images [[Proj]](http://www.cse.cuhk.edu.hk/~leojia/projects/multimodal/index.html)

#### - Remote Sensing

- Coarse to fine non-rigid registration: a chain of scale-specific neural networks for multimodal image alignment with application to remote sensing, arXiv2018.2
- [**2018ECCV**] Multimodal Image Alignment Through a Multiscale Chain of Neural Networks with Application to Remote Sensing [[Homepage]](https://www.lri.fr/~gcharpia/alignment/) [[Code]](https://github.com/Lydorn/mapalignment)
- [2018Acce] Multi-Temporal Remote Sensing Image Registration Using Deep Convolutional Features [[github]](https://github.com/yzhq97/cnn-registration)

- **CVPR 2019**   
- Metric Learning for Image Registration [[github]](https://github.com/uncbiag/registration)
- Networks for Joint Affine and Non-Parametric Image Registration
- Multiview 2D/3D Rigid Registration via a Point-Of-Interest Network for Tracking and Triangulation
- SDRSAC: Semi-definite-Based Randomized Approach for Robust Point Cloud Registration Without Correspondences [[Codes]](https://github.com/intellhave/SDRSAC)
- 3D Local Features for Direct Pairwise Registration
- PointNetLK: Robust & Efficient Point Cloud Registration Using PointNet [[Codes]](https://github.com/hmgoforth/PointNetLK)
- FilterReg: Robust and Efficient Probabilistic Point-Set Registration Using Gaussian Filter and Twist Parameterization [[Codes]](https://bitbucket.org/gaowei19951004/poser/src/master/)

- **NeuIPS2019**

- Arbicon-Net: Arbitrary Continuous Geometric Transformation Networks for Image Registration, NeurIPS2019   
  Jianchun Chen (New York University), Lingjing Wang (New York University), Xiang Li (New York University), Yi Fang (New York University)

- Recurrent Registration Neural Networks for Deformable Image Registration, NeuIPS2019  
  Robin Sandkühler, Simon Andermatt, ...

- PRNet: Self-Supervised Learning for Partial-to-Partial Registration, NeuIPS2019  
  Yue Wang (MIT) · Justin M Solomon (MIT)

- Region-specific Diffeomorphic Metric Mapping, NeurIPS 2019

- Automatic and Robust Skull Registration Based on Discrete Uniformization, ICCV2019
  Junli Zhao, Xin Qi, Chengfeng Wen, Na Lei, Xianfeng Gu

- Linearly Converging Quasi Branch and Bound Algorithms for Global Rigid Registration, ICCV2019
  Nadav Dym, Shahar Ziv Kovalsky

- Deep Closest Point: Learning Representations for Point Cloud Registration, ICCV2019
  Yue Wang, Justin M. Solomon

- A Deep Step Pattern Representation for Multimodal Retinal Image Registration, ICCV2019
  Jimmy Addison Lee, Peng Liu, Jun Cheng, Huazhu Fu

- Efficient and Robust Registration on the 3D Special Euclidean Group, ICCV2019
  Uttaran Bhattacharya, Venu Madhav Govindu

- Robust Variational Bayesian Point Set Registration, ICCV2019
  Jie Zhou, Xinke Ma, Li Liang, Yang Yang, Shijin Xu, Yuhe Liu, Sim-Heng Ong

- Recursive Cascaded Networks for Unsupervised Medical Image Registration, ICCV2019 [[github]](https://github.com/microsoft/Recursive-Cascaded-Networks)
  Shengyu Zhao, Yue Dong, Eric I-Chao Chang, Yan Xu

#### - Medical Registration

- **MICCAI2019**  

- Image-and-Spatial Transformer Networks for Structure-Guided Image Registration, 

- Probabilistic Multilayer Regularization Network for Unsupervised 3D Brain Image Registration

- A Deep Learning Approach to MR-less Spatial Normalization for Tau PET Images

- TopAwaRe: Topology-Aware Registration

- Multimodal Data Registration for Brain Structural Association Networks

- Dual-Stream Pyramid Registration Network

- A Cooperative Autoencoder for Population-Based Regularization of CNN Image Registration

- Conditional Segmentation in Lieu of Image Registration

- DeepAtlas: Joint Semi-supervised Learning of Image Registration and Segmentation

- Linear Time Invariant Model Based Motion Correction (LiMo-MoCo) of Dynamic Radial Contrast Enhanced MRI

- Incompressible Image Registration Using Divergence-Conforming B-Splines

- Closing the Gap between Deep and Conventional Image Registration using Probabilistic Dense Displacement Networks [[Codes]](https://github.com/multimodallearning/pdd_net)


#### - Point-cloud Registration

- [2019ICCV] DeepVCP: An End-to-End Deep Neural Network for Point Cloud Registration
- CMRNet: Camera to LiDAR-Map Registration, IEEE ITSC2019



## Image Stitching

### CNN Stitching

- [2020] Attentive Deep Stitching and Quality Assessment for 360° Omnidirectional Images,  JSTSP
- **Secondary**
- [2019] StitchNet: Image Stitching using Autoencoders and Deep Convolutional Neural Networks, thesis
- [2018] Learning-based Natural Geometric Matching with Homography Prior, ElectronicsLetter
- [2016] Image stitching with single-hidden layer feedforward neural networks, IJCNN



### Spatially-Varying Warps

- [**2020TIP**] Local-Adaptive Image Alignment Based on Triangular Facet Approximation
- [2020JINS] Shape-optimizing mesh warping method for stereoscopic panorama stitching
- [**2019TVCG**] Content-Preserving Image Stitching with Regular Boundary Constraints
- [2019CGI] Stereoscopic Image Stitching with Rectangular Boundaries
- [**2019TMM**] A Novel Projective-Consistent Plane based Image Stitching Method
- [**2018TMM**] Parallax-Tolerant Image Stitching Based on Robust Elastic Warping [[Code]](https://github.com/gain2217/Robust_Elastic_Warping)
- [**2018TMM**] Quasi-Homography Warps in Image Stitching
- [**2018ECCV**] Image Stitching with Multiple Registrations [[Homepage]](https://sites.google.com/view/oois-eccv18)
- [**2018ECCV**] Object-Centered Image Stitching  [[Homepage]](https://sites.google.com/view/oois-eccv18)
- [2018ECCVW] GreenWarps: A Two-Stage Warping Model for Stitching Images using Diffeomorphic Meshes and Green Coordinates
- [2018Acce] An Accurate Multi-Row Panorama Generation Using Multi-Point Joint Stitching
- [2018Acce] Generalized Content-Preserving Warps for Image Stitching
- [2018Conf] Large Parallax Image Stitching Using an Edge-Preserving Diffeomorphic Warping Process
- [2017] Robust Multi-homography Method for Image Stitching under Large Viewpoint Changes, conf
- [2014TMM] Image Alignment by Piecewise Planar Region Matching



### Seam-based Stitching

- [**2016ECCV**] SEAGULL: Seam-guided Local Alignment for Parallax-tolerant Image Stitching [[Note]](https://blog.csdn.net/miracle0_0/article/details/81606388)

- [2014CVPR] Parallax-tolerant Image Stitching [[Proj/Data]](http://web.cecs.pdx.edu/~fliu/project/stitch/)

- [2013EG] Seam-Driven Image Stitching

  

### Dsitortion Preserving

- [**2019TIP**] Single-Perspective Warps in Natural Image Stitching [[Code]](https://github.com/tlliao/Single-perspective-warps) [[Code-multi]](https://github.com/tlliao/Single-perspective-warps-multiple)

- [**2016ECCV**] Natural Image Stitching with the Global Similarity Prior [[Proj]](http://www.cmlab.csie.ntu.edu.tw/project/stitching-wGSP/) [[MacOS]](https://github.com/nothinglo/NISwGSP) [[CCC]](https://github.com/Yannnnnnnnnnnn/NISwGSP) [[VS]](https://github.com/firdauslubis88/NISwGSP)

- [2005TOG] As-Rigid-As-Possible Shape Manipulation; [JoG2009] Implementing As-Rigid-As-Possible Shape Manipulation and Surface Flattening [[Proj]](https://www-ui.is.s.u-tokyo.ac.jp/~takeo/research/rigid/)



### Warping/Projection 

- [2009CGF] A Shape-Preserving Approach to Image Resizing [[Proj/Code]](http://mmcheng.net/imageresizing/)

- [2005ICCV] Squaring the Circle in Panoramas
- [2005TOG] As-rigid-as-possible shape manipulation [[Proj]](http://www.dgp.toronto.edu/~rms/software/Deform2D/)



### Stitching/Panoramas

- [**2016TOG**] Jump: Virtual reality video
- [2016ACCV] Pano2Vid: Automatic Cinematography for Watching 360° Videos [[Proj]](http://vision.cs.utexas.edu/projects/Pano2Vid/#publication) [[Code]](https://github.com/sammy-su/Pano2Vid)
- [2014ECCV] PanoContext: A Whole-room 3D Context Model  for Panoramic Scene Understanding, oral [[Proj/Code]](http://panocontext.cs.princeton.edu/)
- [2014ECCV] Photo Uncrop [[Proj]](http://grail.cs.washington.edu/projects/sq_photo_uncrop/)
- [2010ECCV] Real-Time Spherical Mosaicing Using Whole Image Alignment
- [2010CVPR] Generating Sharp Panoramas from Motion-blurred Videos [[Proj]](http://neelj.com/projects/sharppanoramas/)
- [2008MM] Discovering panoramas in web videos [[Proj]](http://web.cecs.pdx.edu/~fliu/project/discover-pano.htm)

- [2007EG] Scene Collages and Flexible Camera Arrays [[Proj]](http://www1.cs.columbia.edu/CAVE/projects/scene_collage/scene_collage.php) [[Sofeware]](http://www1.cs.columbia.edu/CAVE/software/scene_collage/)
- [2007CVPR] Layered Depth Panoramas [[Proj]](http://grail.cs.washington.edu/projects/ldp/index.htm)

- [2007Project] Automating Joiners [[Proj]](http://www.vision.caltech.edu/lihi/Demos/AutoJoiners.html) [[Code]](https://www.cs.cmu.edu/afs/andrew/scs/cs/15-463/f07/proj_final/www/echuangs/) [[PDF]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.369.3142&rep=rep1&type=pdf)
- [2006TOG] Photographing long scenes with multi-viewpoint panoramas [[Proj]](http://grail.cs.washington.edu/projects/multipano/)

**Stitching Application**

- [2016] Introducing facebook surround 360: An open, high-quality 3d-360 video capture system [[Page]](https://engineering.fb.com/video-engineering/introducing-facebook-surround-360-an-open-high-quality-3d-360-video-capture-system/)

- [2012CVPR] Recognizing Scene Viewpoint using Panoramic Place Representation [[Proj/Code]](https://vision.princeton.edu/projects/2012/SUN360/)



### Stereo Stitching

- [2015CVPR]  Casual Stereoscopic Panorama Stitching [[Proj/Data]](http://web.cecs.pdx.edu/~fliu/project/stereostitch/)



## Image Composition

### Seamline

- Coarse-to-fine Seam Estimation for Image Stitching, arXiv2018.5

- [2019SIVP] Quality evaluation-based iterative seam estimation for image stitching [[Code]](https://github.com/tlliao/Iterative-seam-estimation)
- [2018SIVP] Perception-based seam cutting for image stitching [[Code]](https://github.com/tlliao/Perception-based-seam-cutting)
- [2017IPOL] Efros and Freeman Image Quilting Algorithm for Texture Synthesis [2001Dynamic Seamline] [[Code]](http://www.ipol.im/pub/art/2017/171/?utm_source=doi)

- [2012TOG] Panorama weaving: fast and flexible seam processing [[Proj]](http://www.sci.utah.edu/~bsumma/projects/weaving/index.html)



### Blending

#### - Gradient-based

- [**2019MM**] GP-GAN: Towards Realistic High-Resolution Image Blending  [[Proj]](http://wuhuikai.me/GP-GAN-Project/)  [[github]](https://github.com/wuhuikai/GP-GAN) :star:
- [2012TOG] Image Melding: Combining Inconsistent Images using Patch-based Synthesis [[Proj/Code]](https://www.ece.ucsb.edu/~psen/melding.html)
- [2010ECCV] Error-tolerant Image Compositing [[Code]](http://graphics.berkeley.edu/papers/Tao-ERR-2010-09/)
- [2007TOG] Efficient gradient-domain compositing using quadtrees [in PS CS3] [[Proj]](http://www.agarwala.org/efficient_gdc/)
- [2004SIGG] Interactive Digital Photomontage [[Proj&Code]](http://grail.cs.washington.edu/projects/photomontage/)
- [2004ECCV] Seamless image stitching in the gradient domain
- [2003SIGG] Poisson image editing 



### Dodging

- [**2019ISPRSJ**] A Closed-Form Solution for Multi-View Color Correction with Gradient Preservation [[Code]](https://github.com/MenghanXia/ColorConsistency)

  > [2017ICCVW] Color Consistency Correction Based on Remapping Optimization for Image Stitching

- [**2018TIP**] Dissecting and Reassembling Color Correction Algorithms for Image Stitching [[Code&Supp]](1https://drive.google.com/open?id=0B_3Nh0OK9BclQkt4empQVU5yVE0)

- [**2016CVPR**] Efficient and Robust Color Consistency for Community Photo Collections [[Homepage]](http://jaesik.info/publications/photoconsistency/) [[Code]](https://github.com/syncle/photo_consistency)
- [2011ICCV] Revisiting radiometric calibration for color computer vision



## Stitching Assessment

- [2019MM] Cross-Reference Stitching Quality Assessment for 360° Omnidirectional Images [[Slides]](/Docs/2019MM_Cross_Reference_Stitching.pptx) [[Dataset]](https://github.com/Kaiwen1949/CRSQA) 
- [2017ICCVW] A content-aware metric for stitched panoramic image quality assessment

- **Secondary**

- Quality Evaluation for Stitched Panoramic Videos, Thesis2018.11



## Video Stitching

- [**2019BMVC**] [**CNNStitch**] Video Stitching for Linear Camera Arrays [CNN-based]  [[Proj]](http://vllab.ucmerced.edu/wlai24/video_stitching/)  :star:

- [**2018TIP**] Dynamic Video Stitching via Shakiness Removing [[github]](https://github.com/SuTanTank/VideoStitchingViaShakinessRemoving)
- [2017CGF] High-resolution 360 video foveated stitching for realtime VR
- [**2016TIP**] Joint video stitching and stabilization from moving cameras [[Proj]](http://www.liushuaicheng.org/TIP/VideoStitching2016/index.html) [[Shuaicheng Liu]](http://www.liushuaicheng.org/)
- [**2016TOG**] Rich360: Optimized spherical representation from structured panoramic camera arrays
- [2016CGF] Seamless video stitching from hand-held camera inputs [[Proj]](http://www.linkaimo.com/publications/VideoStitching/VideoStitching.html)
- [2015CVPRW] Video Stitching with Spatial-Temporal Content-Preserving Warping
- [2015EG] Panoramic Video from Unstructured Camera Arrays [[Homepage]](https://fperazzi.github.io/projects/panoramic_video/)

- [2015TOC] Efficient video stitching based on fast structure deformation

- **Secondary**

- [2018] Robust spatial–temporal bayesian view synthesis for video stitching with occlusion handling, MVA



## Video Stabilization

- StableNet: Semi-Online, Multi-Scale Deep Video Stabilization, arXiv2019.7

- [**2019SIGGAsia**] Deep Iterative Frame Interpolation for Full-frame Video Stabilization

- [**2019TIP**] Deep Online Video Stabilization With Multi-Grid Warping Transformation Learning [[Code]](https://github.com/cxjyxxme/deep-online-video-stabilization) [[DebugNote]](https://github.com/24werewolf/video-stabilization/tree/0635bc287a0a631d24807161e037e8d694a1f0f5/code/deep-online-video-stabilization-master) [[Note]](https://github.com/24werewolf/video-stabilization/blob/0635bc287a0a631d24807161e037e8d694a1f0f5/paper/Deep%20Online%20Video%20Stabilization%20with%20Multi-grid.md)  Deep Online Video Stabilization, arXiv2018
- [**2019CVPR**] Robust Video Stabilization by Optimization in CNN Weight Space [[Video]](https://cseweb.ucsd.edu/~ravir/)
- [**2018TOG**] Joint Stabilization and Direction of 360◦ Videos
- [2018CGF] Deep Video Stabilization Using Adversarial Networks [[Note]](https://github.com/24werewolf/video-stabilization/blob/0635bc287a0a631d24807161e037e8d694a1f0f5/paper/Deep%20Video%20Stabilization%20Using%20Adversarial%20Networks.md)
- [2018] Deep Learning in Video Stabilization Homography Estimation, ConfNNA2018
- [**2015TIP**] Video Stabilization Based on Feature Trajectory Augmentation and Selection and Robust Mesh Grid Warping
- [**2013CVPR**] Plane-Based Content Preserving Warps for Video Stabilization
- [**2013TOG**] Bundled camera Paths for Video Stabilization [[Proj/Code]](http://www.liushuaicheng.org/SIGGRAPH2013/index.htm) [As-similar-as-possible warping]

- [2013TVCG] Spatially and Temporally Optimized Video Stabilization [[Proj]](https://people.cs.nctu.edu.tw/~yushuen/VideoStabilization/)
- [2009TOG] Content-Preserving Warps for 3D Video Stabilization [[Proj/Data]](http://web.cecs.pdx.edu/~fliu/project/3dstab.htm)



## Libs

- [SmartBlend](https://wiki.panotools.org/SmartBlend)

  It is an application for seamless image blending by Michael Norel. Smartblend allows stitching of many problematic shots (parallaxed, with moving objects or with differing exposure).

- [GCO3.0](https://vision.cs.uwaterloo.ca/code/)

  Matlab code for Max-flow/min-cut



## Stitching Docs/Examples

### Blogs

- [环形影像拼接的视差问题, 2011](https://finalfrank.pixnet.net/blog/post/30022271-%5B%E5%BD%B1%E5%83%8F%E8%99%95%E7%90%86%5D-%E7%92%B0%E5%A0%B4%E5%BD%B1%E5%83%8F%E6%8B%BC%E6%8E%A5%E7%9A%84%E8%A6%96%E5%B7%AE%E5%95%8F%E9%A1%8C)

- [Real-time panorama and image stitching with OpenCV](https://www.pyimagesearch.com/2016/01/25/real-time-panorama-and-image-stitching-with-opencv/), 2016



### Examples

- Panorama stitching Project (Python) [[Code]](https://github.com/tsherlock/panorama) :star:

- OpenPano: Automatic Panorama Stitching From Scratch [[Code]](https://github.com/ppwwyyxx/OpenPano) :star::star:
- Image-Alignment-and-Panoramas [[Code]](https://github.com/TejasNaikk/Image-Alignment-and-Panoramas)

