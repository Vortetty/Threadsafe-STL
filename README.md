# Threadsafe-STL

Threadsafe versions of C++17 STL containers.

Essentially thin wrappers around the existing STL, that add a mutex so that youi can't read and write simutaniously.

## Usage

compatible with existing stl, just replace `std::<container>` with `std::threadsafe::safe_<container>`

## Implemented containers

#### Sequence Containers

- [ ] Array
- [x] Vector
- [x] Deque
- [ ] Forward List
- [ ] List

#### Container Adaptors

- [ ] Stack
- [ ] Queue
- [ ] Priority Queue

#### Associative Containers

- [ ] Set
- [ ] Multiset
- [ ] Map
- [ ] Multimap

#### Unordered Associative Containers

- [ ] Unordered Set
- [ ] Unordered Multiset
- [ ] Unordered Map
- [ ] Unordered Multimap
