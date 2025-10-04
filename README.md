
<!--
Profile README — RF & DSP cyberpunk edition.
-->

<div align="center">

<!-- Cyberpunk oscilloscope banner with subtle animated glow -->
<svg width="100%" height="140" viewBox="0 0 1200 140" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Waveform banner">
  <defs>
    <linearGradient id="g" x1="0" x2="1" y1="0" y2="0">
      <stop offset="0%" stop-color="#00FFFF"/>
      <stop offset="100%" stop-color="#C77DFF"/>
    </linearGradient>

    <!-- Soft glow filter -->
    <filter id="glow" x="-20%" y="-200%" width="140%" height="500%">
      <feGaussianBlur stdDeviation="2.2" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <style>
    /* Subtle pulse on the main trace */
    @keyframes pulse {
      0%, 100% { stroke-opacity: 0.95 }
      50%      { stroke-opacity: 0.55 }
    }
    .gridL { stroke:#4B4B4B; stroke-dasharray:4 6; opacity:0.25 }
    .gridS { stroke:#333;    stroke-dasharray:2 10; opacity:0.25 }

    /* Halo behind the trace */
    .halo {
      stroke:url(#g);
      stroke-width:8;
      opacity:0.18;
      filter:url(#glow);
      stroke-linecap:round;
    }
    /* Main neon trace */
    .trace {
      stroke:url(#g);
      stroke-width:3;
      fill:none;
      filter:url(#glow);
      stroke-linecap:round;
      animation:pulse 2.8s ease-in-out infinite;
    }
  </style>

  <rect width="1200" height="140" fill="transparent"/>

  <!-- Grid -->
  <path class="gridL" d="M0 70 H1200"/>
  <path class="gridS" d="M0 35 H1200 M0 105 H1200"/>

  <!-- Waveform path (duplicated: halo + trace) -->
  <path class="halo" d="
    M0,70
    C60,30 120,110 180,70
    S300,30 360,70
    S540,110 600,70
    S780,30 840,70
    S1020,110 1080,70
    S1140,50 1200,70" />

  <path class="trace" d="
    M0,70
    C60,30 120,110 180,70
    S300,30 360,70
    S540,110 600,70
    S780,30 840,70
    S1020,110 1080,70
    S1140,50 1200,70" />
</svg>

<h1 style="color:#00FFFF;">Enrique / perazaharmonics</h1>
<h3 style="color:#C77DFF;">RF • Digital Signal Processing • SDR • Real-time Systems • Kubernetes</h3>

<p>
  <em>Building low-level systems that process and shape reality in real time.</em>
</p>

<!-- neon badges -->
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
- **DSP/RF engineer** building elegant **C++17 header-only** libraries and real-time DSP tools.
- Works on **telemetry ground systems** (AOS, commutators, packet processors) and **SDR** pipelines.
- Packages everything inside **containers**, orchestrated via **Kubernetes**, hardened for production.
- Enjoys proofs where they matter, profilers where they count, and **pretty waveforms always**.

---

### Current Work
- **FCWTransforms** — FFTs (Split-Radix, PFA, Bluestein, Rader), MUSIC, PCA, windowing zoo. Cosine Transforms, etc.
- **Smart Wavelet Daughters (WOLA)** — live wavelet synthesis for timbre morphing.
- **Waveguide Modeling** — physical strings, bodies, FDN reverbs, 2D/3D meshes; fractional delays (Thiran→Farrow).
- **Aerospace SDR Stack** —
- High-Reliability Aerospace SSR.
- **K8s Infrastructure** — Cilium networking, Helm-managed services, persistent metrics endpoints.

---

### Visual Gallery — RF / DSP

<p align="center">
  <img src="assets/spectrogram_lofi.gif" width="30%" alt="Live spectrogram">
  <img src="assets/waveguide_mesh.gif" width="30%" alt="Waveguide mesh sim">
  <img src="assets/wola_grains.gif" width="30%" alt="Wavelet OLA grains">
</p>

<p align="center">
  <img src="assets/constellation_qpsk.png" width="30%" alt="QPSK constellation">
  <img src="assets/fft_peaks.png" width="30%" alt="FFT peaks with windowing">
  <img src="assets/hilbert_phase.gif" width="30%" alt="Hilbert/phase unwrap">
</p>

<p align="center">
  <img src="https://wiki.gnuradio.org/images/0/0a/Waterfall-ex.png" width="32%" alt="GNU Radio Waterfall spectrogram" title="FM-band waterfall">
  <img src="https://upload.wikimedia.org/wikipedia/commons/8/8f/QPSK_Gray_Coded.svg" width="32%" alt="QPSK constellation (Gray-coded)">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a8/Continuous_wavelet_transform.svg/640px-Continuous_wavelet_transform.svg.png" width="32%" alt="Continuous Wavelet Transform scalogram">
</p>

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/9/98/Butterfly-FFT.png" width="32%" alt="Radix-2 FFT butterfly diagram">
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/23/Radix-2_FFT_butterfly_diagram.png" width="32%" alt="FFT butterfly flow">
  <img src="https://upload.wikimedia.org/wikipedia/commons/4/44/Analysis_of_three_superposed_sinusoidal_signals.jpg" width="32%" alt="STFT vs Wavelet comparison">
</p>

<details>
  <summary>Capture details</summary>
  <ul>
    <li>Oscilloscope traces via Tektronix TBS series → PNG</li>
    <li>Matplotlib animations → GIF (ffmpeg / ImageMagick)</li>
    <li>Live app recordings → OBS Studio crop → GIF</li>
  </ul>
</details>

<sub>
Sources: GNU Radio Wiki, Wikimedia Commons (FFT, Wavelet, QPSK, STFT figures).  
Download locally into <code>/assets</code> for stability if desired.
</sub>

---

### Selected Projects
- **[FCWTransforms](https://github.com/perazaharmonics/FCWTransforms)** — transforms toolkit: FFTs, DCTs, wavelets.
- **[Time Frequency Analysis](https://github.com/perazaharmonics/Time-and-Frequency-py)** — Multi Resolution Analysis.
- **[Digital Image Processing](https://github.com/perazaharmonics/Image-Processing-Matrices)** —
- **Peraza & Ampere Synth** — Wavelet atom injector, 4D waveshaping projection synth.
- **Aerospace SDR** — modular telemetry stack.

---

### Toolchain
- **Languages**: C++, C, Go, Python, MATLAB, LabVIEW, JAVA, BASH
- **DSP**: FFTs, STFT/WOLA, Wavelets, MUSIC/ESPRIT, Kalman/LQG  
- **RF/SDR**: VITA-49, framing, constellations, SNR/EB/N₀, Ambiguity Surface Resolution, Phased Arrays
- **Infrastructure**: Kubernetes, Helm, Cilium, containerd, Prometheus  
- **Build/Test**: CMake, Make, Catch2, GitHub Actions 
- **OS**: RHEL 8/9, Fedora, Alma

---

<div align="center">
  <img width="480" alt="cyber image" src="https://github.com/user-attachments/assets/7a5338a7-df8a-4683-b17e-74ebfd28207e">
</div>

### Philosophy
> Build it. Break it. Learn from it.  
> Precision, noise, and punk

---

<div align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=perazaharmonics&show_icons=true&theme=radical" alt="GitHub stats">
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=perazaharmonics&layout=compact&theme=radical" alt="Top languages">
</div>

<p align="center"><sub style="color:#C77DFF;">Built for RF, DSP, and clean systems.</sub></p>

If you want the glow a touch stronger, bump the stdDeviation from 2.2 → 3.0, or increase the .halo opacity from 0.18 → 0.25.
