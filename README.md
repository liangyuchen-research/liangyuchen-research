# Liang-Yu (Lio) Chen

I am a master's student in Chemical Engineering at National Taiwan University. My research focuses on machine learning for real-time heavy metal quantification from plasma spectroscopy, with additional work in experimental automation and ocean-satellite signal processing.

## Research Experience

| Project | Research and available code |
| --- | --- |
| [Autonomous Laboratory for Automated Solution Preparation and Quantitative Analysis](https://github.com/liangyuchen-research/laboratory-instrument-control) | **Plasma Engineering Laboratory, NTU.** FastAPI backend, touch-oriented browser console, and Arduino Mega firmware for eight peristaltic pumps, a syringe pump, valve interlocks, and mass-feedback dosing. The v6 system includes a device simulator and wiring guides. Earlier Raspberry Pi/STM32 pulse-control and spectral-acquisition code is retained in `legacy/`. |
| [GAN-Based Restoration of Plasma Spectra for Real-Time Heavy Metal Quantification](https://github.com/liangyuchen-research/conditional-gan-spectral-restoration) | **Plasma Engineering Laboratory, NTU.** Conditional GAN spectral restoration and concentration calibration across solution matrices, including wastewater experiments. Related regression and occlusion-based explainable AI code is in the [plasma spectroscopy repository](https://github.com/liangyuchen-research/plasma-spectroscopy-quantification). |
| [Deep Learning for Source Separation in SWOT Satellite Altimetry](https://github.com/liangyuchen-research/ocean-satellite-wave-separation) | **Scripps Institution of Oceanography, UC San Diego.** Denoising autoencoder experiments to separate Rossby and internal-wave signals from sea surface height, with comparisons of input dimensions and representations. |

## Projects

| Project | Methods and scale |
| --- | --- |
| [Kubernetes Pipeline for Linking Social Media Sentiment with Daily Weather Data](https://github.com/liangyuchen-research/social-sentiment-weather-analytics) | **Unimelb, Cluster and Cloud Computing.** Architecture case study covering harvesters for 3 platforms and 3 Australian cities, 1.22M posts, and 12.5K weather records. Melbourne Research Cloud, Kubernetes, Fission REST APIs, and Elasticsearch. |
| [Two-Stage Evidence Retrieval and Transformer-Based Claim Verification](https://github.com/liangyuchen-research/evidence-retrieval-claim-verification) | **Unimelb, Natural Language Processing.** TF-IDF retrieval over 1.2M passages, cross-encoder reranking, and DeBERTa-v3 fine-tuning with class-weighted loss. Top-500 candidate retrieval found at least one correct passage for 89% of development claims. PyTorch, Hugging Face Transformers, and scikit-learn. |

## Additional Research and Tools

- [Plasma Spectroscopy for Heavy Metal Quantification](https://github.com/liangyuchen-research/plasma-spectroscopy-quantification): spectral regression, transfer learning, and occlusion-based analysis of characteristic emission regions. Published in [*Talanta*, 297 (2026), 128652](https://doi.org/10.1016/j.talanta.2025.128652).
- [Mixture-of-Experts Spectral Calibration](https://github.com/liangyuchen-research/mixture-of-experts-spectral-calibration): staged calibration experiments across solution matrices.
