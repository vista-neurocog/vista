# VISTA: Visual Inference for Spatio-Temporal Attention

**An open-source community initiative for generating naturalistic, annotated video datasets to advance gaze tracking, cognitive assessment, and behavioral neuroscience.**

***

## 🧠 Overview

VISTA (Visual Inference for Spatio-Temporal Attention) is a framework and dataset initiative aimed at fostering more ecologically valid research in attention and cognition. We provide:

* **AI-generated naturalistic videos** simulating everyday scenes
* **Human-curated scripts and interactions**, ensuring realism and task relevance
* **Rich metadata annotations** conforming to [HED](https://www.hedtags.org/) and [FHIR](https://www.hl7.org/fhir/) standards
* **Tools for researchers** to create, customize, and annotate stimuli for cognitive and gaze-tracking experiments

This project supports explainable AI models and personalized neurocognitive assessment pipelines.

***

## 🔍 Key Features

* 🎥 **Naturalistic Video Stimuli**  Real-world inspired visual scenarios designed to maximize ecological validity.
* 🧠 **Spatio-Temporal Attention Labels**  Includes Areas of Interest (AOIs), moving targets, and time-locked cognitive events.
* 📚 **Scripted & Versioned Content**  All scenes are generated from structured, version-controlled YAML scripts.
* ⚙️ **HED + FHIR Metadata**  Enables semantic and clinical interoperability for both research and clinical deployment.
* 🛠️ **Custom Stimuli Toolkit** *(coming soon)*  Interface and CLI to scaffold new scenes, annotate, and export in formats like JSON, SVG, or Lottie.

***

## 🧪 Applications

* Development and benchmarking of gaze tracking algorithms
* Cognitive load and attention modeling in real-world contexts
* Remote and scalable digital neuropsychological assessments
* Screening for neurodevelopmental conditions (e.g. autism)
* Monitoring cognitive resilience and aging trajectories

***

## 🚀 Getting Started

```shellscript
# 1. Clone the repository
git clone https://github.com/neurocog-ai/vista.git
cd vista

# 2. Install dependencies
pip install -r requirements.txt

# 3. Preview sample video annotations
python tools/preview_dataset.py

# 4. Generate a custom video scene (experimental)
python tools/generate_scene.py --script scripts/example_scene.yaml
```

***

## 📜 Citation

An OSF DOI will be available soon. Until then, cite as:

VISTA: Visual Inference for Spatio-Temporal Attention (2025).

An open-source dataset for naturalistic gaze tracking and cognitive testing.

https://github.com/vista-neurocog