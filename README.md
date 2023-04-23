# octree_zoo

A repository to test and benchmark all possible OcTree implementations, nothing less (**WIP**)

---

I asked [God Mode](https://godmode.space) but nothing very interesting came out of it, so I decided to do it by myself

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
