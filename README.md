# NAME

App::Inspect - Command line tool for inspecting installed modules

# DESCRIPTION

Provides the 'inspect' command which takes module names as arguments. It will
print out the name of the module, the installed version, and where it was
loaded from.

# USAGE

    $ inspect Moose Fake::Module Test::More Scalar::Util

Output:

    Moose        2.1604   is installed at /path/to/Moose.pm
    Fake::Module --       is not installed
    Test::More   1.001014 is installed at /path/to/Test/More.pm
    Scalar::Util 1.41     is installed at /path/to/Scalar/Util.pm
    No::Ver      --       is installed at /path/to/No/Ver.pm

The output will be in color, which cannot be shown in POD.

# SOURCE

The source code repository for App-Inspect can be found at
`http://github.com/exodist/App-Inspect/`.

# MAINTAINERS

- Chad Granum &lt;exodist@cpan.org>

# AUTHORS

- Chad Granum &lt;exodist@cpan.org>

# COPYRIGHT

Copyright 2015 Chad Granum &lt;exodist7@gmail.com> and Dreamhost.

This program is free software; you can redistribute it and/or
modify it under the same terms as Perl itself.

See `http://dev.perl.org/licenses/`
