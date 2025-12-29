🌧️ Sea Level-Rainfall-Weathering Model
Welcome to the MATLAB implementation of our GEOCLIM-based silicate weathering model. This repository contains the code used for the research presented in our paper.

📖 Research Context
This code accompanies the following manuscript:

"Rainfall amplified sea-level control on silicate weathering in the Indo-Pacific Convergence Zone during Quaternary glacials"
Target Journal: Communications Earth & Environment
Current Status: Under review (as of this README)

Important: Please do not cite or distribute this code until the associated manuscript is formally published. We will update this repository upon publication and welcome its use and citation at that time.

🧩 Model Heritage
Core Foundation
The model parameters and physical formulations are derived from the GEOCLIM-Dynsoil-Steady-State model (Fortran version) developed by:

Goddéris, Y. & Donnadieu, Y. (2019)
Geological Magazine, 156(2), 355–365
DOI: 10.1017/S0016756818000130

Our Contributions
We have extended the original model by:

Improved Accessibility: Translated from Fortran to MATLAB for broader usability

Automation: Reduced manual configuration through automated workflows

Enhanced Functionality: Implemented point-to-point calculation of physical erosion and chemical weathering fluxes

Documentation: Added comprehensive comments to improve code transparency

⚠️ Important Note on Test Data
The file ERA5_1981-2018_30minx30min.nc is provided for testing purposes only.

Please note:

This data is used solely to verify that the code runs correctly

Results obtained with this dataset have no scientific significance

It serves as a placeholder to demonstrate the model structure

The actual data used in our research is described in detail in the manuscript's methods section and is fully reproducible

📚 Citation
If you use this model in your research, please cite:

Our paper (once published):
[To be updated upon publication]

The foundational model (required):
Goddéris, Y. & Donnadieu, Y. (2019). A sink- or a source-driven carbon cycle at the geological timescale? Relative importance of palaeogeography versus solid Earth degassing rate in the Phanerozoic climatic evolution. Geological Magazine, 156(2), 355-365.

🔗 Related Resources
Original GEOCLIM model: https://github.com/piermafrost/GEOCLIM-dynsoil-steady-state
We recommend consulting the original implementation to understand the core concepts.

🤝 Contact
Scientific Questions
Please contact the corresponding authors:

Dr. Zhaokai Xu: zhaokaixu@qdio.ac.cn

Dr. Debo Zhao: zhaodebo@qdio.ac.cn

Code-related Inquiries
For discussions about the code, bug reports, or implementation questions:

Yifei Yang: yangyifei@qdio.ac.cn

Final Note:
Models are tools to understand complex systems. Always validate results against observations and theory.
