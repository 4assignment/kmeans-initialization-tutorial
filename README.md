# K-Means Clustering: The Impact of Initialization

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

**MSc Machine Learning Tutorial**  
**Author:** Anandasai Sunke  
**Student ID:** 24057259  
**University of Hertfordshire**  
**Submission Date:** December 11, 2025

---

## 📚 Overview

This tutorial explores a critical yet often overlooked aspect of K-Means clustering: **centroid initialization**. Through hands-on Python code and clear visualizations, you'll learn why initialization matters and how to achieve more reliable clustering results.

### What You'll Learn
- How K-Means clustering works mathematically
- The impact of random vs. k-means++ initialization
- Quantitative metrics for cluster quality (inertia, silhouette score)
- Best practices for reliable clustering in real-world applications

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/4assignment/kmeans-initialization-tutorial.git
cd kmeans-initialization-tutorial

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook kmeans_initialization_tutorial.ipynb
```

### Running the Tutorial

1. Open `kmeans_initialization_tutorial.ipynb` in Jupyter Notebook
2. Run all cells sequentially (Cell → Run All)
3. All plots and results will be generated automatically

## 📁 Repository Structure

```
kmeans-initialization-tutorial/
│
├── kmeans_initialization_tutorial.ipynb  # Main Jupyter notebook
├── tutorial.md                            # Written tutorial document
├── requirements.txt                       # Python dependencies
├── README.md                              # This file
├── LICENSE                                # MIT License
└── .gitignore                            # Python gitignore
```

## 🎯 Key Findings

Our comprehensive analysis demonstrates that:
- **K-Means++ initialization** consistently produces better clusters (10-30% lower inertia)
- **Random initialization** can lead to suboptimal results with high variability
- **Multiple runs** (`n_init` parameter) significantly improve reliability
- **Silhouette scores** provide additional validation of cluster quality

## 🎨 Accessibility Features

This tutorial prioritizes accessibility:
- ✅ Colorblind-friendly palettes (viridis, tab10)
- ✅ Large, readable fonts and labels (14pt minimum)
- ✅ Alt-text descriptions for all figures
- ✅ Well-commented, clear code structure
- ✅ Screen reader compatible documentation

## 📚 References

- Arthur, D., & Vassilvitskii, S. (2007). "k-means++: The advantages of careful seeding." *SODA '07: Proceedings of the eighteenth annual ACM-SIAM symposium on Discrete algorithms*.
- Celebi, M.E., et al. (2013). "A comparative study of efficient initialization methods for the K-means clustering algorithm." *Expert Systems with Applications*, 40(1), 200-210.
- [Scikit-learn K-Means Documentation](https://scikit-learn.org/stable/modules/clustering.html#k-means)
- [Matplotlib Colorblind-Friendly Palettes](https://matplotlib.org/stable/tutorials/colors/colormaps.html)

## 👤 Author

**Anandasai Sunke**  
Student ID: 24052759  
MSc Data Science  
University of Hertfordshire

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💬 Contact

For questions or feedback:
- GitHub Issues: [Open an issue](https://github.com/4assignment/kmeans-initialization-tutorial/issues)
- Email: as24anp@herts.ac.uk

---

**Assignment Details:**
- Module: Machine Learning / Neural Networks
- Tutor: Peter Scicluna
- Weighting: 40%
- Submission Deadline: December 11, 2025
