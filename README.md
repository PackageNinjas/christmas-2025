# Pack christmas bingo 2025

For this year's holiday season, the SUSE Packaging team has prepared a challenge to all openSUSE Packagers (and those who want to become one): An openSUSE packaging bingo!

## How it works

For each field in the bingo card below find a package in openSUSE:Factory in the [OBS](https://build.opensuse.org) that fits the Requirement.

Each package can only be used once. When you have at least one bingo (meaning one complete row, column or diagonal) you can open an issue in this repository and add the package names in the empty markdown table.
You can leave the free space if you currently don't maintain any packages in openSUSE Factory, otherwise please enter your favourite package to maintain.

> **_Hint:_** [This repo](https://github.com/bmwiedemann/openSUSE) and [this page](https://rpmlint.opensuse.org/) might come in handy for searching

We will then verify your solution for you and mark the issue as either completed or closed.

Extra challenge is to find unique packages that nobody else has found yet.

## Bingo card

|                                              |                                                     |                                                                      |                                                                       |                                                             |
| -------------------------------------------- | --------------------------------------------------- | -------------------------------------------------------------------- | --------------------------------------------------------------------- | ----------------------------------------------------------- |
| Package with 1000+ line spec file            | Non-trivial Package with 0 RPM Lint Errors/Warnings | Package with 25+ patches                                             | Package with the filelist-forbidden-fhs23 RPM Lint Error              | Package with an animal in the name                          |
| Package with a changelog entry from Dec 24th | Package with 5+ year old a FIXME or TODO            | Package with 5+ Sources                                              | Package that uses "Supplements:"                                      | Package with a %post scriptlet longer than 20 lines         |
| Package that uses "\_multibuild"             | Package with more than 20 BuildRequires             | Free space / Package you maintain                                    | Package that builds only for x86_64                                   | Non-Python Package that produces at least one noarch binary |
| Package that builds for non-openSUSE distros | Package where Source is a .zip file                 | Package that redirects output to /dev/null inside the %build section | Package that BuildRequires Python, Perl, AND Ruby in one specfile     | Package that uses a feature introduced in RPM 4.20          |
| Package that does NOT specify %license tag   | Package that fixed at least 5 openSUSE bugs         | Package that does not use %autosetup but does not have any patches   | Package in which the last rpm changelog entry was written before 2023 | Package created in the ‘90s but still developed             |

> **_Note:_** Non-trivial means a package that isn't a dummy or meta package
