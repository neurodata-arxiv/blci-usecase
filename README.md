# blci-usecase

Here we have the following:
- `data` directory containing both input and output data
  - Within `atlas` is a *fixed* input file (i.e. will not change)
  - Within `fibers` is a *variable* input file (i.e. can change and should be versioned)
  - Within `graphs` is a *variable* output folder and files (i.e. produced by the code contained within this repo and should be versioned or compared to newly generated outputs)
  - Within `qc` is a *variable* output folder and files (i.e. QC statistics performed on the derived graphs)
- `code` directory containing a jupyter notebook which produces the graph from fibers
- `Dockerfile` which details the required setup steps to launch a computer with this pipeline installed
