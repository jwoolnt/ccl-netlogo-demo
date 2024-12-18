
# NetLogo Demo

This small opinion model was created to gain hands-on practice using [NetLogo](https://ccl.northwestern.edu/netlogo/).

**NOTE**: This model is being further developed to be used as an example for the [NetTango](https://ccl.northwestern.edu/nettangoweb/) project, however, since it is no longer just a demo model, further progress will be continued in [a different repository](https://github.com/jwoolnt/ccl-opinion-model).

## About the Model

The model is meant to simulate opinion dynamics (specifically polarization and segregation of opinion) in a given population. There are two modes the model can be in: binary, where agents can have 1 of 2 opinions; and spectrum, where agents can hold an opinion somewhere on a spectrum between two sides. At a high level, the model works by having the agents update their opinion according to the local mode or mean opinion, depending on whether the model is in binary or spectrum mode. Additionally, each agent tracks internal values such as how "stubborn" they are, how many people they pay attention to, etc. Both modes will display segregation of opinion over time, and in addition, spectrum mode will also show polarization over time.
