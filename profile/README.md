<img align="right" src="https://avatars.githubusercontent.com/u/119048450?s=200&v=4">

# PtyLab


PtyLab is a toolbox to reconstruct [Ptychography datasets](https://en.wikipedia.org/wiki/Ptychography) available in Python, Julia and Matlab. Head over to the respective repositories to try it out.
- [Python implementation](https://github.com/PtyLab/PtyLab.py)
- [Julia implementation](https://github.com/PtyLab/PtyLab.jl) 
- [Matlab implementation](https://github.com/PtyLab/PtyLab.m). 

## Citing
See this [Optics express article](https://opg.optica.org/oe/fulltext.cfm?uri=oe-31-9-13763&id=529026).
```
@article{Loetgering:23,
author = {Lars Loetgering and Mengqi Du and Dirk Boonzajer Flaes and Tomas Aidukas and Felix Wechsler and Daniel S. Penagos Molina and Max Rose and Antonios Pelekanidis and Wilhelm Eschen and J\"{u}rgen Hess and Thomas Wilhein and Rainer Heintzmann and Jan Rothhardt and Stefan Witte},
journal = {Opt. Express},
keywords = {Aperture synthesis; Imaging techniques; Optical coherence tomography; Phase imaging; Phase retrieval; Scanning electron microscopy},
number = {9},
pages = {13763--13797},
publisher = {Optica Publishing Group},
title = {PtyLab.m/py/jl: a cross-platform, open-source inverse modeling toolbox for conventional and Fourier ptychography},
volume = {31},
month = {Apr},
year = {2023},
url = {https://opg.optica.org/oe/abstract.cfm?URI=oe-31-9-13763},
doi = {10.1364/OE.485370},
abstract = {Conventional (CP) and Fourier (FP) ptychography have emerged as versatile quantitative phase imaging techniques. While the main application cases for each technique are different, namely lens-less short wavelength imaging for CP and lens-based visible light imaging for FP, both methods share a common algorithmic ground. CP and FP have in part independently evolved to include experimentally robust forward models and inversion techniques. This separation has resulted in a plethora of algorithmic extensions, some of which have not crossed the boundary from one modality to the other. Here, we present an open source, cross-platform software, called PtyLab, enabling both CP and FP data analysis in a unified framework. With this framework, we aim to facilitate and accelerate cross-pollination between the two techniques. Moreover, the availability in Matlab, Python, and Julia will set a low barrier to enter each field.},
}
```
