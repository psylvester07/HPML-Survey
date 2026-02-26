# Survey on Spiking Neural Networks (SNNs) and Neuromorphic Computing  
### Efficient Training, Acceleration, and Hardware–Algorithm Co-Design

---

## 📌 Overview

This repository contains materials and drafts for a comprehensive survey on **Spiking Neural Networks (SNNs)** and **neuromorphic computing**, with a focus on efficient training algorithms and hardware-aware acceleration techniques.

While conventional Artificial Neural Networks (ANNs) have achieved remarkable success, they rely heavily on dense floating-point computation and energy-intensive hardware. As AI systems increasingly move toward edge devices and always-on embedded systems, energy efficiency and low-latency processing have become critical challenges.

SNNs, inspired by biological neural systems, offer a promising alternative by leveraging sparse, event-driven computation and temporal dynamics. Neuromorphic hardware platforms such as TrueNorth and Loihi are designed to exploit these properties for ultra-low-power intelligence.

However, efficiently training SNNs and achieving competitive performance remains an open research problem. This survey systematically examines the state-of-the-art at the intersection of algorithms and hardware.

---

## 🎯 Motivation

Despite their theoretical advantages, SNNs face several practical challenges:

- Non-differentiable spike functions complicate gradient-based learning  
- Temporal dynamics introduce instability and credit assignment difficulties  
- Conventional GPUs/TPUs are not optimized for sparse, event-driven workloads  
- Performance gaps remain between SNNs and ANN baselines in many benchmarks  

Recent advances — including surrogate gradient methods, ANN-to-SNN conversion strategies, and neuromorphic hardware innovations — are rapidly evolving the field. However, the literature is fragmented across algorithms, architectures, and applications.

This survey aims to consolidate and structure these developments.

---

## 🔍 Scope of the Survey

The final survey paper will:

- Review **4 foundational papers** that established key neuron models, learning rules, and early neuromorphic systems  
- Analyze **6 recent journal publications** representing major advances  
- Examine **10 recent and relevant conference papers** defining state-of-the-art techniques  
- Lightly reference additional relevant works for completeness  

<!-- ### Core Focus Areas

1. **Efficient Training Algorithms**
   - Surrogate gradient methods  
   - Local learning rules  
   - Temporal credit assignment strategies  

2. **ANN-to-SNN Conversion Techniques**
   - Accuracy preservation  
   - Latency–energy trade-offs  
   - Scalability considerations  

3. **Hardware–Algorithm Co-Design**
   - Mapping SNNs to neuromorphic hardware  
   - Exploiting sparsity and event-driven computation  
   - Energy–accuracy–latency trade-offs  

---
-->

## 🧠 Key Research Questions

- How can SNNs be trained efficiently while maintaining competitive accuracy?
- What are the trade-offs between direct training and ANN-to-SNN conversion?
- How should algorithms be designed to align with neuromorphic hardware constraints?
- What bottlenecks prevent large-scale deployment of neuromorphic AI?

---

## 📚 Repository Goals

This repository serves as a working space to:

- Catalog and organize relevant literature  
- Classify papers by methodology and contribution  
- Track open problems and research gaps  
- Draft and refine survey sections  
- Compare performance, scalability, and energy metrics  

---

## 📂 Planned Structure

---

## 👥 Intended Audience

- Graduate students entering neuromorphic AI research  
- Researchers in energy-efficient machine learning  
- Hardware architects designing AI accelerators  
- ML practitioners exploring biologically inspired models  

---

## 🚧 Status

- Literature search in progress  
- Foundational papers being identified  
- Drafting introduction and taxonomy sections  

---

<!-- ## 📖 Long-Term Goal

Beyond summarizing existing work, this survey aims to:

- Clarify current limitations in SNN training  
- Identify unresolved challenges in hardware–algorithm integration  
- Highlight promising research directions  
- Provide a structured roadmap for scalable, energy-efficient neuromorphic intelligence  

---
-->

*This repository documents the development of an ACM-style survey paper on Spiking Neural Networks and neuromorphic computing.*
