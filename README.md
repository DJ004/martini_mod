>Note: 
>##### The original 'insane.py' script was created by:
>- Tsjerk A. Wassenaar, Helgi I. Ingólfsson, Rainer A. Böckmann, D. Peter Tieleman, and Siewert J. Marrink
>  - Paper: [Computational Lipidomics with insane: A Versatile Tool for Generating Custom Membranes for Molecular Simulations](https://pubs.acs.org/doi/10.1021/acs.jctc.5b00209)
>##### The original 'martini_v2.2_aminoacids.itp' topology was created by:
>- D.H. de Jong, G. Singh, W.F.D. Bennet, C. Arnarez, T.A. Wassenaar, L.V. Schafer, X. Periole, D.P. Tieleman, S.J. Marrink.
>  - Paper: [Improved Parameters for the Martini Coarse-Grained Protein Force Field](https://pubs.acs.org/doi/10.1021/ct300646g)
>  - Original topology: http://cgmartini.nl/images/parameters/ITP/martini_v2.2_aminoacids.itp
>##### The original 'martinize.py' script (version 2.6) was created by:
>- D.H. de Jong, Jaakko J. Uusitalo, Tsjerk A. Wassenaar.
>  - Original script: http://cgmartini.nl/index.php/tools2/proteins-and-bilayers/204-martinize
#### [ 1 ] Acylated amino acids (update to Martini 2.2 ff)
- martini_v2.2_aminoacids_lipidtails.itp
- martinize2.6_lipidtails.py

Each of the above files are updated with the following acylated amino acid parameters according to 
[Yoav Atsmon-Raz and D. Peter Tieleman, 2017 (J. Phys. Chem. B)](https://pubs.acs.org/doi/10.1021/acs.jpcb.7b10175)
  - CYF = CYS Farnesyl
  - CYG = CYS Geranylgeranyl
  - CYP = CYS Palmitoyl
  - GMN = N-terminal GLY Myristoyl

----

#### [ 2 ] N-acetyl glucosamine-Asparagine (update to Martini 2.2 ff)
- martini_v2.2_aminoacids_lipidtails_ASG.itp
- martinize2.6_lipidtails_ASG.py

Each of the above files are updated with the following glycosylated amino acid parameters according to [Shivgan et al., 2020 (JCIM)](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00495)
- ASG = N-acetyl glucosamine-Asn

