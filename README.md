# sparkling-graph

[![Join the chat at https://gitter.im/sparkling-graph/sparkling-graph](https://badges.gitter.im/sparkling-graph/sparkling-graph.svg)](https://gitter.im/sparkling-graph/sparkling-graph?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Build Status](https://travis-ci.org/sparkling-graph/sparkling-graph.svg?branch=master)](https://travis-ci.org/sparkling-graph/sparkling-graph) [![Documentation Status](https://readthedocs.org/projects/sparkling-graph/badge/?version=latest&cache=1234)](http://sparkling-graph.readthedocs.org/en/latest/?badge=latest) [![codecov.io](https://codecov.io/github/sparkling-graph/sparkling-graph/coverage.svg?branch=master)](https://codecov.io/github/sparkling-graph/sparkling-graph?branch=master) [![Codacy Badge](https://api.codacy.com/project/badge/grade/9ddff907e39a431485fecaf0f612a528)](https://www.codacy.com/app/riomus/sparkling-graph) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/ml.sparkling/sparkling-graph-examples_2.10/badge.svg)](https://maven-badges.herokuapp.com/maven-central/ml.sparkling/sparkling-graph-examples_2.10) [API](http://sparkling-graph.github.io/sparkling-graph/latest/api/) |  [Spark packages](http://spark-packages.org/package/sparkling-graph/sparkling-graph)

SparklingGraph provides easy to use set of features that will give you ability to proces large scala graphs using Spark and GraphX.

# Dependencies
## Snapshot
```
resolvers +=  "Sonatype OSS Snapshots" at "https://oss.sonatype.org/content/repositories/snapshots"
```
```
libraryDependencies += ml.sparkling % sparkling-graph-loaders % 0.0.5-SNAPSHOT
libraryDependencies += ml.sparkling % sparkling-graph-operators % 0.0.5-SNAPSHOT
```
## Release
```
libraryDependencies += ml.sparkling % sparkling-graph-loaders % 0.0.4
libraryDependencies += ml.sparkling % sparkling-graph-operators % 0.0.4
```

# Current features

* Loading
  * CSV
* Measures - all measures can be configured to treat graphs as directed and undirected
  *  Closeness
  *  Local clustering
  *  Eigenvector
  *  Hits
  *  Neighbor connectivity
  *  Vertex embeddedness
* Experiments
  *  Describe graph using all measures to CSV files

# Planned features
* DSL - easy to use domain specific language that will boost productivity of library
* Loading
  *  GraphML
  *  GML
* Measures
  * Katz
  * Betweenness
* Comunity detection methods
  * Modularity maximization
  * SCAN
  * Infomap 
* API
  *  Random walk
  *  BFS
* ML
  *  Link prediction
  *  Vertex classification
  
# How to

Please check [API](http://sparkling-graph.github.io/sparkling-graph/latest/api/), [examples](https://github.com/sparkling-graph/sparkling-graph/tree/master/examples/src/main/scala/ml/sparkling/graph/examples) or [docs](http://sparkling-graph.readthedocs.org/en/latest/)



# Citation
If you use SparklingGraph in your research and publish it, please consider citing us, it will help us get funding for making the library better.
Currently manuscript is in preparation, so please us following references:

 ``` Bartusiak R. (2016). SparklingGraph: large scale, distributed graph processing made easy. Manuscript in preparation. ```
 
 ```
@unpublished{sparkling-graph
title={SparklingGraph: large scale, distributed graph processing made easy},
author={Bartusiak R.},
note = {Manuscript in preparation},
year = {2016}
}
```
