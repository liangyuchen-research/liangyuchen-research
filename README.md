# Liang-Yu (Lio) Chen

M.S. student in Chemical Engineering at **National Taiwan University** (Plasma Engineering Laboratory, advisor Prof. Cheng-Che Hsu). I build machine-learning and automation systems around plasma spectroscopy: models that read metal concentrations from emission spectra, generative restoration of interfered spectra, and the autonomous laboratory that acquires the data.

📧 r13524148@ntu.edu.tw · 📄 [Talanta 297 (2026) 128652](https://doi.org/10.1016/j.talanta.2025.128652)

<p align="center">
  <a href="https://github.com/liangyuchen-research/plasma-spectroscopy-quantification"><img src="https://raw.githubusercontent.com/liangyuchen-research/plasma-spectroscopy-quantification/main/docs/figures/occlusion_importance.png" width="49%" alt="Occlusion importance over a plasma emission spectrum"></a>
  <a href="https://github.com/liangyuchen-research/laboratory-instrument-control"><img src="https://raw.githubusercontent.com/liangyuchen-research/laboratory-instrument-control/main/docs/figures/console.png" width="49%" alt="Touch console of the autonomous laboratory"></a>
</p>

<p align="center"><sub>Left: the convolutional Transformer's prediction depends almost only on the Cu I 324.75 / 327.40 nm lines (occlusion analysis, Talanta 2026). Right: the touch console of Autonomous Laboratory v6 on its device simulator.</sub></p>

## Research

| Project | Summary |
| --- | --- |
| [Plasma spectroscopy for heavy metal quantification](https://github.com/liangyuchen-research/plasma-spectroscopy-quantification) | ANN / CNN / convolutional-Transformer regression of Cu, Ni, Pb and Zn from plasma emission spectra, spectral occlusion analysis, wastewater evaluation. Code, data and checkpoints of the *Talanta* paper. **NTU** |
| [GAN-based spectral restoration](https://github.com/liangyuchen-research/conditional-gan-spectral-restoration) | Conditional GAN that removes matrix interference from spectra before calibration; restored 1–5 ppm readouts within 5–9 % mean error in the archived evaluation. **NTU** |
| [Autonomous laboratory](https://github.com/liangyuchen-research/laboratory-instrument-control) | FastAPI service, touch console and Arduino firmware for eight peristaltic pumps, a syringe pump, interlocked valves and 10 Hz gravimetric feedback dosing; earlier Raspberry Pi / STM32 acquisition system preserved. **NTU** |
| [Matrix-matched spectral calibration](https://github.com/liangyuchen-research/mixture-of-experts-spectral-calibration) | Measurement processing and calibration tools for Na/Ca/K/Mg interference studies; archived results show matrix-matched calibration cutting test error 2–5×. **NTU, ongoing** |
| [SWOT satellite wave separation](https://github.com/liangyuchen-research/ocean-satellite-wave-separation) | Denoising autoencoders that separate Rossby-wave signal from internal-wave contamination in SWOT swath altimetry. **Scripps Institution of Oceanography, UC San Diego** |

## Course projects (University of Melbourne)

| Project | Summary |
| --- | --- |
| [Social media sentiment × daily weather](https://github.com/liangyuchen-research/social-sentiment-weather-analytics) | Kubernetes / Fission / Elasticsearch pipeline: rate-limit-aware harvesters for Reddit, Bluesky and Mastodon across three Australian cities, sentiment scoring of 1.22M posts joined with 12.5K daily weather records, served through REST functions. |
| [Evidence retrieval and claim verification](https://github.com/liangyuchen-research/evidence-retrieval-claim-verification) | TF-IDF candidate retrieval over 1.2M passages (top-500 hit rate 89 %), MiniLM cross-encoder reranking and a class-weighted DeBERTa-v3 classifier in PyTorch / Hugging Face. |

## Publication

- L.-Y. Chen, C.-Y. Wang, C.-C. Hsu, *Machine learning-based system for online quantitative monitoring of heavy metals across different aqueous matrices using spectroscopy of plasmas in liquids*, **Talanta** 297 (2026) 128652. [doi:10.1016/j.talanta.2025.128652](https://doi.org/10.1016/j.talanta.2025.128652)
- A second first-author manuscript on GAN-based spectral restoration is under review at *Analytica Chimica Acta*.

**Tools I use:** Python, C/C++, MATLAB · PyTorch, TensorFlow, scikit-learn, OpenCV · Arduino, Raspberry Pi, STM32, Modbus · Linux, Git, Docker, Kubernetes, LaTeX.
