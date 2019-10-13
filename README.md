# Prediction of the Critical temperature of Superconductor

## Introduction
Superconductivity is a phenomenon of exactly zero electrical resistance and
expulsion of magnetic flux fields occurring in certain materials, called super-
conductors, when cooled below a characteristic critical temperature. Supercon-
ductors are widely used in many industry fields, e.g. the Magnetic Resonance
Imaging (MRI) in health care, electricity transportation in energy industry and
magnetic separation, etc.
Predicting the critical temperature (Tc) of a superconductor is still an open
problem in the scientific community. In the past, simple empirical rules based on
experiments have guided researchers in synthesizing superconducting materials
for many years. Nowadays, features (or predictors) based on the superconduc-
tor's elemental properties can be generated and used to predict Tc.
In this task, we are going to analyze superconductor data from the Super-
conducting Material Database maintained by Japan's National Institute for Ma-
terials Science (NIMS). The aim is to build statistical models that can predict
Tc based on the material's chemical properties.
Specifically, We are going to analyse a superconductor data set, which is
based on real world material science data. The problem that we are trying to solve
is: Can we
- predict the critical temperature Tc given some chemical properties of a
material?
- explain our prediction and the associated findings? For example, describe the key properties associated with the response variable.

## Data set
The data set was originally from from the Superconducting Material Database maintained by Japan's National Institute for Materials Science(NIMS). It contains 21,263 material records, each of which have 82 columns: 81 columns corresponding to the features extracted and the last 1 column of the observed Tc values. Among those 81 columns, the first column is the number of elements in the material, the rest 80 columns are features extracted from 8 properties (each property has 10 features).
