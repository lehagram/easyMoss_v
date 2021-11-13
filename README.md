### easyMoss
# Mossbauer spectrum simulation

easyMoss is a software package for the simulation of 57Fe Mössbauer spectra of powder or solution samples,
   mainly used in the fields of coordination chemistry and metalloprotein biochemistry.
Two models are used : Quadrupole Doublet or Spin Hamiltonian.
Several spectra from either model can be compounded in order to form a composite theoretical spectrum.
Parameters can be adjusted manually or automatically in order for the simulation to fit either one
   or several simultaneous experimental spectra.
57Fe sites simulated in the Spin Hamiltonian model can be coupled together via J-coupling.

____

easyMoss is written in Python3 and is based on a PYQT5 graphical interface.
The following esternal libraries are called 
- numpy
- scipy
- matplotlib
- lmfit (least-squares minimization)
- fbs (application packaging)

____

# License

GNU GENERAL PUBLIC LICENSE
Version 3, 29 June 2007
