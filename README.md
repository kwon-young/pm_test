# [pm_test](https://github.com/kwon-young/pm_test)
Little cmake prolog mali project to experiment the [prolog mali language support with cmake](https://github.com/kwon-young/cmake-pm).

## Usage

* Install CMake.
* Install [prolog mali](https://gforge.inria.fr/projects/prolog-mali/).
* Then install [prolog mali cmake support](https://github.com/kwon-young/cmake-pm).

Then CMake is used as usual:

```
# Out of source build
$ mkdir build
$ cd build

$ cmake ..
$ make
```

Execution:

```
$ cd build; ./PmTest 5
 [5, 4, 3, 2, 1] --> [1, 2, 3, 4, 5]
```

Enjoy !
