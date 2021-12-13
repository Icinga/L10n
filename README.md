# Icinga - L10n

L10n (short for *Localization*) is the central location for all translations available
for Icinga.

## Installation

We provide packages for [supported platforms](https://icinga.com/subscription/support-details/).
The package's name is `icinga-l10n` and should already be installed if you've got Icinga Web 2
or the Icinga CLI installed. (More info at https://packages.icinga.com)

If there's no package available for your platform, install Icinga L10n in `/usr/share/icinga-L10n`
and Icinga Web 2 or the Icinga CLI (v2.8+) will detect and use it already. (Restart php-fpm or your
web server if not)

It's also possible to place it in a different path and pass an environment variable to Icinga Web 2
or the Icinga CLI: `ICINGAWEB_LOCALEDIR=/var/www/icinga/L10n/locale`

## Contributing

We manage translations now on [translate.icinga.com](https://translate.icinga.com). We don't accept
pull requests on Github anymore. To report bugs in either source or translation strings, please also
head over there and [lookup](https://translate.icinga.com/projects/icinga/#search) the offending
string and add a comment to it in the respective scope.
