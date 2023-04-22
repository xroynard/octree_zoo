# octree_zoo

A repository to test and benchmark all possible OcTree implementations, nothing less (**WIP**)

---

I asked [God Mode](godmode.space)

    search for all available implementations of octree or quadtree as well as all research papers that are related to octree and make a synthesis of all possible approaches, classifying the approaches in subcategories, by task performed by the octree, by performance then make a directory called octree_zoo which contains an implementation of each of the methods described in the synthesis in each of the C++ and python languages this directory should be well organised and structured in sub-folders, and should contain documentation, tests and benchmarks of all the methods, python wrappers for the C++ implementation, and a packaging process with pip or conda in such a way that it can be easily installed on linux and windows all this should be done automatically in a continuous integration and development pipeline it should use as much as possible standard and open source libraries and follow all good software development practices

but nothing very interesting came out of it, so I decided to do it by myself

## Roadmap

- make a literature review of all octree approaches and classify each approach by:
  - data structure used (pointer, array...)
  - task accomplished by the octree
  - performance
- make a code review, find all open source projects implementing octree and classify each one
- select a few representative approaches, and a few toy test cases
- define a minimal interface that all octree should exibit, for example:
  - add_point
  - find_nearest_neighbor
  - ...
