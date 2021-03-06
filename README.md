**Phabricator** is an open source collection of web applications which help software companies build better software.

Phabricator includes applications for:

  - reviewing and auditing source code;
  - hosting and browsing repositories;
  - assembling a party to venture forth;
  - tracking bugs;
  - managing projects;
  - writing stuff down and reading it later;
  - hiding stuff from coworkers; and
  - also some other things.

You can learn more about the project (and find links to documentation and resources) at [Phabricator.org](http://phabricator.org)

Phabricator is developed and maintained by [Phacility](http://phacility.com). The first version of Phabricator was originally built at Facebook.

----------

**BUG REPORTS**

Please update your install to **HEAD** before filing bug reports. Follow our [bug reporting guide](https://secure.phabricator.com/book/phabcontrib/article/bug_reports/) for complete instructions.

**FEATURE REQUESTS**

We're big fans of feature requests that state core problems, not just 'add this'. We've compiled a short guide to effective upstream requests [here](https://secure.phabricator.com/book/phabcontrib/article/feature_requests/).

**COMMUNITY CHAT**

Please visit our [IRC Channel (#phabricator on FreeNode)](irc://chat.freenode.net/phabricator) to talk with other members of the Phabricator community. There might be someone there who can help you with setup issues or what image to choose for a macro.

**SECURITY ISSUES**

Phabricator participates in HackerOne and may pay out for various issues reported there. You can find out more information on our [HackerOne page](https://hackerone.com/phabricator).

**PULL REQUESTS**

We do not accept pull requests through GitHub. If you would like to contribute code, please read our [Contributor's Guide](https://secure.phabricator.com/book/phabcontrib/article/contributing_code/) for more information.

**LICENSE**

Phabricator is released under the Apache 2.0 license except as otherwise noted.
=======
docker-phabricator
==================
Dockerfile with debian:jessie / mysql / phabricator


Run
----
Build and run
---------------

```
./build.sh
./run-server.sh
````

Go to http://localhost:8081
On Mac  http://192.168.59.103:8081

You can connect into container with this command :
```
docker exec -it <containerId> bash
```

Mysql files are written on `/data/phabricator/mysql` (described in run-server.sh)

Conf files are written on `/data/phabricator/conf` (described in run-server.sh)

Repositories files are written on `/data/phabricator/repo` (described in run-server.sh)
