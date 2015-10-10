Upgrade Plex Script
===================

Upgrade plex on Ubuntu in the easiest way possible

Will result in a noop if the latest version is already available

Usage
-----

    $ sudo ./upgrade-plex
    installed: 0.9.12.11.1406-8403350
    latest: 0.9.12.13.1464-4ccd2ca
    downloading https://downloads.plex.tv/plex-media-server/0.9.12.13.1464-4ccd2ca/plexmediaserver_0.9.12.13.1464-4ccd2ca_amd64.deb to /home/dave/.plex/pkg/plexmediaserver_0.9.12.13.1464-4ccd2ca_amd64.deb...
    installing...
    (Reading database ... 30661 files and directories currently installed.)
    Preparing to unpack .../plexmediaserver_0.9.12.13.1464-4ccd2ca_amd64.deb ...
    plexmediaserver stop/waiting
    Unpacking plexmediaserver (0.9.12.13.1464-4ccd2ca) over (0.9.12.11.1406-8403350) ...
    Setting up plexmediaserver (0.9.12.13.1464-4ccd2ca) ...
    plexmediaserver start/running, process 42170
    Processing triggers for ureadahead (0.100.0-16) ...
    Processing triggers for mime-support (3.54ubuntu1.1) ...
    installed version: 0.9.12.13.1464-4ccd2ca
    $

License
-------

MIT License
