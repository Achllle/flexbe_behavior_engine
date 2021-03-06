^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package flexbe_testing
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.2.3 (2020-01-10)
------------------
* Merge pull request `#97 <https://github.com/team-vigir/flexbe_behavior_engine/issues/97>`_ from team-vigir/feature/test_behaviors
  flexbe_testing support for behaviors
* [flexbe_testing] Remove deprecated state tester
* [flexbe_testing] Allow specification of behavior name in test config
* [flexbe_testing] Add support for behavior tests
* Merge remote-tracking branch 'origin/develop' into feature/test_behaviors
  # Conflicts:
  #	flexbe_testing/bin/testing_node
  #	flexbe_testing/src/flexbe_testing/state_tester.py
* Merge pull request `#94 <https://github.com/team-vigir/flexbe_behavior_engine/issues/94>`_ from LoyVanBeek/feature/check_missing_testfile
  Fail test if provided test-yaml-file does not exist
* Generate test results also when test file is missing
* Move test configuration files to StateTester so failing to configure can also be included in the test results
* Fail test if provided test-file does not exist
  There is no way to know which arguments are intended to be filenames, so best we can do is guess?
* [flexbe_testing] Refactor testing framework as basis for new feature
* Contributors: Loy van Beek, Philipp Schillinger

1.2.2 (2019-09-16)
------------------

1.2.1 (2019-06-02)
------------------
* [flexbe_testing] Respect state rate in tests (fix `FlexBE/flexbe_app#36 <https://github.com/FlexBE/flexbe_app/issues/36>`_)
* Merge remote-tracking branch 'origin/feature/sub_parameters' into develop
* Bump required flexbe_app version
* Merge remote-tracking branch 'origin/master' into develop
* Contributors: Philipp Schillinger

1.1.2 (2019-04-09)
------------------
* Merge remote-tracking branch 'origin/master' into develop
* Contributors: Philipp Schillinger

1.1.1 (2018-12-18)
------------------
* Merge remote-tracking branch 'origin/develop'
* Revise run dependencies
* Merge remote-tracking branch 'origin/master' into develop
* Contributors: Philipp Schillinger

1.1.0 (2018-12-01)
------------------
* Merge branch 'develop'
* Merge branch 'feature/flexbe_app' into develop
* Update maintainer information
* Merge remote-tracking branch 'origin/fix/state_tests' into feature/flexbe_app
* [flexbe_testing] Let "pass" test fail if preparation fails
* [flexbe_testing] Install rostest files for install-space testing
* Merge branch 'develop' into feature/flexbe_app
* Merge branch 'develop'
* [flexbe_testing] Correct states for selftest (fix `#49 <https://github.com/team-vigir/flexbe_behavior_engine/issues/49>`_)
* Merge remote-tracking branch 'origin/master' into develop
* Merge pull request `#24 <https://github.com/team-vigir/flexbe_behavior_engine/issues/24>`_ from fmauch/7-state_test_output_data_missing
  [flexbe_testing] complain if output data is requested inside the test but not given
* complain if output data is requested inside the test, but not given
  from the state
* Merge remote-tracking branch 'origin/develop'
* [flexbe_testing] Added optional waiting condition for attached launch files
* Merge remote-tracking branch 'origin/master'
* fix bug in state_tester.py
* Merge remote-tracking branch 'origin/master' into feature/multirobot
  Conflicts:
  flexbe_core/src/flexbe_core/core/monitoring_state.py
  flexbe_core/src/flexbe_core/core/operatable_state.py
* [flexbe_testing] Added self tests
* [flexbe_testing] Added test case for passing flexbe tests
* [flexbe_testing] Only require package arg if performing rostest
* [flexbe_testing] Added rostest integration
* [flexbe_testing] Start launchfile before importing the state
* [flexbe_testing] Added feature to specify launch files in test cases
* [flexbe_testing] Set correct file permissions for testing node
* [flexbe_testing] Call on_start and on_stop events of states
* [flexbe_testing] Added import_only option for tests
* [flexbe_testing] Added launch file for running a set of test cases
* [flexbe_testing] Added parameters for output format configuration
* [flexbe_testing] Removed temporary example files
* [flexbe_testing] Correctly shut down on ctrl+c during a test
* [flexbe_testing] Added initial version of unit testing framework for evaluation
* Contributors: David Conner, Felix Mauch, Philipp Schillinger
