# Welcome to Perltidy

Perltidy is a Perl script which indents and reformats Perl scripts to make them
easier to read.  If you write Perl scripts, or spend much time
reading them, you will probably find it useful.

Perltidy is free software released under the GNU General Public
License -- please see the included file [COPYING](./COPYING.txt) for details.

The formatting can be controlled with command line parameters.  The default
parameter settings approximately follow the suggestions in the
[Perl Style Guide](https://perldoc.perl.org/perlstyle.md).

Besides reformatting scripts, Perltidy can help in tracking
down errors with missing or extra braces, parentheses, and square brackets
because it is very good at localizing errors.

## Documentation

- [A Brief Perltidy Tutorial](./tutorial.md)

- [Perltidy Style Key](./stylekey.md) will help
 in methodically selecting a set of style parameters.

- [The Perltidy man page](./perltidy.md) explains how
to precisely control the formatting details.

- [The Perl::Tidy man page](./Tidy.md) discusses how to use the Perl::Tidy module

- [Change Log](./ChangeLog.md)


## Prerequisites

Perltidy should run on any system with perl 5.008 or later.
The total disk space needed after removing the installation directory will be
about 2 Mb.


## Download


- The most recent release is always at [CPAN](https://metacpan.org/release/Perl-Tidy)

- The most recent release is also at [sourceforge](https://sourceforge.net/projects/perltidy/)

- For related modules search CPAN for [perltidy](https://metacpan.org/search?q=perltidy)


## Installation

Perl::Tidy can be installed directly from CPAN one of the available methods.

One way is to download a distribution file, unpack it and then 
test and install using the Makefile.PL:

    perl Makefile.PL
    make
    make test
    make install

The [INSTALL file](./INSTALL.md) has additional installation notes, and tells how
to use perltidy without doing an installation.


## Links

 - [Perl::Tidy source code repository at GitHub](https://github.com/perltidy/perltidy)
 - [Tidyview](http://sourceforge.net/projects/tidyview) is a graphical program for tweaking your .perltidyrc configuration parameters.
 - [A perltidy plugin for Sublime Text 2/3](https://github.com/vifo/SublimePerlTidy)


## FEEDBACK / BUG REPORTS

A list of current bugs and issues can be found at the CPAN site [https://rt.cpan.org/Public/Dist/Display.html?Name=Perl-Tidy](https://rt.cpan.org/Public/Dist/Display.html?Name=Perl-Tidy)

To report a new bug or problem, use the link on this page .