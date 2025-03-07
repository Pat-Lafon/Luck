# ReadMe

## Running

`cabal build` using `ghc` and `cabal` installed from `ghcup`.

`ghc --version` should
say `The Glorious Glasgow Haskell Compilation System, version
9.6.6`

You can run a specific example file using

`cabal run luck -- examples/Tree.luck`


## How I think enumeration works?



## Help page

```
❯ cabal run luck -- --help
The flags program

flags [OPTIONS] FILE

Common flags:
     --fun=ITEM ---function
     --mode=RUNMODE ---runmode
  -r --reps=INT ---evaltries
  -f --full-output[=INT] ---fulloutput    With no argument, do not truncate
                                          the output. With INT, keep INT
                                          internal nodes.
  -n --no-sample ---nosample              Do not sample holes
     --maxUnroll=INT ---maxunroll         Maximum number of times to unroll a
                                          function
     --max-backtrack=INT ---maxbacktrack
  -d --default-depth=INT ---defdepth
     --irmin=INT ---intrangemin           Bottom of default int range
     --irmax=INT ---intrangemax           Top of default int range
  -? --help                               Display help message
  -V --version                            Print version information
```