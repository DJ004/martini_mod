# martini_mod
Modifications made to Martini2.2 FF according to published parameters

---------------
Modification #1
---------------

Updated with lipid tail parameters according to DOI:10.1021/acs.jpcb.7b10175 (Authors: Yoav Atsmon-Raz and D. Peter Tieleman)
; CYS Farnesyl             = CYF
; CYS Geranylgeranyl       = CYG
; CYS Palmitoyl            = CYP
; N-terminal GLY Myristoyl = GMN

The above modifications are saved in the following files:
(1) martini_v2.2_aminoacids_lipidtails.itp
(2) martinize2.6_lipidtails.py

The original topology (martini_v2.2_aminoacids.itp) was created by the authors of the following work:
Improved Parameters for the Martini Coarse-Grained Protein Force Field. J. Chem. Theory Comput., DOI: 10.1021/ct300646g
D.H. de Jong, G. Singh, W.F.D. Bennet, C. Arnarez, T.A. Wassenaar, L.V. Schafer, X. Periole, D.P. Tieleman, S.J. Marrink.
(http://cgmartini.nl/images/parameters/ITP/martini_v2.2_aminoacids.itp)

The original script (martinize.py) version 2.6 was created by the following authors:
Djurre H. de Jong, Jaakko J. Uusitalo, Tsjerk A. Wassenaar.
(http://cgmartini.nl/index.php/tools2/proteins-and-bilayers/204-martinize)

---------------
Modification #2
---------------
Updated with N-acetyl glucosamine-Asn according to DOI:10.1021/acs.jcim.0c00495
; N-acetyl glucosamine-Asn = ASG

The above modifications are saved in the following files:
(1) martini_v2.2_aminoacids_lipidtails_ASG.itp
(2) martinize2.6_lipidtails_ASG.py
