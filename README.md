# Machine Learning Engineer Nanodegree
### Capstone Proposal
Vasudev Kartheek Akkur

April 6th, 2019

### Proposal
#### Domain Background

In this Project I will be working the Retinal Optical Coherence Tomography and how it is used to detect different retinal diseases.
Optical coherence tomography (OCT) is a non-invasive imaging test. OCT uses light waves to take cross-section pictures of your retina.
With OCT, your ophthalmologist can see each of the retina’s distinctive layers.  This allows your ophthalmologist to map and measure their thickness. These measurements help with diagnosis. They also provide treatment guidance for glaucoma and diseases of the retina. These retinal diseases include age-related macular degeneration (AMD) and diabetic eye disease.
Retinal optical coherence tomography (OCT) is an imaging technique used to capture high-resolution cross sections of the retinas of living patients. Approximately 30 million OCT scans are performed each year, and the analysis and interpretation of these images takes up a significant amount of time (Swanson and Fujimoto, 2017).

![fSTeZMd](https://user-images.githubusercontent.com/43079315/55676086-11962480-5893-11e9-8447-09a4dc0df3b5.png)
 
(A) (Far left) choroidal neovascularization (CNV) with neovascular membrane (white arrowheads) and associated subretinal fluid (arrows). (Middle left) Diabetic macular edema (DME) with retinal-thickening-associated intraretinal fluid (arrows). (Middle right) Multiple drusen (arrowheads) present in early AMD. (Far right) Normal retina with preserved foveal contour and absence of any retinal fluid/edema.

#### Citations:
Mooney, Paul. “Retinal OCT Images (Optical Coherence Tomography).” Kaggle, 25 Mar. 2018, www.kaggle.com/paultimothymooney/kermany2018.
“Optical Coherence Tomography.” EyeWiki, 20 Jan. 2015, eyewiki.aao.org/Optical_Coherence_Tomography.
Kermany, D.S., Goldbaum, M., Cai, W., Valentim, C.C.S., Liang, H., Baxter, S.L., McKeown, A., Yang, G., Wu, X., Yan, F., Dong, J., Prasadha, M.K., Pei, J., Ting, M.Y.L., Zhu, J., Li, C., Hewett, S., Dong, J., Ziyar, I., Shi, A., Zhang, R., Zheng, L., Hou, R., Shi, W., Fu, X., Duan, Y., Huu, V.A.N., Wen, C., Zhang, E.D., Zhang, C.L., Li, O., Wang, X., Singer, M.A., Sun, X., Xu, J., Tafreshi, A., Lewis, M.A., Xia, H. and Zhang, K. (2018). Identifying Medical Diagnoses and Treatable Diseases by Image-Based Deep Learning. Cell, [online] 172(5), p.1122–1131.e9. Available at: https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5 [Accessed 6 Apr. 2019].


#### Dataset and Inputs

The dataset is organized into 3 folders (train, test, Val) and contains subfolders for each image category (NORMAL, CNV, DME, DRUSEN). There are 84,495 X-Ray images (JPEG) and 4 categories (NORMAL, CNV, DME, DRUSEN).
Images are labeled as (disease)-(randomized patient ID) -(image number by this patient) and split into 4 directories: CNV, DME, DRUSEN, and NORMAL.

Optical coherence tomography (OCT) images (Spectralis OCT, Heidelberg Engineering, Germany) were selected from retrospective cohorts of adult patients from the Shiley Eye Institute of the University of California San Diego, the California Retinal Research Foundation, Medical Center Ophthalmology Associates, the Shanghai First People’s Hospital, and Beijing Tongren Eye Center between July 1, 2013 and March 1, 2017.

Dataset: Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification

http://dx.doi.org/10.17632/rscbjbr9sj.2#file-9e8f7acf-7d3a-487f-8eb5-0bd3255b9685


https://www.kaggle.com/paultimothymooney/kermany2018

