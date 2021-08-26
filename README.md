# Cisco package of Linux PAM

This is the Cisco Linux PAM package, forked from the Ubuntu 18.04
http://archive.ubuntu.com/ubuntu/pool/main/p/pam/pam_1.1.8-3.6ubuntu2.18.04.3.tar.gz
source package.  This package is identical to the origianl Ubuntu
package, with the exception that two additional patches were added to
this package, back-ported from the Linux PAM repository:

* https://github.com/linux-pam/linux-pam/commit/55f206447a1e4ee26e307e7a9c069236e823b1a5,
  and
* https://github.com/linux-pam/linux-pam/commit/80bfda5962e5be3daa70e0fc8c75fc97d1c55121

And an `cisco-package-version.json` file included in the
`libpam0g*.deb` file.

This package is not supported by Ubuntu.
