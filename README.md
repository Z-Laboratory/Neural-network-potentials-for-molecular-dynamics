# Neural network forcefield for molten salts

NaCl.pb and FLiNaK.pb are neural network forcefields based on DeePMD framework for molecular dynamic simulaiton.

Updates: FLiNaK-CsF.pb are the newly trained DeePMD(v2.1.4) model (smooth version), we trained this model using VASP (PBE+vdw-DF) with T = 800~1200 K, CsF mol% = 1 ~ 9. (Atom type: 1: F, 2: Li, 3: Na, 4: K, 5: Cs)

Please cite the paper below upon using these potentials:

Shao-Chun Lee, Yanqin Zhai, Zhixia Li, Nathan P. Walter, Melissa Rose, Brent J. Heuser, and Y Z, Comparative studies of the structural and transport properties of molten salt FLiNaK using machine-learned neural network and reparametrized classical forcefields, Thye Journal of Physical Chemistry B, 2021, DOI: 10.1021/acs.jpcb.1c05608

Please also cite the DeePMD toolkit, details can be found in:
https://github.com/deepmodeling/deepmd-kit
