# Li Li
  - Introduction:
    * False sense of security in testing programs part.
  - Technical Approaches:
    * Hashing, HyperLogLog, Bloom Filter, Count-Min Sketch.
  - Experimental results:
    * LCOV coverage results.
  - Related Work:
    * QuickCheck, QuickCheck: A Lightweight Tool, Hypothesis, khmer, The economics of software correctness,
    * Automatic predicate Abstraction of C Programs.
  - References
  - Tests run:
    * test_hypothesis_fuzzer, generating test inputs without format restraints to feed the test cases.
    * test_hypothesis.py, test cases fed with valid inputs.
    * test_countgraph_undercounting_bigcounts(kmers: testing countgrapgh undercounting with big count feature.

# Mousumi Chattaraj:
- Technical approaches:
  Installation of khmer project- tried ubuntu machine but ubuntu 13 did not work,
  so upgraded to ubuntu 14 which did not go so well. Installed project in virtual machine in windows.
  Designed what kind of tests will be written. Implemented some of the tests. Used Travis CI and coveralls
  to see coverage information. Used LCOV to see function coverage.
- Read documentation for installing khmer and other information.Read all the papers.
- Wrote tests for countgraph and nodegraph. Ran all of the tests.
  * test_hypothesis.py, test cases fed with valid inputs.  
  * test_countgraph_undercounting_bigcounts_consume(kmers): testing countgraph undercounting, using the bigcount feature and using consume.
- Modified all sections of report.
