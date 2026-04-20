# 🧠 Mesidor Dataset for Retinal Analysis

This repository provides a structured version of the **MESSIDOR dataset** for research and development in **diabetic retinopathy detection**, **lesion segmentation**, and **computer-aided diagnosis systems**.

---

## 📖 About the Dataset

The **MESSIDOR dataset** is a widely used medical imaging dataset for studying **diabetic retinopathy (DR)**. It contains high-resolution **color fundus images** along with diagnostic labels.

To enhance research in **segmentation and explainability**, this project can be used alongside **MAPLES-DR**, an extension of MESSIDOR that provides **pixel-wise annotations of retinal structures**.

---

## 🔬 MAPLES-DR Extension

**MAPLES-DR (MESSIDOR Anatomical and Pathological Labels for Explainable Screening of Diabetic Retinopathy)** is a public dataset that builds on MESSIDOR by adding:

* 🧠 Expert annotations from **retinologists**
* 🧩 Pixel-level segmentation maps
* 🔍 Labels for **10 retinal structures**, including:

  * Optic disc & cup
  * Macula
  * Blood vessels
  * Microaneurysms
  * Hemorrhages
  * Exudates
  * Cotton wool spots
  * Drusen
  * Neovascularization

It contains annotations for **198 MESSIDOR images** and is designed to improve **model explainability and reliability in DR screening**.

⚠️ **Note:**

* MAPLES-DR **does not include the original fundus images**
* You must download MESSIDOR separately and align them with the labels

---

## 🎯 Purpose of This Repository

This repository is designed to:

* 📂 Provide an **organized dataset structure**
* 🤖 Support **AI / Deep Learning workflows**
* 🧪 Enable **retinal disease research**
* 🔗 Serve as a bridge between **MESSIDOR images and MAPLES-DR annotations**

---

## 📚 References

### 📌 MESSIDOR

Decencière et al., *Feedback on a publicly distributed database: the MESSIDOR database*, Image Analysis & Stereology, 2014.

---

### 📌 MAPLES-DR

Lepetit-Aimon et al., *MAPLES-DR: MESSIDOR Anatomical and Pathological Labels for Explainable Screening of Diabetic Retinopathy*, Scientific Data, 2024.

---

### 📄 BibTeX

```bibtex
@article{maples_dr,
  title={MAPLES-DR: MESSIDOR Anatomical and Pathological Labels for Explainable Screening of Diabetic Retinopathy},
  author={Lepetit-Aimon, Gabriel and Playout, Clément and Boucher, Marie Carole and Duval, Renaud and Brent, Michael H and Cheriet, Farida},
  journal={Scientific Data},
  volume={11},
  number={1},
  pages={914},
  year={2024},
  doi={10.1038/s41597-024-03739-6}
}
```

