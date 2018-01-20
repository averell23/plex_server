# Plex box ansible script

A small setup script to set up a plex server using a cheap vServer
and storage solution (e.g. at Hetzner)

The server should be hardened against the usual nuisances and
relatively carefree (autoupdates). The script assumes an ubuntu
base system.

## Warning

This is not a high security setup. The Plex server itself ain't 
exactly hardened, the content list is also accessible by plex.tv
and mounting CIFS/Samba shares over the internet is not the safest
thing to do either.

So don't have confidential files mounted in the storage share.

