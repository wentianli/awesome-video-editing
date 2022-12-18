# awesome-video-editing [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A paper list of automatic video editing and its related computer vision tasks.

I use some icons to mark several frequent application scenarios: 💬(talking/meeting), 💃(dancing/performance), 🛒(advertisement/promotional videos), 🎬(movie), etc.  
The papers are put into categories, and unavoidably there is some overlapping and imprecision.

*Note: This paper list does not include the works on image/video manipulation (e.g. content editing, object removal, video stylization).*


## Datasets
- `[ECCV 2022]` The Anatomy of Video Editing: A Dataset and Benchmark Suite for AI-Assisted Video Editing [[paper]](http://arxiv.org/abs/2207.09812)
- `[ECCV 2022]` MovieCuts: A New Dataset and Benchmark for Cut Type Recognition [[paper]](https://arxiv.org/abs/2109.05569) [[code]](https://github.com/PardoAlejo/MovieCuts)🎬
- `[ECCV 2020]` MovieNet: A Holistic Dataset for Movie Understanding [[paper]](https://arxiv.org/pdf/2007.10937.pdf) [[code]](https://github.com/movienet) [[project page & dataset]](https://movienet.github.io/) 🎬

<br/>

## Text-based Video Editing
#### Using texts as input to automatically create video sequences from a collection of videos or images.
- `[MM 2022]` Transcript to Video: Efficient Clip Sequencing from Texts [[paper]](https://arxiv.org/abs/2107.11851) [[project page]](http://www.xiongyu.me/projects/transcript2video/)
- `[CHI 2020]` Generating Audio-Visual Slideshows from Text Articles Using Word Concreteness [[paper]](https://dl.acm.org/doi/abs/10.1145/3313831.3376519)
- `[TOG 2019]` Write-A-Video: Computational Video Montage from Themed Text [[paper]](https://dl.acm.org/doi/abs/10.1145/3355089.3356520)
- `[TMM 2020]` Story-driven Video Editing [[paper]](https://ieeexplore.ieee.org/abstract/document/9257101)
- `[IMX 2020]` Joint Attention for Automated Video Editing [[paper]](https://dl.acm.org/doi/abs/10.1145/3391614.3393656) 💬
- `[UIST 2016]` QuickCut: An Interactive Tool for Editing Narrated Video [[paper]](https://dl.acm.org/doi/abs/10.1145/2984511.2984569)
#### Modifying the transcript of a speech to change the speech content or to remove filler words.
- `[TOG 2019]` Text-based Editing of Talking-head Video [[paper]](https://dl.acm.org/doi/abs/10.1145/3306346.3323028) 💬

<br/>

## Cutting and Sequencing Shots
#### To cut unedited videos into shots and to put them in an appropriate order.
- `[arxiv 2022]` Match Cutting: Finding Cuts with Smooth Visual Transitions [[paper]](https://arxiv.org/abs/2210.05766) [[code]](https://github.com/netflix/matchcut) [[project page]](https://netflixtechblog.com/match-cutting-at-netflix-finding-cuts-with-smooth-visual-transitions-31c3fc14ae59?gi=8873f373fd1d) 🎬
- `[SAC 2022]` Automated Video Editing Based on Learned Styles Using LSTM-GAN [[paper]](https://dl.acm.org/doi/abs/10.1145/3477314.3507141) 💃
- `[ICCV 2021 Workshop]` Learning Where To Cut From Edited Videos [[paper]](https://openaccess.thecvf.com/content/ICCV2021W/CVEU/html/Huang_Learning_Where_To_Cut_From_Edited_Videos_ICCVW_2021_paper.html)
- `[ICCV 2021]` Learning to Cut by Watching Movies [[paper]](https://arxiv.org/abs/2108.04294) [[code & dataset]](https://github.com/PardoAlejo/LearningToCut) [[project page]](https://www.alejandropardo.net/publication/learning-to-cut/)
- `[WACV 2018]` Learning Video-Story Composition via Recurrent Neural Network [[paper]](https://arxiv.org/abs/1801.10281)
- `[CVPR 2016]` Video-Story Composition via Plot Analysis [[paper]](https://openaccess.thecvf.com/content_cvpr_2016/html/Choi_Video-Story_Composition_via_CVPR_2016_paper.html)

<br/>

## Multi-Camera / Multi-Take Editing
#### To select video shots from multiple camera views or multiple takes of the same event.
- `[TOG 2022]` PopStage: The Generation of Stage Cross-Editing Video Based on Spatio-Temporal Matching [[paper]](https://dl.acm.org/doi/abs/10.1145/3550454.3555467) [[project page]](https://w-dlee.github.io/popstage) 💃
- `[ECCV 2022 Workshop]` Temporal and Contextual Transformer for Multi-Camera Editing of TV Shows [[paper]](https://arxiv.org/abs/2210.08737)
- `[ICME 2021]` Reinforcement Learning Based Automatic Personal Mashup Generation [[paper]](https://www.computer.org/csdl/proceedings-article/icme/2021/09428357/1uim1GOOhtC)
- `[TOMCCAP 2021]` Smart Director: An Event-Driven Directing System for Live Broadcasting [[paper]](https://dl.acm.org/doi/full/10.1145/3448981) ⚽
- `[TOG 2017]` Computational Video Editing for Dialogue-Driven Scenes [[paper]](https://dl.acm.org/doi/abs/10.1145/3072959.3073653) 💬
- `[ACE 2017]` Automatic System for Editing Dance Videos Recorded Using Multiple Cameras [[paper]](https://link.springer.com/chapter/10.1007/978-3-319-76270-8_47) 💃
- `[TOG 2014]` Automatic Editing of Footage from Multiple Social Cameras [[paper]](https://dl.acm.org/doi/abs/10.1145/2601097.2601198)
- `[ICME 2007]` Automatic Multi-Modal Meeting Camera Selection for Video-Conferences and Meeting Browsers [[paper]](https://ieeexplore.ieee.org/abstract/document/4285090) 💬

<br/>

## Video Summarization & Highlight Detection
- `[AutomotiveUI 2021]` Automatic Generation of Road Trip Summary Video for Reminiscence and Entertainment using Dashcam Video [[paper]](https://dl.acm.org/doi/abs/10.1145/3409118.3475151)
- `[MM 2021]` Automated Multi-Modal Video Editing for Ads Video [[paper]](https://dl.acm.org/doi/abs/10.1145/3474085.3479205) 🛒
- `[MM 2021]` VideoDiscovery: An Automatic Short-Video Generation System for E-commerce Live-streaming [[paper]](https://dl.acm.org/doi/abs/10.1145/3474085.3478554) [[project page]](https://discovery.aliyun.com/index#/) 🛒
- `[MMAsia 2019]` Domain Specific and Idiom Adaptive Video Summarization [[paper]](https://dl.acm.org/doi/abs/10.1145/3338533.3366603) 🛒
- `[MM 2019]` Personalized Video Summarization with Idiom Adaptation [[paper]](https://dl.acm.org/doi/pdf/10.1145/3343031.3350584) 🛒
- `[MM 2019]` Generating 1 Minute Summaries of Day Long Egocentric Videos [[paper]](https://dl.acm.org/doi/abs/10.1145/3343031.3350880) [[code]](https://github.com/anuj-rathore/Generating-One-Minute-Summaries)
- `[TMM 2019]` Automatic Curation of Sports Highlights Using Multimodal Excitement Features [[paper]](https://ieeexplore.ieee.org/abstract/document/8491305) 🏌️🎾
- `[ICNC-FSKD 2019]` Towards Data-Driven Automatic Video Editing [[paper]](https://arxiv.org/abs/1907.07345) 🎬
- `[CVPR 2018 Workshop]` The Excitement of Sports: Automatic Highlights Using Audio/Visual Cues [[paper]](https://openaccess.thecvf.com/content_cvpr_2018_workshops/w49/html/Merler_The_Excitement_of_CVPR_2018_paper.html) 🏌️🎾
- `[CVPR 2013]` Story-Driven Summarization for Egocentric Video [[paper]](https://openaccess.thecvf.com/content_cvpr_2013/html/Lu_Story-Driven_Summarization_for_2013_CVPR_paper.html)
- `[MM 2003]` AVE: automated home video editing [[paper]](https://dl.acm.org/doi/abs/10.1145/957013.957121)


<br/>

## Fast-Forwarding & Retiming
#### To change the video speed.
- `[CVPR 2022 Workshop]` Video-ReTime: Learning Temporally Varying Speediness for Time Remapping [[paper]](https://arxiv.org/abs/2205.05609)
- `[TPAMI 2020]` A Sparse Sampling-Based Framework for Semantic Fast-Forward of First-Person Videos [[paper]](https://arxiv.org/abs/2009.11063)
- `[CVPR 2018]` A Weighted Sparse Sampling and Smoothing Frame Transition Approach for Semantic Fast-Forward First-Person Videos [[paper]](https://arxiv.org/abs/1802.08722) [[project page]](https://www.verlab.dcc.ufmg.br/semantic-hyperlapse/)
- `[MM 2020]` Automated Aesthetic Enhancement of Videos [[paper]](https://dl.acm.org/doi/abs/10.1145/1873951.1873991) 💃

<br/>

## Music-Driven Editing
- `[CVPR 2018 Workshop]` Visual Rhythm and Beat [[paper]](https://openaccess.thecvf.com/content_cvpr_2018_workshops/w49/html/Davis_Visual_Rhythm_and_CVPR_2018_paper.html)
- `[TOG 2015]` audeosynth: Music-Driven Video Montage [[paper]](https://dl.acm.org/doi/abs/10.1145/2766966)

<br/>

## Spatial Editing
#### To crop the video based on actionness, aesthetics, etc.
- `[CVPR 2020 Workshop]` Production Using Gaussian-Based Actionness and Game States Recognition [[paper]](https://openaccess.thecvf.com/content_CVPRW_2020/html/w53/Quiroga_As_Seen_on_TV_Automatic_Basketball_Video_Production_Using_Gaussian-Based_CVPRW_2020_paper.html) [[project page]]( https://gsbasketball.github.io) 🏀
- `[CHI 2020]` GAZED– Gaze-guided Cinematic Editing of Wide-Angle Monocular Video Recordings [[paper]](https://dl.acm.org/doi/abs/10.1145/3313831.3376544) 💃
- `[SA 2017 Poster]` Aesthetic Temporal and Spatial Editing of Casual Videos [[paper]](https://dl.acm.org/doi/abs/10.1145/3145690.3145733)

<br/>

## Video Editing Styles Transfer
#### To extract the editing styles in a source video and apply them to other video footages.
- `[CVPR 2021 Workshop]` Editing Like Humans: A Contextual, Multimodal Framework for Automated Video Editing [[paper]](https://openaccess.thecvf.com/content/CVPR2021W/MULA/html/Koorathota_Editing_Like_Humans_A_Contextual_Multimodal_Framework_for_Automated_Video_CVPRW_2021_paper.html) [[project page]](http://cmve.foveainsights.com/) 💬
- `[CVPR 2021 Workshop]` Automatic Non-Linear Video Editing Transfer [[paper]](https://arxiv.org/abs/2105.06988)

<br/>

## Virtual Cinematography
- `[CHI 2021]` Virtual Camera Layout Generation using a Reference Video [[paper]](https://dl.acm.org/doi/abs/10.1145/3411764.3445437)
- `[TOMCCAP 2018]` Thinking Like a Director: Film Editing Patterns for Virtual Cinematographic Storytelling [[paper]](https://dl.acm.org/doi/abs/10.1145/3241057)

<br/>

## Other
- `[ECCV 2022]` AutoTransition: Learning to Recommend Video Transition Effects [[paper]](https://arxiv.org/abs/2207.13479) [[code]](https://github.com/acherstyx/AutoTransition) [[dataset]](https://drive.google.com/file/d/179r-bRu9trSgqh4ejhyplfFKO2ta98BT/view?usp=sharing)
- `[IJCAI 2020 Demonstrations Track]` An AI-Empowered Visual Storyline Generator [[paper]](https://dl.acm.org/doi/abs/10.5555/3491440.3492205) 🛒
- `[AAAI 2020 Student Abstract]` Generating Engaging Promotional Videos for E-commerce Platforms [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/7205) 🛒
- `[UIST 2020]` Automatic Video Creation From a Web Page [[paper]](https://dl.acm.org/doi/abs/10.1145/3379337.3415814)
- `[CHI 2019]` B-Script: Transcript-based B-roll Video Editing with Recommendations [[paper]](https://dl.acm.org/doi/pdf/10.1145/3290605.3300311)
