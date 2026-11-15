## Hi, I'm Ramanjit.

I build products, and I study the mathematics underneath them.

I'm a computer science engineer from Punjab, India. I co-founded **FemoraAI**, a women's health app used by more than 4,600 people, and now **[Luna](https://letluna.com)**, an AI executive assistant for founders. I work on software that has to make sense of messy, incomplete information, and on the numerical methods and GPU code that make it fast and trustworthy.

**Website:** [ramanjitsingh-hub.github.io](https://ramanjitsingh-hub.github.io)

### Research
Each investigation is a question, a derivation, code written from scratch, and measured results, including the ones that did not go my way.

| | | |
|---|---|---|
| **01** | [Re-deriving a production cycle predictor](https://ramanjitsingh-hub.github.io/01/) | The Kalman filter I shipped at FemoraAI, ported line by line. It becomes a moving average after five cycles, and a 3σ safety gate can lock it out permanently. An exact Bayesian replacement fixes both. *Synthetic data.* |
| **02** | [A Navier–Stokes solver on a 4 GB laptop GPU](https://ramanjitsingh-hub.github.io/02/) | CUDA from scratch. Matches an independent FFT solver to 5.6 × 10⁻¹⁶, exactly second order, validated on the lid-driven cavity, then 13.5× faster with the same answer. Hardware counters then found warp divergence in the smoother, fixed for a 2.1× kernel speed-up. It also runs in your browser on WebGPU. |
| **03** | [The anatomy of a graphics card](https://ramanjitsingh-hub.github.io/03/) | Microbenchmarks that each isolate one mechanism of the GPU and test it against a model written down first. Most models hold to a few percent. Follow-up experiments found a 16-entry, 2 MB address-translation cache and the 3 idle cycles behind FP64's missing 16%. |

Code for all three: [ramanjitsingh-hub.github.io](https://github.com/ramanjitsingh-hub/ramanjitsingh-hub.github.io)

### Building
- **Luna** (2026 –), co-founder. Agent architecture, AI infrastructure, backend.
- **FemoraAI** (2025 – 2026), co-founder. Backend, AI inference, data infrastructure. Per-user Kalman filtering, 7 microservices, a team of 21.
- **Pink Parcel** (2023 – 2025), co-founder. Period kits to six university hostels in seven minutes.

**Working with:** CUDA · C++ · Python · NumPy/SciPy · PyTorch · Java/Spring Boot · TypeScript · WebGPU · MongoDB · Kafka · GCP/AWS

### Contact
hackit830@gmail.com · [LinkedIn](https://www.linkedin.com/in/ramanjitsingh1) · [Twitter](https://twitter.com/itzramancoder) · [Instagram](https://instagram.com/ramanjit1534)
