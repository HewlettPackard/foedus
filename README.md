# foedus
[Dashboard] FOEDUS: Fast Optimistic Engine for Data Unification Services
=================================

Overview
--------
FOEDUS is a new transactional key-value library developed at Hewlett-Packard Labs that is optimized
for a large number of CPU cores and NVRAM storage. It is a handy C++ library you can
either include in your source code (by invoking CMake script) or dynamically link to.
In a nutshell, it is something like BerkeleyDB, but it is much more efficient on new hardware.

For more details, take a look at the [overview paper](https://github.com/hkimura/foedus_oa_papers/raw/master/foedus_sigmod2015_cr.pdf).

Repositories
--------
We have separated the project into a few sub repositories for easier maintenance.

* [foedus_code](https://github.com/hkimura/foedus_code) : **Waiting for final Open-Sourcing approval**  Main source code repository.
* [foedus_oa_papers](https://github.com/hkimura/foedus_oa_papers) : Open Access Publication (papers/slides etc) repository.
* foedus_papers : (So far private) Drafts/Non-OA Publication repository.
* [foedus_results](https://github.com/hkimura/foedus_results) : **Waiting for final Open-Sourcing approval**  Experimental results and other large binary files.

Most of you would be only interested in [foedus_code](https://github.com/hkimura/foedus_code).
