# OcTree Zoo

A repository to test and benchmark all possible OcTree implementations, nothing less (**WIP**)

---

I asked [God Mode](https://godmode.space) but nothing very interesting came out of it, so I decided to do it by myself

## Limitations

We won’t use cloud computing or multi-node parallelism, but we may benefit from multi-core CPU or a single GPU, basically no distributed memory

## Roadmap

- make a literature review of all octree approaches and classify each approach by:
  - data structure used (pointer, array...)
  - task accomplished by the octree
  - performance
- make a code review, find all open source projects implementing octree and classify each one
- select a few representative approaches, and a few toy test cases
- define a minimal interface that all octree should exibit, for example:
  - insert_point(s)
  - find_nearest_neighbor(s)
  - cast_ray(s)
  - ...
- implement this selected approaches in python first, using as much as possible open source and standard libraries
- setup all the good development practices, for example:
  - test with a high coverage goal
  - document each function and class
  - make code modular
  - package the library in conda-forge
  - benchmark all implementations on the toy test cases
  - use continuous integration (CI) pipeline to realize tasks automatically
- implement the same approaches in C++
- make a wrapper to be able to use C++ implementation in python

When all this is correctly setup, we will implement as many as possible of the approaches found in the literature and code reviews
