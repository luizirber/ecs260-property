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
Since Coveralls doesn't show function coverage,
we are also using [lcov][8] and uploading the results to [this page][9].

## Reproducing the results

We set up an automated build in Docker Hub for the code changes.
After installing Docker (we suggest the [Docker Toolbox][7] if you're running Windows or OSX),
you can run it by executing the following command:

``` bash
$ docker pull luizirber/khmer:latest
$ docker run -it luizirber/khmer:latest
```

If you access to a terminal with the software installed,
you can also do

``` bash
$ docker pull luizirber/khmer:latest
$ docker run -it luizirber/khmer:latest /bin/bash
$ make test
```

The Dockerfile describing how the image is build is available:
https://hub.docker.com/r/luizirber/khmer/

## Final project artifacts

We collected artifacts on [final/artifacts](final/artifacts) for convenience,
but they are also available online (mostly on [PR #1324][1]).
It's is not so easy to visualize this on GitHub,
so you might want to download the repository and open it locally.

- [lcov-report/index.html][11]: LCOV report for function and line coverage.
- [diff.htm][12]: Graphical diff containing our tests and additions to the original codebase.
  This is just a copy of the HTML page of PR #1324 [changes][13] tab.
- [khmer-feature-hypothesis.zip][15]: A snapshot of the git branch,
  downloaded using the [Download ZIP][14] button from the GitHub UI.
- [Dockerfile][16]: Used for creating the image on [Docker Hub][10].
  This is also contained in [diff.htm][12] and in the [snapshot][15].

[1]: https://github.com/dib-lab/khmer/pull/1324
[2]: https://github.com/dib-lab/khmer/
[3]: https://travis-ci.org/
[4]: https://coveralls.io/
[5]: https://travis-ci.org/luizirber/khmer
[6]: https://coveralls.io/github/luizirber/khmer?branch=feature%2Fhypothesis
[7]: https://www.docker.com/docker-toolbox
[8]: https://github.com/linux-test-project/lcov
[9]: http://athyra.oxli.org/~luizirber/ecs260
[10]: https://hub.docker.com/r/luizirber/khmer/
[11]: final/artifacts/lcov-report/index.html
[12]: final/artifacts/diff.htm
[13]: https://github.com/dib-lab/khmer/pull/1324/files
[14]: https://github.com/luizirber/khmer/archive/feature/hypothesis.zip
[15]: final/artifacts/khmer-feature-hypothesis.zip
[16]: final/artifacts/Dockerfile
