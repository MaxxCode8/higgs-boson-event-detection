# 🌠 Higgs Boson Event Detection ⚛
#### ( New Experimentation: _Optuna_ | _AutoML(pycaret)_ | _Tensorboard_ | _Keras_ )
---

The LHC collides bunches of protons every 50 nanoseconds within each of its four experiments, each crossing producing a random number of proton-proton collisions (with a Poisson expectation between 10 and 35, depending on the LHC parameters) called events8. Two colliding protons produce a small firework in which part of the kinetic energy of the protons is converted into new particles. Most of the resulting particles are very unstable and decay quickly into a cascade of lighter particles.

Based on these properties, the properties of the decayed parent particle are inferred, and the inference chain is continued until reaching the heaviest primary particles. given the elusive nature of neutrinos, their minuscule mass, and the way they oscillate between flavors, one could very well imagine that the mass of leptons comes from an entirely different mechanism. Hence the importance of measuring as precisely as possible the coupling of the Higgs to tau arises.

Particle colliders enable us to probe the fundamental nature of matter by observing exotic particles produced by high-energy collisions. Because the experimental measurements from these collisions are necessarily incomplete and imprecise, machine learning algorithms play a major role in the analysis of experimental data. The high-energy physics community typically relies on standardized machine learning software packages for this analysis and devotes substantial effort towards improving statistical power by hand-crafting high-level features derived from the raw collider measurements.

Problem Statement: 
### With the given dataset, we have to classify whether the given event was a "signal" or a "background" noise in the process of decay for Higgs particle acceleration.

---
#### Managed to Get a Precision of:
#### _0.541889_ (Keras Fine Tunned NN Model)
#### _0.61512_ (Auto ML Extra Trees Classifier Model)
---
### Tensorboard Plots: 
_Epoch Accuracy_ :
![epoch_acc_tensorboard](https://github.com/MaxxCode8/higgs-boson-event-detection/assets/105921273/09fa2488-51a1-40ce-a17c-f8335daf2a74)

_Epoch loss (training) all CV Folds_
![epoch_loss_training on all folds](https://github.com/MaxxCode8/higgs-boson-event-detection/assets/105921273/7b3667b8-f715-41d2-b70f-157abfb9cedf)

_Epcoh loss (validation) all CV Folds_
![epoch_loss_validation all folds](https://github.com/MaxxCode8/higgs-boson-event-detection/assets/105921273/5def9b4d-eec6-43c4-b731-8a581d384cd7)

---
#### [Optuna](https://optuna.org/)
#### [Keras Tensorboard Callbacl](https://keras.io/api/callbacks/tensorboard/)
#### [Pycaret AutoML](https://pycaret.org/automl/)
