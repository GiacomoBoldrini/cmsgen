# cmsgen
Repository for various gridpacks generation fragments

---------------

# Inclusive WW

```
 ssh -Y <username>@login-el7.uscms.org
 cmsrel CMSSW_10_6_0
 cd CMSSW_10_6_0/src
 
 git clone --branch UL2019 https://github.com/cms-sw/genproductions.git
 cd genproductions/bin/MadGraph5_aMCatNLO
 git clone 
 
 ./gridpack_generation.sh <card_name> <card_dir>
```
