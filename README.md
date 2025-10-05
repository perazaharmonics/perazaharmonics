<div align="center">
  <p align="center">
    <img src="assets/waveform.PNG" alt="Waveform banner" width="100%">
  </p>

  <h1 style="color:#00FFFF;">Enrique / perazaharmonics</h1>
  <h3 style="color:#C77DFF;">RF • Digital Signal Processing • SDR • Real-time Systems • Kubernetes</h3>

  <p><em>I just really like signals. Computers make waveforms go zoom. So I program those too.</em></p>

  <p>
    <img alt="C++" src="https://img.shields.io/badge/C++-17/20-303030?logo=c%2B%2B&logoColor=00FFFF&labelColor=202020">
    <img alt="Go" src="https://img.shields.io/badge/Go-Concurrency-303030?logo=go&logoColor=00FFFF&labelColor=202020">
    <img alt="DSP" src="https://img.shields.io/badge/DSP-FFT/Wavelets/Estimation-303030?labelColor=202020&color=C77DFF">
    <img alt="SDR" src="https://img.shields.io/badge/SDR-VITA49/DIFI-303030?labelColor=202020&color=7C3AED">
    <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-Cilium/Helm-303030?logo=kubernetes&logoColor=00FFFF&labelColor=202020">
    <img alt="RHEL" src="https://img.shields.io/badge/RHEL-8/9-303030?logo=redhat&logoColor=C77DFF&labelColor=202020">
  </p>
</div>

---

### About
- **DSP/RF engineer** building tools to process data with **nice shapes** on C++, mostly 
- Works on **telemetry ground systems** (AOS, commutators, packet processors) and **SDR** pipelines.
- Packages everything inside **containers**, orchestrated via **Kubernetes**, hardened for production.
- Hardcore punk, man. Drumming, mathematical proofs, and **gorgeous signals**.

---

### Current Work
- **FCWTransforms** — FFTs (Split-Radix, PFA, Bluestein, Rader, Stockham's, etc), MUSIC, PCA, Spectral Windows; Cosine Transforms.
- **Adaptive Wavelet Synthesizer (AWSynth)** — live wavelet synthesis for timbre morphing.
- **The Projectionist** - 4D Noise Field Projector unto a waveshapen LFO. Audio Scaping Engine.
- **Waveguide Modeling** — physical strings, bodies, FDN reverbs, 2D/3D meshes; fractional delays (Thiran→Farrow).
- **Aerospace SDR Stack** — VITA-49/DIFI transport, modular telemetry pipelines, HA/persistence.
- **K8s Infrastructure** — Cilium networking, Helm-managed services, persistent metrics endpoints.

---
### Visual Gallery — RF / DSP

<div align="center">

  <!-- Row 1: QPSK + FFT -->
  <p>
    <img src="assets/qpsk_dark.PNG?v=3" width="40%" style="margin:8px;" alt="QPSK Constellation (Dark)">
    <img src="assets/fft_peaks_dark.PNG?v=3" width="48%" style="margin:8px;" alt="Windowed FFT Spectrum (Dark)">
  </p>

  <!-- Row 2: CWT + Ambiguity -->
  <p>
    <img src="assets/cwt_scalogram_dark.PNG?v=3" width="48%" style="margin:8px;" alt="CWT Scalogram (Dark)">
    <img src="assets/ambiguity_surface_dark.PNG?v=3" width="40%" style="margin:8px;" alt="3D Ambiguity Surface (τ vs ν)">
  </p>

</div>

---

### Projectionist — 4D Noise Fields

<p align="center">
  <img src="assets/IMG_0158.png?v=4" width="30%" alt="Simplex 4D Noise Field">
  <img src="assets/IMG_0159.png?v=4" width="30%" alt="Value 4D Noise Field">
  <img src="assets/IMG_0160.png?v=4" width="30%" alt="Voronoi 4D Noise Field">
</p>

<p align="center">
  <img src="assets/IMG_0161.png?v=4" width="30%" alt="Wavelet 4D Noise Field">
  <img src="assets/IMG_0162.png?v=4" width="30%" alt="Fractal Brownian Motion 4D Noise Field">
  <img src="assets/IMG_0163.png?v=4" width="30%" alt="Tiling 4D Noise Field">
</p>

<p align="center">
  <img src="assets/IMG_0164.png?v=4" width="30%" alt="OpenSimplex Proxy 4D Noise Field">
  <img src="assets/IMG_0166.png?v=4" width="30%" alt="Cell 4D Noise Field">
</p>

<p align="center">
  <sub style="color:#C77DFF;">Generated via Python simulation of <code>Shape4D()</code> dispatcher for C++ Projectionist Synth.</sub>
</p>
---

### Selected Projects
- **[FCWTransforms](https://github.com/perazaharmonics/FCWTransforms)** — transforms toolkit: FFTs, DCTs, wavelets.
- **[Time Frequency Analysis](https://github.com/perazaharmonics/Time-and-Frequency-py)** — Multi Resolution Analysis.
- **[Digital Image Processing](https://github.com/perazaharmonics/Image-Processing-Matrices)** — 2D Spectral analysis kernels.
- **[Wavelet Projectionist Synth (WAVEPRO)]** — Wavelet atom injector of the waveform into itself.
- **[Speech Processing](https://github.com/perazaharmonics/SpeechProc/tree/main)** - Speech Information extraction through spectral methods.
- **[SATMAT](https://github.com/perazaharmonics/SATMAT)** — Radio Frequency Ground Station and Satellite Calculations.

---

### Toolchain
- **Languages**: C++, C, Go, Python, MATLAB, LabVIEW, JAVA, Bash  
- **DSP**: FFTs, STFT/WOLA, Wavelets, MUSIC/ESPRIT, Pattern Recognition  
- **RF/SDR**: VITA-49, framing, constellations, SNR/EB/N₀, Ambiguity Surface Resolution, Phased Arrays  
- **Infrastructure**: Kubernetes, Helm, Ansible, Cilium, containerd, Prometheus  
- **Build/Test**: CMake, Make, Catch2, GitHub Actions  
- **OS**: RHEL 8/9, FedoraLinux, AlmaLimux, Windows

---

<div align="center">
  <img width="480" alt="cyber image" src="https://github.com/user-attachments/assets/7a5338a7-df8a-4683-b17e-74ebfd28207e">
</div>

### Philosophy
> Build it. Break it. Learn from it.  
> Precision, noise; punk rock.

---

<div align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=perazaharmonics&show_icons=true&theme=radical" alt="GitHub stats">
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=perazaharmonics&layout=compact&theme=radical" alt="Top languages">
</div>

<p align="center"><sub style="color:#C77DFF;">Built for RF, DSP, and clean systems.</sub></p>
