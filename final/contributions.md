# Li Li
  1)Introduction:
    False sense of security in testing programs part.
  2)Technical Approaches:
    Hashing, HyperLogLog, Bloom Filter, Count-Min Sketch.
  3)Experimental results:
    LCOV coverage results.
  4)Related Work:
    QuickCheck, QuickCheck: A Lightweight Tool, Hypothesis, khmer, The economics of software correctness,
    Automatica predicate Abstraction of C Programs.
  5)References
  6)Tests run:
    test_hypothesis_fuzzer, generating test inputs without format restraints to feed the test cases.
    test_hypothesis.py, test cases fed with valid inputs.
    test_countgraph_undercounting_bigcounts(kmers: testing countgrapgh undercounting with big count feature.

# Mousumi Chattaraj:
1)Technical approaches:
  Installation of khmer project- tried ubuntu machine but ubuntu 13 did not work,
  so upgraded to ubuntu 14 which did not go so well.Installed project in virtual machine in windows.
  Designed what kind of tests will be written.Implemented some of the tests.Used Travis CI and coveralls
  to see coverage information.Used LCOV to see function coverage.
2)Read documentation for installing khmer and other information.Read all the papers.
3)Wrote tests for countgraph and nodegraph. Ran all of the tests.
  test_hypothesis.py, test cases fed with valid inputs.  
  test_countgraph_undercounting_bigcounts_consume(kmers): testing countgraph undercounting, using the bigcount feature and using consume.
4)Modified all sections of report.
