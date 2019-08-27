# Supplemental material for _Observation of a charge-neutral muon polaron complex in antiferromagnetic Cr<sub>2</sub>O<sub>3</sub>_

M. H. Dehn<sup>1,2,3</sup> J. K. Shenton<sup>4,*</sup> S. Holenstein<sup>5,6</sup> Q. N. Meier<sup>4</sup> D. J. Arseneau<sup>^3</sup> D. L. Cortie<sup>1,2,7,†</sup> B. Hitti<sup>^3</sup> A. C. Y. Fang<sup>1,‡}</sup> W. A. MacFarlane<sup>2,3,7</sup> R. M. L. McFadden<sup>2,7</sup> G.
D. Morris<sup>3</sup> Z. Salman<sup>6</sup> H. Luetkens<sup>6</sup> N. A. Spaldin<sup>4</sup> M. Fechner<sup>4,8</sup> and R. F. Kiefl<sup>1,2,3</sup>


<sup>1</sup>Department of Physics and Astronomy, University of British Columbia, Vancouver, BC V6T 1Z1, Canada    
<sup>2</sup>Stewart Blusson Quantum Matter Institute, University of British Columbia, Vancouver, BC V6T 1Z4, Canada    
<sup>3</sup><span style="font-variant:small-caps;">Triumf</span>, Vancouver, BC V6T 2A3, Canada   
<sup>4</sup>Department of Materials, ETH Zürich, CH-8093 Zürich, Switzerland   
<sup>5</sup>Physik-Institut der Universität Zürich, CH-8057, Zürich, Switzerland   
<sup>6</sup>Laboratory for Muon Spin Spectroscopy, Paul Scherrer Institut, 5232, Villigen PSI, Switzerland   
<sup>7</sup>Department of Chemistry, University of British Columbia, Vancouver, BC, V6T 1Z1, Canada    
<sup>8</sup>Max Planck Institute for the Structure and Dynamics of Matter, 22761 Hamburg, Germany   
<sup>†</sup> Present address: Institute for Superconducting and Electronic
Materials, Australian Institute for Innovative Materials, University of Wollongong, North Wollongong, NSW 2500, Australia    
<sup>‡</sup> Present address: Department of Physics, Simon Fraser University, Burnaby, Canada V5A 1S6  

<sup>*</sup> For queries about the supplemental material in this repository contact [J. Kane Shenton](mailto:john.shenton@mat.ethz.ch).

---
In these notebooks we provide supplemental material for our work on understanding the behaviour of muons in the magnetoelectric antiferromagnet, Cr<sub>2</sub>O<sub>3</sub>.

We provide `vasprun.xml` files that correspond to self-consistent <span style="font-variant:small-caps;">vasp</span> calculations for each of the candidate muon stopping sties and states identified in the paper (also labelled as in the paper). The `vasprun.xml` files contain information about both the input parameters and the output results from these calculations. We summarise the muon stopping sites and give examples of how to parse the `vasprun.xml` files in the jupyter notebook: `Muon_stopping_site_summary.ipynb`

 We further provide `vasprun.xml` files for some of the tests of convergence with respect to plane wave energy cut-off and k-point sampling density. These tests are summarised in the jupyter notebook: `Cr2O3_convergence_tests.ipynb`.

 Finally, we provide results files for our comparison of local field estimates (dipolar and Fermi-contact) using different exchange-correlation functionals. These results are parsed and analysed in the jupyter notebook: `xc_functional_mag_field_predictions.ipynb`.


These jupyter notebooks may be previewed on github or via the [jupyter notebook viewer](https://nbviewer.jupyter.org) website. 

Note that all of the vasprun.xml files are currently compressed to save space. These must be uncompressed before the notebooks can be run.

