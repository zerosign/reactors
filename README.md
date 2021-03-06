CI service | Status | Description
-----------|--------|------------
Travis | [![Build Status](https://travis-ci.org/reactors-io/reactors.png?branch=master)](https://travis-ci.org/reactors-io/reactors) | Linux container tests
Maven | [![Maven Artifact](https://img.shields.io/maven-central/v/com.storm-enroute/reactors_2.11.svg)](http://mvnrepository.com/artifact/com.storm-enroute/reactors_2.11/0.6) | Artifact on Maven

<img src='reactress-title-96.png'></img>

[Reactors.IO](http://reactors.io) is a concurrent, distributed programming framework based
on asynchronous event streams.

- [documentation](http://reactors.io/learn/)
- [download page](http://reactors.io/download/)

# Contributing

You will need to install [SBT](www.scala-sbt.org) build tool on your system.
Once you do that, run:

```
$ sbt
```

Within the `sbt` shell, you can compile the code:

```
> compile
```

You can start continuous compilation whenever your code changes:

```
> ~compile
```

After making changes, submit a pull request to the
[reactors repo at GitHub](https://github.com/reactors-io/reactors).
Tests will be run automatically, and your contribution will be reviewed.
If you want to run tests locally, run `test` or `testOnly <name-of-test>`
in the SBT shell.


# Discussion

Room on Gitter chat: [![Join the chat at https://gitter.im/reactors-io/reactors](https://badges.gitter.im/reactors-io/reactors.svg)](https://gitter.im/reactors-io/reactors?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Mailing list: [Google Groups](https://groups.google.com/forum/#!forum/reactors-io)

Twitter: [Reactors.IO](https://twitter.com/reactors_io)
