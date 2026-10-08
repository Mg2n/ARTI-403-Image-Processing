# ARTI 404 – Image Processing · Lab 5
## Spatial Filtering – Smoothing and Sharpening

| File / folder | Content |
|---|---|
| `Lab5.ipynb` | Jupyter notebook with all tasks, executed with outputs |
| `Lab5_Report.pdf` | Lab report |
| `images/` | Images used: `Parrot.png`, `astronaut.png`, `camera.png` |
| `outputs/` | Figures produced by the notebook |

### Tasks
**Procedural task**
1. Unsharp masking of the Parrot image (Gaussian σ = 2, amount = 1.5)

**Assessment tasks**
1. Convolution with a 7×7 box filter – original and smoothed image side by side (Parrot)
2. 5×5 and 21×21 Gaussian filters – three images side by side (astronaut)
3. Sharpening with a 3×3 Laplacian filter: original, Laplacian and sharpened image (cameraman)

### How to run
```bash
pip install opencv-python scikit-image matplotlib numpy pillow
jupyter notebook Lab5.ipynb
```
Run the notebook from inside the `Lab5` folder so the relative paths `images/` and `outputs/` resolve.
