# awesome-synthetic-time-series

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of papers, methods and libraries implemented in Python for generating synthetic data from time series.

## Contents

* [Research Papers](#research-papers)
* [Libraries](#libraries)
* [Tutorials](#tutorials)
  * [Reading Content](#reading-content)
  * [Videos and Courses](#videos-and-online-courses)


## Research Papers

* [RGAN](https://arxiv.org/pdf/1706.02633.pdf) - Real-valued (Medical) Time Series Generation with Recurrent Conditional GANs. 
* [WaveGAN](https://arxiv.org/pdf/1802.04208.pdf) - WaveGAN, a ML algorithm that learns to synthesize raw waveform audio by examples of real audio.
* [TimeGAN](https://papers.nips.cc/paper/2019/file/c9efe5f26cd17ba6216bbe2a7d26d490-Paper.pdf) - A framework for generating realistic time-series by combining unsupervised and supervised training. 
* [DataAug](https://arxiv.org/pdf/1808.02455.pdf) - Data augmentation using synthetic data for time series classification with deep residual networks.
* [SICCWGAN](https://arxiv.org/pdf/2006.05421.pdf) - Conditional Sig-Wasserstein GANs for time series.
* [COT-GAN](https://proceedings.neurips.cc/paper/2020/file/641d77dd5271fca28764612a028d9c8e-Paper.pdf) - COT-GAN: Generating Sequential Data via Causal Optimal Transport.
* [DoppelGANger](https://dl.acm.org/doi/pdf/10.1145/3419394.3423643) - Generating High-fidelity, Synthetic Time Series Datasets with DoppelGANger.
* [BTGAN](https://doi.org/10.1016/j.neunet.2022.09.010) -  A novel bootstrap procedure for time series data based on Generative Adversarial networks (GANs).
* [STGAN](https://proceedings.neurips.cc/paper/2021/file/f2b4053221961416d47d497814a8064f-Paper.pdf) -  Time-series Generation by Contrastive Imitation.
* [HealthGen](https://arxiv.org/pdf/2201.08186.pdf) - A GAN to synthesize realistic EHR time series data with missingness.
* [EVA](https://proceedings.mlr.press/v149/biswal21a/biswal21a.pdf) - Variational Autoencoder (EVA) for synthesizing sequences of discrete EHR encounter
* [SynTEG](https://academic.oup.com/jamia/article-abstract/28/3/596/6024632) - SynTEG: a framework for temporal structured electronic health data simulation.
* [EHRMGAN](https://arxiv.org/pdf/2112.12047.pdf) - A GAN entitled EHR-M-GAN which simultaneously synthesizes mixed-type timeseries EHR data.
* [ECG-GAN](https://arxiv.org/pdf/1909.09150.pdf) - Synthesis of Realistic ECG using Generative Adversarial Networks.
* [TimeVAE](https://arxiv.org/pdf/2111.08095.pdf) - A novel architecture for synthetically generating time-series data with the use of VAEs.
* [StyleTime](https://arxiv.org/pdf/2209.11306.pdf) - StyleTime: Style Transfer for Synthetic Time Series Generation. 
* [GES](https://ieeexplore.ieee.org/document/9421374) - A method derived from principles of genetic algorithm, to generate artificial healthcare time data series data.
* [TimeTransformer](https://arxiv.org/pdf/2205.11164.pdf) - Time-series Transformer GANs to generate synthetic time-series.
* [TTS-GAN](https://arxiv.org/pdf/2202.02691.pdf) - A transformer-based GAN to generate realistic synthetic time-series data sequences.
* [TTS-CGAN](https://arxiv.org/pdf/2206.13676.pdf) - A Transformer Time-Series Conditional GAN for Biosignal Data Augmentation.
* [PSA-GAN](https://arxiv.org/pdf/2108.00981.pdf) - A GAN to generate long time series samples of high quality using progressive growing of GANs and self-attention.
* [SigWGAN](https://dl.acm.org/doi/pdf/10.1145/3490354.3494393) - Sig-Wasserstein GANs for Time Series Generation.
* [ABC-GAN](10.1109/TII.2022.3204282) - An Attention Based Cycle-Consistent GAN for IoT Data Generation (temporal features).

## Libraries

[Back to Top](#contents)

- [RGAN](https://github.com/ratschlab/RGAN) - Real-valued (Medical) Time Series Generation with Recurrent Conditional GANs.
- [WaveGAN](https://github.com/mostafaelaraby/wavegan-pytorch) - WaveGAN, a ML algorithm that learns to synthesize raw waveform audio by examples of real audio. 
- [TimeGAN](https://github.com/jsyoon0823/TimeGAN) - A framework for generating realistic time-series by combining unsupervised and supervised training. 
- [DeepEcho](https://github.com/sdv-dev/DeepEcho) -  A synthetic data generation Python library for mixed-type, multivariate time series.
- [DataAug](https://github.com/hfawaz/aaltd18) - Data augmentation using synthetic data for time series classification with deep residual networks.
- [SICCWGAN](https://github.com/SigCGANs/Conditional-Sig-Wasserstein-GANs) - Conditional Sig-Wasserstein GANs for time series.
- [COT-GAN](https://github.com/tianlinxu312/cot-gan) - COT-GAN: Generating Sequential Data via Causal Optimal Transport.
- [DoppelGANger](https://github.com/fjxmlzn/DoppelGANger) - Generating High-fidelity, Synthetic Time Series Datasets with DoppelGANger. 
- [HealthGen](https://github.com/simonbing/HealthGen) - A generative model to synthesize realistic EHR time series data with missingness.
- [EHRMGAN](https://github.com/jli0117/ehrMGAN) - A GAN entitled EHR-M-GAN which simultaneously synthesizes mixed-type timeseries EHR data.
- [ECG-GAN](https://github.com/Brophy-E/ECG_GAN_MBD) - Synthesis of Realistic ECG using Generative Adversarial Networks.
- [TimeVAE](https://github.com/abudesai/syntheticdatagen) - A novel architecture for synthetically generating time-series data with the use of VAEs.
- [TTS-GAN](https://github.com/imics-lab/tts-gan) - A transformer-based GAN to generate realistic synthetic time-series data sequences.
- [TTS-CGAN](https://github.com/imics-lab/tts-cgan) - A Transformer Time-Series Conditional GAN for Biosignal Data Augmentation.
- [PSA-GAN](https://github.com/mbohlkeschneider/psa-gan) - A GAN to generate long time series samples using progressive growing of GANs and self-attention. 
- [SigWGAN](https://github.com/SigCGANs/Sig-Wasserstein-GANs) - Sig-Wasserstein GANs for Time Series Generation.

## Tutorials
[Back to Top](#contents)

### Reading Content

[//]: # (* [Convert sparse tabular data to a condensed representation in an image format]&#40;https://towardsdatascience.com/turning-non-image-data-into-images-for-classification-is-surprisingly-effective-70ce82cfee27&#41;)

### Videos and Online Courses
[Back to Top](#contents)

[//]: # (* [Neural Networks for NLP]&#40;http://phontron.com/class/nn4nlp2017/&#41; - Carnegie Mellon Language Technology Institute there)


## License
MIT