# Demo datasets for the Spectre package

Main page: https://immunedynamics.github.io/spectre/

<br /> 

**Datasets**:

`demo.start.RData`: flow cytometry data

`demo.asinh.RData`: flow cytometry data with arcsinh transformed values

`demo.clustered.RData`: flow cytometry data with arcsinh transformed values, clustering, UMAP coordinates, and annotated cell types

`demo.batches.1.RData`: flow cytometry data multiple batches

`demo.exp.RData`: summarised expression values per cluster

`demo.sum.RData`: summarised population data (cells per population per sample, etc)

<br /> 

**Example**:

In R, run ```load(url("https://github.com/ImmuneDynamics/data/blob/main/demo.clustered.RData?raw=TRUE"))```

An object called `demo.clustered` should appear in your global environment.
 
