TEST 001: base ref has a scanning result, and check-licenses.yml works as expected

TEST 002: base ref does not have a scanning result, but recent commits to the base ref do, and check-licenses.yml works as expected

TEST 003: neither the base ref nor recent commits have scanning results, and check-licenses.yml fails as expected

TEST 004: if no workflow is run (i.e. license scan) for a manual merge commit, scanning results from recent commits are used....

TEST 005: