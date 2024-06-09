# DL_SOC
The goal of this project is to estimate State of charge (SOC) of Li-ion batteries using Deep learning models for EV applications.
Li-ion Batteries currently dominate The EV industry due to their comparably higher power and energy density among  market mature technoloies. Among other challenges of this technologies (e.g. high sensitivy for operational conditions, Safety), battery state modeling like State of charge (SOC), State of Helath (SOH) is challenging. The difficulty arises from the non-linear behavior of the battery state w.r.t  parameters like Voltage,Current, current, and temperature. Moreover, different battery chemistries have their own non-linearity profiles. This problem had been approached using different modeling techniques, like empirical models, Electrochemical models, Equivalent circuit models and data-driven models (black box). The project effort belongs to the last group which uses Time series Deep learning networks (LSTM, GRU) for SOC estimation.


## Dataset
Dataset used for models training is the 18650 cell [LG18650HG2](https://data.mendeley.com/datasets/b5mj79w5w9/2) dataset , which had been collected by researches in McMaster Universityin  Hamilton, Ontario, Canada . This rich dataset includes different load cases, including constant load, load Pulse and standardized driving cycles (USSD, US06, HWFET, LA92, mixed cycles), each collected at  controlled temperatures of (-20°C, -10°C, 0°C, 10°C, 25°C, 40°C). Only the driving cycle data has been used for model training, since this data group represents the desired application (EV). 


## Result 

## usage

## Environment Setup
Models had been developed using Python and Tensorflow framework
Python libraries used are numy, pandas, tensorflow, kera, in addition to utility packages like os, time, datetime, psutil and matplot package for graphing


## Contributors 
Mohammad Tahoon - Hochschule Rhein-Waal

## Acknowlegements
Kollmeyer,  Phillip; Naguib, Mina; Skells, Michael  (2020), “LG 18650HG2 Li-ion Battery Data”, Mendeley Data, V2, doi: 10.17632/b5mj79w5w9.2
