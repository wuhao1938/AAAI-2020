# AAAI-2020
Prediction of particle radiative heat transfer flux is an important
task in the large discrete granular systems, such as pebble
bed in power plants and industrial fluidized beds. For particle
motion and packing, discrete element method (DEM) now is
widely accepted as the excellent Lagrangian approach. For
thermal radiation, traditional methods focus on calculating
the obstructed view factor directly by numerical algorithms.
The major challenge for the simulation is that the method is
proven to be time-consuming and not feasible to be applied
in the practical cases. In this work, we propose an analytical
model to calculate macroscopic effective conductivity from
particle packing structures Then, we develop a deep neural
network (DNN) model used as a predictor of the complex
view factor function. The DNN model is trained by a large
dataset and the computational speed is greatly improved with
good accuracy. It is feasible to perform real-time simulation
with DNN model for radiative heat transfer in large pebble
bed. The trained model also can be coupled with DEM and
used to analyze efficiently the directional radiative conductivity,
anisotropic factor and wall effect of the particle thermal
radiation.
