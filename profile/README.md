# Hello World!©®™

Welcome to The Hello Corporation, an organization
where all the software is Hello World.

Many other Enterprises in the software space think
we have it easy over here at The Hello Corporation,
because all our software is trivial.

Outsiders seem to think we're a bunch of slackers who
sit around doing nothing and getting high all the time,
which is absolutely untrue, although admittely our
name does spell THC©®™.

In reality, we find that software development at
The Hello Corporation is just as complex and difficult
as it is at other enterprises.

This is not a joke.

We're not making things complex on purpose to make
fun of over-engineered software, like the classic
"Fizzbuzz Enterprise Edition" repo, though that one
was pretty good.

We're absolutely serious.

And recently, the developers at Hello Corporation
have been finding that it's taking them longer and
longer to get anything done, despite extensive efforts
we've put into documention.

If you're reading this, you've been selected for an
interview based on your expertise and obvious charm.

The interview process will consist of one challenge.

We call it:

_The Scalable Hello World Challenge!_

Based on your background, you clearly know a thing or
two about software development.

So we want you to help us simplify things around here,
so our developers can spend less time doing things
manually, and more time writing quality Hello Worlds
at higher levels.

Oh, right, I haven't explained levels.

Let's dive into that topic now.

## Level 1

These are Hello Worlds that have no runtime dependencies
outside of the standard library of the language in which
they are written.

For example, a Hello World in C that uses `<stdio.h>` and
`printf` would be considered a Level 1 Hello World, as would
a Hello World in Python that uses only the `print` builtin,
or a slightly different program in Python that consists of
`import os` followed by `os.system('echo Hello World')`.

Level 1 Hello Worlds are typically the ones that laymen
outside of the Hello World Industry think of when they hear
the term Hello World.

See the following repositories for examples of Level 1:

```
https://github.com/orgs/hello-corporation/repositories/c-bin
https://github.com/orgs/hello-corporation/repositories/c-lib
https://github.com/orgs/hello-corporation/repositories/sh-lib
https://github.com/orgs/hello-corporation/repositories/sh-bin
https://github.com/orgs/hello-corporation/repositories/python-bin
https://github.com/orgs/hello-corporation/repositories/python-lib-file
https://github.com/orgs/hello-corporation/repositories/python-lib-package
https://github.com/orgs/hello-corporation/repositories/python-pyproject
```

Level 1 is simple enough. Now onto Level 2.

## Level 2

These are Hello Worlds that depend on one or more other
Hello Worlds written in the same programming language.

One example would be a python project A that depends on
another python project B via the legacy method `setup.py`,
or the more modern method of `pyproject.toml`. In A's
pyproject.toml it declares its dependency on B, either
as a bare name (if B is on the Python Package Index)
or as a Github URL or following any of the other methods.

Another example would be a C project A that depends on
a shared library libB.so. These dependencies are usually
declared in READMEs and have to be collected manually
by the heroes who created things like:

The Linux from Scratch project
https://www.linuxfromscratch.org/lfs/view/stable/

and that knowledge is passed down the line to the monk-like
individuals we call distribution maintainers.

These language specific dependencies are as variable
as the programming languages in which they're written,
and some languages pull this off much better than others.


## Level 3

Don't be afraid, Level 3 isn't much harder than Level 2
was in C, but it's considerably harder than Level 2 in
most modern languages.

So what's a Level 3 Hello World, I hear you ask?

These are Hello Worlds that depend on one or more other
Hello Worlds written in either a different programming
language, or in no language at all. For example, data
dependencies are Level 3 dependencies, and the repos
with such dependencies are Level 3 Hello Worlds.

Simple enough, right?

Can't be that hard to solve a problem like this.

All we need is a solution to scaling a system of
Level 3 Hello Worlds that works on every major operating
system.

Let us know when you've got a working POC of how to
help us scale.

One last thing: The Hello World industry is all about
simplicity. So whatever you build as a POC to help us
scale, we're not looking for PRs that ask us to add a
top level "your-solution.yaml" (or whatever) file in
each of our repos.

We're leaders in the Hello World industry after all,
and we would look pretty ridiculous if we did something
complex and ugly like that.

Sincerely,
-The Hello Corporation©®™
