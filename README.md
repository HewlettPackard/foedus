[Dashboard] FOEDUS: Fast Optimistic Engine for Data Unification Services
=================================

Overview
--------
FOEDUS is a new transactional key-value store developed at Hewlett-Packard Labs that is optimized
for a large number of CPU cores and NVRAM storage (or fast SSD). It is a handy C++ library you can
either include in your source code (by invoking CMake script) or dynamically link to.
In a nutshell, it is something like BerkeleyDB, but it is much more efficient on new hardware.

For more details, take a look at the [overview paper](http://www.hpl.hp.com/techreports/2015/HPL-2015-37.html).

Repositories
--------
We have split the original repository into a few sub repositories for easier maintenance.

* [foedus_code](https://github.com/hkimura/foedus_code) : **(Waiting for final Open-Sourcing approval)**  Main source code repository.
* [foedus_oa_papers](https://github.com/hkimura/foedus_oa_papers) : Open Access Publication (papers/slides etc) repository.
* foedus_papers : (So far private) Drafts/Non-OA Publication repository.
* [foedus_results](https://github.com/hkimura/foedus_results) : **(Waiting for final Open-Sourcing approval)**  Experimental results and other large binary files.

Most of you would be only interested in [foedus_code](https://github.com/hkimura/foedus_code).
Especially, start with reading READMEs in these folders:

*  [foedus_code](https://github.com/hkimura/foedus_code).
*  [foedus_code/foedus-core](https://github.com/hkimura/foedus_code/foedus-core).

Links
--------
So far all in private network. Trying to migrate to public cloud.

* [HP Labs](http://www.hpl.hp.com/) **We are hiring**.
* [FOEDUS Jenkins server (x86_64)](http://243-1.bfc.hpl.hp.com:8080/) (so far private)
* [FOEDUS Jenkins server (aarch64)](http://ms01915-003.hpl.hp.com:8080/) (so far private)
* [FOEDUS Latest Doxygen HTML](http://243-1.bfc.hpl.hp.com:8080/job/foedus-develop-doxygen/doxygen/) (so far private)
