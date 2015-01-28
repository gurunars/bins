lin
===

Installs a package located on a local machine with all its dependencies.

::

  sudo lin /path/to/pkg.one.deb ../path/to/pkg.two.deb

replace
=======

Recursively replaces a string with a substring in all the files in a current directory

::

  replace "string" "substring"

killsome
========

Kills all the processes with a specific name under the current bash session. It is not an
alternative to `killall` even though it does somewhat the same thing.

::

  killsome python
