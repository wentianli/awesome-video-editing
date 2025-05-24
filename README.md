# awesome-video-editing [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A paper list on video editing (in a cinematographic sense) and its related computer vision tasks.

The papers are put into categories, in which there is unavoidably some overlapping and imprecision. I use some icons to mark several frequent application scenarios: 💬(talk/meeting), 💃(dance/performance), ⚽🏀🏌️🎾(sports), 🛒(ads/promotional videos), 🎬(movie), etc.


*Note: This paper list does not include the works on image/video manipulation (e.g. content editing, object removal, video stylization).*

🀄视频剪辑

---
## Text-based Video Editing
**LLM-Powered or Instruction-based Editing.**
- `[NeurIPS 2024 workshop]` Generative Timelines for Instructed Visual Assembly [[paper]](https://arxiv.org/abs/2411.12293) [[project page]](https://sites.google.com/kaust.edu.sa/timeline-assembler)
- `[IUI 2024]` LAVE: LLM-Powered Agent Assistance and Language Augmentation for Video Editing [[paper]](https://arxiv.org/abs/2402.10294)

**Using texts as input to automatically create video sequences from a collection of videos or images.**
- `[arxiv 2025]` SKALD: Learning-Based Shot Assembly for Coherent Multi-Shot Video Creation [[paper]](https://arxiv.org/abs/2503.08010)
- `[arxiv 2024]` Text-Video Multi-Grained Integration for Video Moment Montage [[paper]](https://arxiv.org/abs/2412.09276)
- `[ICMR 2023]` Shot Retrieval and Assembly with Text Script for Video Montage Generation [[paper]](https://dl.acm.org/doi/10.1145/3591106.3592247) [[code]](https://github.com/RATVDemo/RATV)
- `[MM 2022]` Transcript to Video: Efficient Clip Sequencing from Texts [[paper]](https://arxiv.org/abs/2107.11851) [[project page]](http://www.xiongyu.me/projects/transcript2video/)
- `[CHI 2020]` Generating Audio-Visual Slideshows from Text Articles Using Word Concreteness [[paper]](https://dl.acm.org/doi/abs/10.1145/3313831.3376519)
- `[TOG 2019]` Write-A-Video: Computational Video Montage from Themed Text [[paper]](https://dl.acm.org/doi/abs/10.1145/3355089.3356520)
- `[TMM 2020]` Story-driven Video Editing [[paper]](https://ieeexplore.ieee.org/abstract/document/9257101)
- `[IMX 2020]` Joint Attention for Automated Video Editing [[paper]](https://dl.acm.org/doi/abs/10.1145/3391614.3393656) 💬
- `[UIST 2016]` QuickCut: An Interactive Tool for Editing Narrated Video [[paper]](https://dl.acm.org/doi/abs/10.1145/2984511.2984569)

**Modifying the transcript of a speech to change the speech content or to remove filler words.**
- `[TOG 2019]` Text-based Editing of Talking-head Video [[paper]](https://dl.acm.org/doi/abs/10.1145/3306346.3323028) 💬
- `[TOG 2012]` Tools for Placing Cuts and Transitions in Interview Video [[paper]](https://dl.acm.org/doi/abs/10.1145/2185520.2185563) 💬

<br/>

## Cutting and Sequencing Shots
**To cut unedited videos into shots and/or to put them in an appropriate order.**
- `[ICASSP 2024]` Audio Match Cutting: Finding and Creating Matching Audio Transitions in Movies and Videos [[paper]](https://ieeexplore.ieee.org/abstract/document/10447306) [[project page]](https://denfed.github.io/audiomatchcut/)
- `[CVPR 2024]` Towards Automated Movie Trailer Generation [[paper]](https://arxiv.org/abs/2404.03477) 🎬
- `[MM 2023]` A Reinforcement Learning-Based Automatic Video Editing [[paper]](https://arxiv.org/abs/2301.00135v2) 🎬
- `[ICCV 2023 Workshop]` Representation Learning of Next Shot Selection for Vlog Editing [[paper]](https://cveu.github.io/2023/papers/31.pdf)
- `[WACV 2023]` Match Cutting: Finding Cuts with Smooth Visual Transitions [[paper]](https://arxiv.org/abs/2210.05766) [[code]](https://github.com/netflix/matchcut) [[project page]](https://netflixtechblog.com/match-cutting-at-netflix-finding-cuts-with-smooth-visual-transitions-31c3fc14ae59?gi=8873f373fd1d) 🎬
- `[ACCV 2022]` Multi-modal Segment Assemblage Network for Ad Video Editing with Importance-Coherence Reward [[paper]](https://arxiv.org/abs/2209.12164v1) [[code]](https://github.com/yunlong10/Ads-1k) 🛒
- `[SAC 2022]` Automated Video Editing Based on Learned Styles Using LSTM-GAN [[paper]](https://dl.acm.org/doi/abs/10.1145/3477314.3507141) 💃
- `[ICCV 2021 Workshop]` Learning Where To Cut From Edited Videos [[paper]](https://openaccess.thecvf.com/content/ICCV2021W/CVEU/html/Huang_Learning_Where_To_Cut_From_Edited_Videos_ICCVW_2021_paper.html)
- `[ICCV 2021]` Learning to Cut by Watching Movies [[paper]](https://arxiv.org/abs/2108.04294) [[code & dataset]](https://github.com/PardoAlejo/LearningToCut) [[project page]](https://www.alejandropardo.net/publication/learning-to-cut/)
- `[WACV 2018]` Learning Video-Story Composition via Recurrent Neural Network [[paper]](https://arxiv.org/abs/1801.10281)
- `[arxiv 2018]` From Trailers to Storylines: An Efficient Way to Learn from Movies [[paper]](https://arxiv.org/abs/1806.05341) 🎬
- `[CVPR 2016]` Video-Story Composition via Plot Analysis [[paper]](https://openaccess.thecvf.com/content_cvpr_2016/html/Choi_Video-Story_Composition_via_CVPR_2016_paper.html)

<br/>

## Multi-Camera / Multi-Take Editing
**To select video shots from multiple camera views or multiple takes of the same event.**
- `[MIG 2023]` Real-time Computational Cinematographic Editing for Broadcasting of Volumetric-captured events: an Application to Ultimate Fighting [[paper]](https://dl.acm.org/doi/abs/10.1145/3623264.3624468) 🥊
- `[TOG 2022]` PopStage: The Generation of Stage Cross-Editing Video Based on Spatio-Temporal Matching [[paper]](https://dl.acm.org/doi/abs/10.1145/3550454.3555467) [[project page]](https://w-dlee.github.io/popstage) 💃
- `[ECCV 2022 Workshop]` Temporal and Contextual Transformer for Multi-Camera Editing of TV Shows [[paper]](https://arxiv.org/abs/2210.08737)
- `[ICME 2021]` Reinforcement Learning Based Automatic Personal Mashup Generation [[paper]](https://www.computer.org/csdl/proceedings-article/icme/2021/09428357/1uim1GOOhtC)
- `[TOMCCAP 2021]` Smart Director: An Event-Driven Directing System for Live Broadcasting [[paper]](https://dl.acm.org/doi/full/10.1145/3448981) ⚽
- `[ICISP 2018]` Automatic Camera Selection in the Context of Basketball Game [[paper]](https://link.springer.com/chapter/10.1007/978-3-319-94211-7_9) 🏀
- `[TOG 2017]` Computational Video Editing for Dialogue-Driven Scenes [[paper]](https://dl.acm.org/doi/abs/10.1145/3072959.3073653) 💬
- `[ACE 2017]` Automatic System for Editing Dance Videos Recorded Using Multiple Cameras [[paper]](https://link.springer.com/chapter/10.1007/978-3-319-76270-8_47) 💃
- `[TOG 2014]` Automatic Editing of Footage from Multiple Social Cameras [[paper]](https://dl.acm.org/doi/abs/10.1145/2601097.2601198)
- `[CHI 2008]` Improving Meeting Capture by Applying Television Production Principles with Audio and Motion Detection [[paper]](https://dl.acm.org/doi/abs/10.1145/1357054.1357095) 💬
- `[ICME 2007]` Automatic Multi-Modal Meeting Camera Selection for Video-Conferences and Meeting Browsers [[paper]](https://ieeexplore.ieee.org/abstract/document/4285090) 💬

<br/>

## Video Summarization & Highlight Detection
- `[CVPR 2023]` Collaborative Noisy Label Cleaner: Learning Scene-aware Trailers for Multi-modal Highlight Detection in Movies [[paper]](https://arxiv.org/abs/2303.14768) [[code]](https://github.com/TencentYoutuResearch/HighlightDetection-CLC) 🎬
- `[NeurIPS 2022 Workshop]` Videogenic: Video Highlights via Photogenic Moments [[paper]](https://neuripscreativityworkshop.github.io/2022/papers/ml4cd2022_paper02.pdf) [[project page]](https://humanvideointeraction.github.io/videogenic/)
- `[AutoUI 2021]` Automatic Generation of Road Trip Summary Video for Reminiscence and Entertainment using Dashcam Video [[paper]](https://dl.acm.org/doi/abs/10.1145/3409118.3475151)
- `[MM 2021]` Automated Multi-Modal Video Editing for Ads Video [[paper]](https://dl.acm.org/doi/abs/10.1145/3474085.3479205) 🛒
- `[MM 2021]` VideoDiscovery: An Automatic Short-Video Generation System for E-commerce Live-streaming [[paper]](https://dl.acm.org/doi/abs/10.1145/3474085.3478554) [[project page]](https://discovery.aliyun.com/index#/) 🛒
- `[ECCV 2020]` Learning Trailer Moments in Full-Length Movies [[paper]](https://arxiv.org/abs/2008.08502) 🎬
- `[MMAsia 2019]` Domain Specific and Idiom Adaptive Video Summarization [[paper]](https://dl.acm.org/doi/abs/10.1145/3338533.3366603) 🛒
- `[MM 2019]` Personalized Video Summarization with Idiom Adaptation [[paper]](https://dl.acm.org/doi/pdf/10.1145/3343031.3350584) 🛒
- `[MM 2019]` Generating 1 Minute Summaries of Day Long Egocentric Videos [[paper]](https://dl.acm.org/doi/abs/10.1145/3343031.3350880) [[code]](https://github.com/anuj-rathore/Generating-One-Minute-Summaries)
- `[TMM 2019]` Automatic Curation of Sports Highlights Using Multimodal Excitement Features [[paper]](https://ieeexplore.ieee.org/abstract/document/8491305) 🏌️🎾
- `[ICNC-FSKD 2019]` Towards Data-Driven Automatic Video Editing [[paper]](https://arxiv.org/abs/1907.07345) 🎬
- `[CVPR 2018 Workshop]` The Excitement of Sports: Automatic Highlights Using Audio/Visual Cues [[paper]](https://openaccess.thecvf.com/content_cvpr_2018_workshops/w49/html/Merler_The_Excitement_of_CVPR_2018_paper.html) 🏌️🎾
- `[CVPR 2013]` Story-Driven Summarization for Egocentric Video [[paper]](https://openaccess.thecvf.com/content_cvpr_2013/html/Lu_Story-Driven_Summarization_for_2013_CVPR_paper.html)
- `[MM 2003]` AVE: automated home video editing [[paper]](https://dl.acm.org/doi/abs/10.1145/957013.957121)

<br/>

## Other Forms of Editing
- `[arxiv 2024]` MatchDiffusion: Training-free Generation of Match-cuts [[paper]](https://arxiv.org/abs/2411.18677) [[project page]](https://matchdiffusion.github.io/)
- `[arxiv 2024]` VCoME: Verbal Video Composition with Multimodal Editing Effects [[paper]](https://arxiv.org/abs/2407.04697) [[code]](https://github.com/LetsGoFir/VCoME) 💬
- `[CHI 2024]` ChunkyEdit: Text-first video interview editing via chunking [[paper]](https://dl.acm.org/doi/10.1145/3613904.3642667) 💬
- `[IUI 2024]` ExpressEdit: Video Editing with Natural Language and Sketching [[paper]](https://arxiv.org/abs/2403.17693) [[code]](https://github.com/fesiib/video-editing-pipeline) [[project page]](https://expressedit.kixlab.org/)
- `[UIST 2023]` Automated Conversion of Music Videos into Lyric Videos [[paper]](https://arxiv.org/abs/2308.14922) [[project page]](https://majiaju.io/lyric-video)
- `[NeurIPS 2022 Workshop]` VideoMap: Video Editing in Latent Space [[paper]](https://arxiv.org/abs/2211.12492) [[project page]](https://chuanenlin.com/videomap)
- `[ECCV 2022]` AutoTransition: Learning to Recommend Video Transition Effects [[paper]](https://arxiv.org/abs/2207.13479) [[code]](https://github.com/acherstyx/AutoTransition) [[dataset]](https://drive.google.com/file/d/179r-bRu9trSgqh4ejhyplfFKO2ta98BT/view?usp=sharing)
- `[IJCAI 2020 Demonstrations Track]` An AI-Empowered Visual Storyline Generator [[paper]](https://dl.acm.org/doi/abs/10.5555/3491440.3492205) 🛒
- `[AAAI 2020 Student Abstract]` Generating Engaging Promotional Videos for E-commerce Platforms [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/7205) 🛒
- `[UIST 2020]` Automatic Video Creation From a Web Page [[paper]](https://dl.acm.org/doi/abs/10.1145/3379337.3415814)
- `[TOM 2020]` AutoFoley: Artificial Synthesis of Synchronized Sound Tracks for Silent Videos With Deep Learning [[paper]](https://arxiv.org/abs/2002.10981)
- `[CHI 2019]` B-Script: Transcript-based B-roll Video Editing with Recommendations [[paper]](https://dl.acm.org/doi/pdf/10.1145/3290605.3300311)
### Fast-Forwarding & Retiming
**To change the video speed.**
- `[PRL 2023]` A Multimodal Hyperlapse Method Based on Video and Songs' Emotion Alignment [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0167865522002537)
- `[TPAMI 2023]` Text-Driven Video Acceleration: A Weakly-Supervised Reinforcement Learning Method [[paper]](https://arxiv.org/abs/2203.15778) [[project page]](https://www.verlab.dcc.ufmg.br/semantic-hyperlapse/tpami2022/)
- `[CVPR 2022 Workshop]` Video-ReTime: Learning Temporally Varying Speediness for Time Remapping [[paper]](https://arxiv.org/abs/2205.05609)
- `[TPAMI 2020]` A Sparse Sampling-Based Framework for Semantic Fast-Forward of First-Person Videos [[paper]](https://arxiv.org/abs/2009.11063)
- `[MM 2020]` Automated Aesthetic Enhancement of Videos [[paper]](https://dl.acm.org/doi/abs/10.1145/1873951.1873991) 💃
- `[CVPR 2018]` A Weighted Sparse Sampling and Smoothing Frame Transition Approach for Semantic Fast-Forward First-Person Videos [[paper]](https://arxiv.org/abs/1802.08722) [[project page]](https://www.verlab.dcc.ufmg.br/semantic-hyperlapse/)
- `[ECCV 2016 Workshop]` Towards Semantic Fast-Forward and Stabilized Egocentric Videos [[paper]](https://arxiv.org/abs/1708.04146)
- `[ICIP 2016]` Fast-Forward Video Based on Semantic Extraction [[paper]](https://arxiv.org/abs/1708.04160)
- `[TOG 2015]` Real-Time Hyperlapse Creation via Optimal Frame Selection [[paper]](https://dl.acm.org/doi/abs/10.1145/2766954)
- `[TOG 2014]` First-Person Hyper-Lapse Videos [[paper]](https://dl.acm.org/doi/abs/10.1145/2601097.2601195)
### Music-Driven Editing
- `[arxiv 2023]` AutoMatch: A Large-scale Audio Beat Matching Benchmark for Boosting Deep Learning Assistant Video Editing [[paper]](https://arxiv.org/abs/2303.01884)
- `[SIBGRAPI 2021]` Musical Hyperlapse: A Multimodal Approach to Accelerate First-Person Videos [[paper]](https://www.computer.org/csdl/proceedings-article/sibgrapi/2021/235400a184/1zurthy1oJ2)
- `[CVPR 2018 Workshop]` Visual Rhythm and Beat [[paper]](https://openaccess.thecvf.com/content_cvpr_2018_workshops/w49/html/Davis_Visual_Rhythm_and_CVPR_2018_paper.html)
- `[TOG 2015]` audeosynth: Music-Driven Video Montage [[paper]](https://dl.acm.org/doi/abs/10.1145/2766966)
### Spatial Editing
**To crop the video based on actionness, aesthetics, etc.**
- `[arxiv 2024]` Reframe Anything: LLM Agent for Open World Video Reframing [[paper]](https://arxiv.org/abs/2403.06070)
- `[WACV 2024]` Real Time GAZED: Online Shot Selection and Editing of Virtual Cameras from Wide-Angle Monocular Video Recordings [[paper]](https://arxiv.org/abs/2311.15581)
- `[CVPR 2020 Workshop]` As Seen on TV: Automatic Basketball Video Production Using Gaussian-Based Actionness and Game States Recognition [[paper]](https://openaccess.thecvf.com/content_CVPRW_2020/html/w53/Quiroga_As_Seen_on_TV_Automatic_Basketball_Video_Production_Using_Gaussian-Based_CVPRW_2020_paper.html) [[project page]]( https://gsbasketball.github.io) 🏀
- `[CHI 2020]` GAZED– Gaze-guided Cinematic Editing of Wide-Angle Monocular Video Recordings [[paper]](https://dl.acm.org/doi/abs/10.1145/3313831.3376544) 💃
- `[SA 2017 Poster]` Aesthetic Temporal and Spatial Editing of Casual Videos [[paper]](https://dl.acm.org/doi/abs/10.1145/3145690.3145733)
### Video Editing Styles Transfer
**To extract the editing styles in a source video and apply them to other video footages.**
- `[CVPR 2023]` JAWS: Just A Wild Shot for Cinematic Transfer in Neural Radiance Fields [[paper]](https://arxiv.org/abs/2303.15427) [[project page]](https://www.lix.polytechnique.fr/vista/projects/2023_cvpr_wang/)
- `[CVPR 2021 Workshop]` Editing Like Humans: A Contextual, Multimodal Framework for Automated Video Editing [[paper]](https://openaccess.thecvf.com/content/CVPR2021W/MULA/html/Koorathota_Editing_Like_Humans_A_Contextual_Multimodal_Framework_for_Automated_Video_CVPRW_2021_paper.html) [[project page]](http://cmve.foveainsights.com/) 💬
- `[CVPR 2021 Workshop]` Automatic Non-Linear Video Editing Transfer [[paper]](https://arxiv.org/abs/2105.06988)
### Virtual Cinematography
- `[CVPR 2024]` Cinematic Behavior Transfer via NeRF-based Differentiable Filming [[paper]](https://arxiv.org/abs/2311.17754) [[project page]](https://virtualfilmstudio.github.io/projects/cinetransfer)
- `[SIGGRAPH 2023 Poster]` Dynamic Storyboard Generation in an Engine-based Virtual Environment for Video Production [[paper]](https://arxiv.org/abs/2301.12688) [[project page]](https://virtualfilmstudio.github.io/)
- `[CHI 2021]` Virtual Camera Layout Generation using a Reference Video [[paper]](https://dl.acm.org/doi/abs/10.1145/3411764.3445437)
- `[TOMCCAP 2018]` Thinking Like a Director: Film Editing Patterns for Virtual Cinematographic Storytelling [[paper]](https://dl.acm.org/doi/abs/10.1145/3241057)
<br/>

## Datasets And More
**Datasets and papers related to video editing, camera movement🎥, shot type🖼️, etc.**
- `[CVPR 2025]` VEU-Bench: Towards Comprehensive Understanding of Video Editing [[paper]](https://arxiv.org/abs/2504.17828) [[project page]](https://labazh.github.io/VEU-Bench.github.io/)
- `[arxiv 2024]` Edit3K: Universal Representation Learning for Video Editing Components [[paper]](https://arxiv.org/abs/2403.16048) [[code]](https://github.com/GX77/Edit3K) [[dataset]](https://huggingface.co/datasets/Gstar666/Edit3K)
- `[CVPR 2024]` Neighbor Relations Matter in Video Scene Detection [[paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Tan_Neighbor_Relations_Matter_in_Video_Scene_Detection_CVPR_2024_paper.pdf) [[code]](https://github.com/ExMorgan-Alter/NeighborNet)
- `[WACV 2024]` Movie Genre Classification by Language Augmentation and Shot Sampling [[paper]](https://arxiv.org/abs/2203.13281) [[code]](https://github.com/Zhongping-Zhang/Movie-CLIP) 🎬
- `[IMXw 2023]` Recognition of Camera Angle and Camera Level in Movies from Single Frames [[paper]](https://dl.acm.org/doi/fullHtml/10.1145/3604321.3604334) [[project page]](https://cinescale.github.io/camera_al/) 🎬🖼️
- `[ICCV 2023 Workshop]` LEMMS: Label Estimation of Multi-feature Movie Segments [[paper]](https://openaccess.thecvf.com/content/ICCV2023W/CVEU/html/Vacchetti_LEMMS_Label_Estimation_of_Multi-Feature_Movie_Segments_ICCVW_2023_paper.html) 🎬🖼️
- `[ICCV 2023]` Long-range Multimodal Pretraining for Movie Understanding [[paper]](https://arxiv.org/abs/2308.09775) 🎬
- `[ECCV 2022 Workshop]` Movie Lens: Discovering and Characterizing Editing Patterns in the Analysis of Short Movie Sequences [[paper]](https://dl.acm.org/doi/abs/10.1007/978-3-031-25069-9_42) 🎬
- `[ECCV 2022]` The Anatomy of Video Editing: A Dataset and Benchmark Suite for AI-Assisted Video Editing [[paper]](http://arxiv.org/abs/2207.09812) [[code & dataset]](https://github.com/dawitmureja/AVE) 🎬🎥🖼️
- `[ECCV 2022]` MovieCuts: A New Dataset and Benchmark for Cut Type Recognition [[paper]](https://arxiv.org/abs/2109.05569) [[code & dataset]](https://github.com/PardoAlejo/MovieCuts) 🎬
- `[ICIP 2022]` HISTORIAN: A Large-Scale HISTORIcal Film Dataset with Cinematographic ANnotation [[paper]](https://x.sci-hub.org.cn/target?link=https://www.vhh-project.eu/wp-content/uploads/VHH_Publication_HELM-Daniel_Historian_2022.pdf) [[code & dataset]](https://github.com/dahe-cvl/historian_dataset) 🎬🎥
- `[ICIS Fall 2021]` RO-TextCNN Based MUL-MOVE-Net for Camera Motion Classification [[paper]](https://ieeexplore.ieee.org/abstract/document/9627386) [[code & dataset]](https://github.com/YMediaLab/Auto-Montage) 🎥
- `[ICCV 2021 Workshop]` High-Level Features for Movie Style Understanding [[paper]](https://hal.archives-ouvertes.fr/hal-03381587/) 🎬🎥
- `[ECCV 2020]` MovieNet: A Holistic Dataset for Movie Understanding [[paper]](https://arxiv.org/pdf/2007.10937.pdf) [[code]](https://github.com/movienet) [[project page & dataset]](https://movienet.github.io/) 🎬🎥🖼️
- `[ECCV 2020]` A Unified Framework for Shot Type Classification Based on Subject Centric Lens [[paper]](http://arxiv.org/abs/2008.03548) [[project page & dataset]](https://anyirao.com/projects/ShotType.html) 🎬🎥🖼️
- `[ICIP 2011]` Using Context Saliency For Movie Shot Classification [[paper]](http://www.nlpr.ia.ac.cn/2011papers/gjhy/gh121.pdf) 🎬🖼️
