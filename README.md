# IllustrisTNG
## Extracting disk galaxies from  the TNG-50 simulation of the Star Forming Main Sequence using SFR and Mass-Size Relation

### Simulation Name: TNG-50

### Fields available: 
- 1)total mass
- 2)stellar mass
- 3)gas mass
- 4)dark matter mass
- 5)SFR
- 6)V_max
- 7)velocity dispersion


### Redshift Bins:
- [0,0.05):z=0
- [0.05,0.45):z=0.1,0.2,0.3,0.4
- [0.45-1.05):z=0.5,0.7,1
- [1.05-1.45): No snapshot
- [1.45-2.05):z=1.5,2
- [2.05-2.45): No snapshot
- [2.45-3.05):z=3

### Selection criteria:
- Galaxies of cosmological origin only(SubhaloFlag==1)
- Removed galaxies with unrealistic values of stellar mass, SFR, stellar half mass radius<0 but there may be such unrealistic values for other fields.

### References:
#### Filtering by SFR:
- [Speagle et al 2014](https://arxiv.org/abs/1405.2041)
- [Santini et al 2017](https://iopscience.iop.org/article/10.3847/1538-4357/aa8874)
- [Pearson et al 2018](https://arxiv.org/abs/1804.03482)
- [Iyer et al 2018](https://iopscience.iop.org/article/10.3847/1538-4357/aae0fa)

#### Filtering by Mass-Size Relation:
- [Lapi et al 2018](https://iopscience.iop.org/article/10.3847/1538-4357/aabf35/meta)
- [van der Wel et al 2014](https://iopscience.iop.org/article/10.1088/0004-637X/788/1/28/pdf)
- [Genel et al 2017](https://academic.oup.com/mnras/article/474/3/3976/4675227?login=false)
