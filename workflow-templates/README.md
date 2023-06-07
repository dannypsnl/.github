# workflow dev note

We must create templates in different name, even they are in the different directories, for example, we have

1. [`./julia/julia-test.yml`](./julia/julia-test.yml)
2. [`./racket/racket-test.yml`](./racket/racket-test.yml)
3. [`./lean/ci.yml`](./lean/ci.yml)

We would like to have `./racket/test.yml` and `./julia/test.yml`, but this is impossible, if we do that, both templates will disappear.

The same logic stands for icon.
