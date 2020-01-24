# Papers on Explainable Artificial Intelligence

This is an on-going attempt to consolidate interesting efforts in the area of understanding / interpreting / explaining / visualizing *a pre-trained ML model*.

---------------------------------------

# GUI tools
* DeepVis: Deep Visualization Toolbox. _Yosinski et al. 2015_ [code](https://github.com/yosinski/deep-visualization-toolbox) | [pdf](http://yosinski.com/deepvis)
* SWAP: Generate adversarial poses of objects in a 3D space. _Alcorn et al. 2018_ [code](https://github.com/airalcorn2/strike-with-a-pose) | [pdf](https://arxiv.org/abs/1811.11553)

# Libraries
* [CNN visualizations](https://github.com/utkuozbulak/pytorch-cnn-visualizations) (activation maximization, PyTorch)
* [iNNvestigate](https://github.com/albermax/innvestigate) (heatmaps, Keras)
* [DeepExplain](https://github.com/marcoancona/DeepExplain) (heatmaps, Keras)
* [Lucid](https://github.com/tensorflow/lucid) (activation maximization, heatmaps, Tensorflow)

# Surveys
* Methods for Interpreting and Understanding Deep Neural Networks. _Montavon et al. 2017_ [pdf](https://arxiv.org/pdf/1706.07979.pdf)
* Visualizations of Deep Neural Networks in Computer Vision: A Survey. _Seifert et al. 2017_ [pdf](https://link.springer.com/chapter/10.1007/978-3-319-54024-5_6)
* How convolutional neural network see the world - A survey of convolutional neural network visualization methods. _Qin et al. 2018_ [pdf](https://arxiv.org/abs/1804.11191)
* A brief survey of visualization methods for deep learning models from the perspective of Explainable AI. _Chalkiadakis 2018_ [pdf](https://www.macs.hw.ac.uk/~ic14/IoannisChalkiadakis_RRR.pdf)
* A Survey Of Methods For Explaining Black Box Models. _Guidotti et al. 2018_ [pdf](https://arxiv.org/pdf/1802.01933.pdf)
* Understanding Neural Networks via Feature Visualization: A survey. _Nguyen et al. 2019_ [pdf](https://arxiv.org/pdf/1904.08939.pdf)
* Explaining Explanations: An Overview of Interpretability of Machine Learning. _Gilpin et al. 2019_ [pdf](https://arxiv.org/pdf/1806.00069.pdf)
* DARPA updates on the XAI program [pdf](https://www.darpa.mil/attachments/XAIProgramUpdate.pdf)
* A Survey on Explainable Artificial Intelligence (XAI): towards Medical XAI. _Toja et al. [pdf](https://arxiv.org/pdf/1907.07374.pdf)

#### Definitions of Interpretability
* The Mythos of Model Interpretability. _Lipton 2016_ [pdf](https://arxiv.org/abs/1606.03490)
* Towards A Rigorous Science of Interpretable Machine Learning. _Doshi-Velez & Kim. 2017_ [pdf](https://arxiv.org/pdf/1702.08608.pdf)
* Interpretable machine learning: definitions, methods, and applications. _Murdoch et al. 2019_ [pdf](https://arxiv.org/pdf/1901.04592v1.pdf)

#### Books
* A Guide for Making Black Box Models Explainable. _Molnar 2019_ [pdf](https://christophm.github.io/interpretable-ml-book/)

# A. Explaining inner-workings

## A1. Visualizing Preferred Stimuli

#### Synthesizing images / Activation Maximization
* AM: Visualizing higher-layer features of a deep network. _Erhan et al. 2009_ [pdf](https://www.researchgate.net/publication/265022827_Visualizing_Higher-Layer_Features_of_a_Deep_Network)
* Deep inside convolutional networks: Visualising image classification models and saliency maps. _Simonyan et al. 2013_ [pdf](https://arxiv.org/pdf/1312.6034.pdf)
* DeepVis: Understanding Neural Networks through Deep Visualization. _Yosinski et al. 2015_ [pdf](http://yosinski.com/media/papers/Yosinski__2015__ICML_DL__Understanding_Neural_Networks_Through_Deep_Visualization__.pdf) | [url](http://yosinski.com/deepvis)
* MFV: Multifaceted Feature Visualization: Uncovering the different types of features learned by each neuron in deep neural networks. _Nguyen et al. 2016_ [pdf](http://www.evolvingai.org/files/mfv_icml_workshop_16.pdf) | [code](https://github.com/Evolving-AI-Lab/mfv)
* DGN-AM: Synthesizing the preferred inputs for neurons in neural networks via deep generator networks. _Nguyen et al. 2016_ [pdf](anhnguyen.me/project/synthesizing) | [code](https://github.com/Evolving-AI-Lab/synthesizing)
* PPGN: Plug and Play Generative Networks. _Nguyen et al. 2017_ [pdf](anhnguyen.me/project/ppgn/) | [code](https://github.com/Evolving-AI-Lab/ppgn)
* Feature Visualization. _Olah et al. 2017_ [url](https://distill.pub/2017/feature-visualization)
* Diverse feature visualizations reveal invariances in early layers of deep neural networks. _Cadena et al. 2018_ [pdf](https://arxiv.org/pdf/1807.10589.pdf)
* Computer Vision with a Single (Robust) Classifier. _Santurkar et al. 2019_ [pdf](https://arxiv.org/abs/1906.09453) | [blog](http://gradsci.org/robust_apps) | [code](https://github.com/MadryLab/robustness_applications)
* BigGAN-AM: Improving sample diversity of a pre-trained, class-conditional GAN by changing its class embeddings. _Li et al. 2019_ [pdf](https://arxiv.org/abs/1910.04760)

#### Real images / Segmentation Masks
* Visualizing and Understanding Recurrent Networks. _Kaparthey et al. 2015_ [pdf](https://arxiv.org/abs/1506.02078)
* Object Detectors Emerge in Deep Scene CNNs. Zhou et al. 2015 [pdf](https://arxiv.org/abs/1412.6856)
* Understanding Deep Architectures by Interpretable Visual Summaries [pdf](https://arxiv.org/pdf/1801.09103.pdf)

## A2. Inverting Neural Networks
* Understanding Deep Image Representations by Inverting Them [pdf](https://arxiv.org/abs/1412.0035)
* Inverting Visual Representations with Convolutional Networks [pdf](https://arxiv.org/abs/1506.02753)
* Neural network inversion beyond gradient descent [pdf](http://opt-ml.org/papers/OPT2017_paper_38.pdf)

## A3. Distilling DNNs into more interpretable models
* Interpreting CNNs via Decision Trees [pdf](https://arxiv.org/abs/1802.00121)
* Distilling a Neural Network Into a Soft Decision Tree [pdf](https://arxiv.org/abs/1711.09784)
* Distill-and-Compare: Auditing Black-Box Models Using Transparent Model Distillation. _Tan et al. 2018_ [pdf](https://arxiv.org/abs/1710.06169)
* Improving the Interpretability of Deep Neural Networks with Knowledge Distillation. _Liu et al. 2018_ [pdf](https://arxiv.org/pdf/1812.10924.pdf)
* EDIT: Interpreting Ensemble Models via Compact Soft Decision Trees. _Yoo et al. 2019 (https://pdfs.semanticscholar.org/7a86/aaa70dc919af0d30eccc364583b9a09839c6.pdf?_ga=2.158361272.382053237.1579885022-681255730.1545175980)

## A4. Quantitatively characterizing hidden features
* TCAV: Interpretability Beyond Feature Attribution: Quantitative Testing with Concept Activation Vectors. _Kim et al. 2018_ [pdf](https://arxiv.org/abs/1711.11279) | [code](https://github.com/tensorflow/tcav)
  * Automating Interpretability: Discovering and Testing Visual Concepts Learned by Neural Networks. _Ghorbani et al. 2019_ [pdf](https://arxiv.org/abs/1902.03129)
* SVCCA: Singular Vector Canonical Correlation Analysis for Deep Learning Dynamics and Interpretability. _Raghu et al. 2017_ [pdf](https://arxiv.org/abs/1706.05806) | [code](https://github.com/google/svcca)
* A Peek Into the Hidden Layers of a Convolutional Neural Network Through a Factorization Lens. _Saini et al. 2018_ [pdf](https://arxiv.org/abs/1806.02012)
* Network Dissection: Quantifying Interpretability of Deep Visual Representations. _Bau et al. 2017_ [url](http://netdissect.csail.mit.edu/) | [pdf](http://netdissect.csail.mit.edu/final-network-dissection.pdf)
  * GAN Dissection: Visualizing and Understanding Generative Adversarial Networks. _Bau et al. 2018_ [pdf](https://arxiv.org/abs/1811.10597)
  * Net2Vec: Quantifying and Explaining how Concepts are Encoded by Filters in Deep Neural Networks. _Fong & Vedaldi 2018_ [pdf](https://arxiv.org/abs/1801.03454)


## A5. Network surgery
* How Important Is a Neuron? _Dhamdhere et al._ 2018 [pdf](https://arxiv.org/pdf/1805.12233.pdf)

## A6. Sensitivity analysis
* NLIZE: A Perturbation-Driven Visual Interrogation Tool for Analyzing and Interpreting Natural Language Inference Models. _Liu et al. 2018_ [pdf](http://www.sci.utah.edu/~shusenl/publications/paper_entailVis.pdf)


# B. Decision explanations

## B1. Attribution maps
### B1.1 White-box / Gradient-based

* A Taxonomy and Library for Visualizing Learned Features in Convolutional Neural Networks [pdf](https://arxiv.org/pdf/1606.07757.pdf)

#### Gradient
* Deep inside convolutional networks: Visualising image classification models and saliency maps. _Simonyan et al. 2013_ [pdf](https://arxiv.org/pdf/1312.6034.pdf)
* Deconvnet: Visualizing and understanding convolutional networks. _Zeiler et al. 2014_ [pdf](https://arxiv.org/pdf/1311.2901.pdf)
* Guided-backprop: Striving for simplicity: The all convolutional net. _Springenberg et al. 2015_ [pdf](http://arxiv.org/pdf/1412.6806.pdf)

#### Input x Gradient
* DeepLIFT: Learning important features through propagating activation differences. _Shrikumar et al. 2017_ [pdf](https://arxiv.org/pdf/1605.01713.pdf)
* Integrated Gradients: Axiomatic Attribution for Deep Networks. _Sundararajan et al. 2018_ [pdf](http://proceedings.mlr.press/v70/sundararajan17a/sundararajan17a.pdf) | [code](https://github.com/ankurtaly/Integrated-Gradients)
 * I-GOR: Visualizing Deep Networks by Optimizing with Integrated Gradients. _Qi et al. 2019_ [pdf](https://arxiv.org/pdf/1905.00954.pdf)
* LRP: Beyond saliency: understanding convolutional neural networks from saliency prediction on layer-wise relevance propagation [pdf](https://arxiv.org/abs/1712.08268)
  * DTD: Explaining NonLinear Classification Decisions With Deep Tayor Decomposition [pdf](https://arxiv.org/abs/1512.02479)
  
#### Activation map
* CAM: Learning Deep Features for Discriminative Localization. _Zhou et al. 2016_ [code](https://github.com/metalbubble/CAM) | [web](http://cnnlocalization.csail.mit.edu/)
* Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization. _Selvaraju et al. 2017_ [pdf](https://arxiv.org/abs/1610.02391)
* Grad-CAM++: Improved Visual Explanations for Deep Convolutional Networks. _Chattopadhyay et al. 2017_ [pdf](https://arxiv.org/abs/1710.11063) | [code](https://github.com/adityac94/Grad_CAM_plus_plus)
* Smooth Grad-CAM++: An Enhanced Inference Level Visualization Technique for Deep Convolutional Neural Network Models. _Omeiza et al. 2019_ [pdf](https://arxiv.org/pdf/1908.01224.pdf)

#### Learning the heatmap
* MP: Interpretable Explanations of Black Boxes by Meaningful Perturbation. _Fong et al. 2017_ [pdf](http://openaccess.thecvf.com/content_ICCV_2017/papers/Fong_Interpretable_Explanations_of_ICCV_2017_paper.pdf)
  * MP-G: Removing input features via a generative model to explain their attributions to classifier's decisions. _Agarwal et al. 2019_ [pdf](https://arxiv.org/abs/1910.04256) | [code](https://github.com/anguyen8/generative-attribution-methods)
  * Understanding Deep Networks via Extremal Perturbations and Smooth Masks. _Fong et al. 2019_ [pdf](https://arxiv.org/abs/1910.08485)
* FIDO: Explaining image classifiers by counterfactual generation. _Chang et al. 2019_ [pdf](https://arxiv.org/pdf/1807.08024.pdf)
* FG-Vis: Interpretable and Fine-Grained Visual Explanations for Convolutional Neural Networks. _Wagner et al. 2019_ [pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wagner_Interpretable_and_Fine-Grained_Visual_Explanations_for_Convolutional_Neural_Networks_CVPR_2019_paper.pdf)

 
#### Others 
* Visual explanation by interpretation: Improving visual feedback capabilities of deep neural networks. _Oramas et al. 2019_ [pdf](https://arxiv.org/pdf/1712.06302.pdf)
* Regional Multi-scale Approach for Visually Pleasing Explanations of Deep Neural Networks. _Seo et al. 2018_ [pdf](https://arxiv.org/pdf/1807.11720.pdf)b

### B1.2 Black-box / Perturbation-based
* Sliding-Patch: Visualizing and understanding convolutional networks. _Zeiler et al. 2014_ [pdf](https://arxiv.org/pdf/1311.2901.pdf)
* PDA: Visualizing deep neural network decisions: Prediction difference analysis. _Zintgraf et al. 2017_ [pdf](https://arxiv.org/pdf/1702.04595.pdf)
* RISE: Randomized Input Sampling for Explanation of Black-box Models. _Petsiuk et al. 2018_ [pdf](https://arxiv.org/pdf/1806.07421.pdf)
* LIME: Why should i trust you?: Explaining the predictions of any classifier. _Ribeiro et al. 2016_ [pdf](https://arxiv.org/pdf/1602.04938.pdf) | [blog](https://homes.cs.washington.edu/~marcotcr/blog/lime/)
  * LIME-G: Removing input features via a generative model to explain their attributions to classifier's decisions. _Agarwal et al. 2019_ [pdf](https://arxiv.org/abs/1910.04256) | [code](https://github.com/anguyen8/generative-attribution-methods)
* SHAP: A Unified Approach to Interpreting Model Predictions. _Lundberg et al. 2017_ [pdf](https://papers.nips.cc/paper/7062-a-unified-approach-to-interpreting-model-predictions.pdf) | [code](https://github.com/slundberg/shap)
* OSFT: Interpreting Black Box Models via Hypothesis Testing. _Burns et al. 2019_ [pdf](https://arxiv.org/pdf/1904.00045.pdf)

### B1.3 Evaluating heatmaps
* The (Un)reliability of saliency methods. _Kindermans et al. 2018_ [pdf](https://openreview.net/forum?id=r1Oen--RW)
* Sanity Checks for Saliency Maps. _Adebayo et al. 2018_ [pdf](http://papers.nips.cc/paper/8160-sanity-checks-for-saliency-maps.pdf)
* A Theoretical Explanation for Perplexing Behaviors of Backpropagation-based Visualizations. _Nie et al. 2018_ [pdf](https://arxiv.org/abs/1805.07039)
* BIM: Towards Quantitative Evaluation of Interpretability Methods with Ground Truth. _Yang et al. 2019_ [pdf](https://arxiv.org/abs/1907.09701)
* On the (In)fidelity and Sensitivity for Explanations. _Yeh et al. 2019_ [pdf](https://arxiv.org/pdf/1901.09392.pdf)
* BIM: Towards Quantitative Evaluation of Interpretability Methods with Ground Truth. _Yang et al. 2019 [pdf](https://arxiv.org/pdf/1907.09701.pdf) | 

## B2. Learning to explain
* Learning how to explain neural networks: PatternNet and PatternAttribution [pdf](https://arxiv.org/abs/1705.05598)
* Deep Learning for Case-Based Reasoning through Prototypes [pdf](https://arxiv.org/pdf/1710.04806.pdf)
* Unsupervised Learning of Neural Networks to Explain Neural Networks [pdf](https://arxiv.org/abs/1805.07468)
* Automated Rationale Generation: A Technique for Explainable AI and its Effects on Human Perceptions [pdf](https://arxiv.org/abs/1901.03729)
  * Rationalization: A Neural Machine Translation Approach to Generating Natural Language Explanations [pdf](https://arxiv.org/pdf/1702.07826.pdf)
* Towards robust interpretability with self-explaining neural networks. _Alvarez-Melis and Jaakola 2018_ [pdf](http://people.csail.mit.edu/tommi/papers/SENN_paper.pdf)  

# C. Counterfactual explanations
* Interpreting Neural Network Judgments via Minimal, Stable, and Symbolic Corrections. _Zhang et al. 2018_ [pdf](http://papers.nips.cc/paper/7736-interpreting-neural-network-judgments-via-minimal-stable-and-symbolic-corrections.pdf)
* Counterfactual Visual Explanations. _Goyal et al. 2019_ [pdf](https://arxiv.org/pdf/1904.07451.pdf)
* Generative Counterfactual Introspection for Explainable Deep Learning. _Liu et al. 2019_ [pdf](https://arxiv.org/abs/1907.03077)

#D. Using Attention for Training
* Squeeze-and-Excitation Networks. _Hu et al. 2017_ [pdf](https://arxiv.org/pdf/1709.01507.pdf)
* CBAM: Convolutional Block Attention Module. _Woo et al. 2018 [pdf](https://arxiv.org/pdf/1807.06521.pdf) | [code](https://github.com/Jongchan/attention-module/blob/master)
* Sharpen Focus: Learning with Attention Separability and Consistency. _Wang et al. 2019 [pdf](https://arxiv.org/pdf/1811.07484.pdf)
* Tell Me Where to Look: Guided Attention Inference Network. _Li et al. 2018 [pdf](https://arxiv.org/pdf/1802.10171.pdf) | [code](https://github.com/ngxbac/GAIN)
* Paying More Attention to Attention: Improving the Performance of Convolutional Neural Networks Via Attention Transfer _Zagoruyko et al. 2017 [pdf](https://openreview.net/pdf?id=Sks9_ajex)

# E. Others
* Yang, S. C. H., & Shafto, P. Explainable Artificial Intelligence via Bayesian Teaching. NIPS 2017 [pdf](http://shaftolab.com/assets/papers/yangShafto_NIPS_2017_machine_teaching.pdf)
* Explainable AI for Designers: A Human-Centered Perspective on Mixed-Initiative Co-Creation [pdf](http://www.antoniosliapis.com/papers/explainable_ai_for_designers.pdf)
* ICADx: Interpretable computer aided diagnosis of breast masses. _Kim et al. 2018_ [pdf](https://arxiv.org/abs/1805.08960)
* Neural Network Interpretation via Fine Grained Textual Summarization. _Guo et al. 2018_ [pdf](https://arxiv.org/pdf/1805.08969.pdf)
* LS-Tree: Model Interpretation When the Data Are Linguistic. _Chen et al. 2019_ [pdf](https://arxiv.org/abs/1902.04187)

