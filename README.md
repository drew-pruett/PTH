# Overview

This model of PTH secretion is based on kinetics of the CaSR.  It is designed to run in Berkeley Madonna, which is available as freeware (if you don't care to save or print your work).  

Two models are available in this format.  The first is the time dependent model, and the second is the steady state model.  The parameters are shared between the two models.

#Parameters

kv=intracellular production
kdeg=intracellular degradation
m=cascade coefficient 
kd=dissociation constant of CaSR
GFR=glomerular filtration rate
LFR=liver filtration rate
SVol=serum volume
alpha=fractional permeation constant
beta=tonic permeation constnat
ProtocolFlag=toggles the time dependent model between 4 paradigms, corresponding to 
1. 24-hour PTH bolus
2. 10 days on "normal diet
3. hysteresis induction
4. effects of chronic hyper- and hypocalcemia on the Ca-PTH relationship
flag1 toggles the statistical model between allowing variance in 
1. all
2. kv
3. kdeg
4. alpha
5. beta
6. m
Flag3 toggles the hysteresis induction between pulsed and stepped protocols
Flag4 toggles between hyper-, normo- and hypocalcemia in the fourth protocol


END







