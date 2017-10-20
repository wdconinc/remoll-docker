# Remoll Docker

Container for [remoll](https://github.com/JeffersonLab/remoll) software used in the Jefferson Lab 12 GeV Moller simulation.

**Note**: This image will allow you to use remoll in batch mode only. A separate image supporting the GUI mode will be available soon.

### Running remoll with docker

```
docker run --rm \
    -v `pwd`/output:/jlab/2.1/Linux_CentOS7.3.1611-x86_64-gcc4.8.5/remoll/rootfiles/ \
    jeffersonlab/remoll [macro to run]
```

The root files produced by remoll will be present in the output directory.

