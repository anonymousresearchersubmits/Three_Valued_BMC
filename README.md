# Three_Valued_BMC
Developing an algorithm for Three-Valued BMC , and tested on usecases.
Project submitted initially for HSCC2027


## Dependencies
To run the experiments:
- Ocaml >v5.0 (we use v5.4.1)
- opam
- Dune >v3.7 (we use v3.24.2)
- Z3 (we use v5.0.1)
- LustreC and LustreV/Zustre.


## Commands to run experiments
General LustreV command: 
$ time dune exec -- lustrev -node evaluation -zustre -zustre-timeout [timeout_zustre] -d [your_preferred_directory] [lustre_file_name]

For :
- file -> "file.lus", with main node "evaluation"
- file location -> "~/repo/"
- output location -> "~/repo/out/"

Command (with a timeout of 900000): 
dune exec -- lustrev -node evaluation -zustre -zustre-timeout 900000 -d ~/repo/out ~/repo/file.lus

Check lustrev --help for other options (e.g. -zustre-bmc-dump to obtain the .smt2 file)
