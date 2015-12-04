# Practical Property-based testing in scientific software

[Mousumi Chattaraj](https://github.com/Sumi999), [Luiz Irber](https://github.com/luizirber), [Li Li](https://github.com/lili0824)

## Presentations

[Project idea slide](Project idea slide.pdf)

## Proposal

[Presentation](proposal/ECS260 Project Proposal presentation.pdf)

[Report](proposal/ECS260 Project Proposal.pdf)

## Implementation / code progress

Code for the tests is being tracked on [PR #1324][1] on the main [khmer repository][2].

We also set up [Travis][3] and [Coveralls][4] to have [continuous integration][5] and [code coverage reports][6].

## Reproducing the results

We set up an automated build in Docker Hub for the code changes.
After installing Docker (we suggest the [Docker Toolbox][7] if you're running Windows or OSX),
you can run it by executing the following command:

``` bash
$ docker run -it luizirber/khmer
```

If you access to a terminal with the software installed,
you can also do

``` bash
$ docker run -it luizirber/khmer /bin/bash
```

and run

``` bash
$ make test
```

The Dockerfile describing how the image is build is available:
https://hub.docker.com/r/luizirber/khmer/~/dockerfile/

[1]: https://github.com/dib-lab/khmer/pull/1324
[2]: https://github.com/dib-lab/khmer/
[3]: https://travis-ci.org/
[4]: https://coveralls.io/
[5]: https://travis-ci.org/luizirber/khmer
[6]: https://coveralls.io/github/luizirber/khmer?branch=feature%2Fhypothesis
[7]: https://www.docker.com/docker-toolbox
