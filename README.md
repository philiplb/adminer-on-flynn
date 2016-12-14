Adminer on Flynn
================

This is a small project to deploy [Adminer 4.2.5](https://www.adminer.org) to
a [Flynn](http://flynn.io/) cluster.

It is handy if you want administrative access to your Flynn DBs but don't
want to open direct
[external](https://flynn.io/docs/databases/postgres#external-access)
[access](https://flynn.io/docs/databases/mysql#external-access).

# Setup

Create an application as usual:

```bash
flynn create adminer
```

# Initial Deployment and Updates

Push this repository towards Flynn:

```bash
git push flynn master
```

# License

This software is licensed under the
[MIT License](https://opensource.org/licenses/MIT). Adminer itself (index.php)
is licensed under the
[Apache License](https://www.apache.org/licenses/LICENSE-2.0.html).
