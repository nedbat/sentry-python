This is a fork for debugging https://github.com/coveragepy/coveragepy/issues/2082

Mostly I've used variants of this command:

```bash
$ rm -rf /tmp/foo.out; COVERAGE_SYSMON_LOG=1 tox -qe py3.14-common-nb  -- -k test_basics
...................ss...............sss................................................................................                                    [100%]
  py3.14-common-nb: OK (24.51 seconds)
  congratulations :) (26.17 seconds)
