This repository contains packages for cross-compilation.

## Significant modifications are required
  * gcc
  * glibc ([riscv-glibc](https://github.com/riscv/riscv-glibc))
  * libcap
  * linux-api-headers (written from scratch)
  * mtd-utils
  * systemd


## Moderate modifications are required
  * ncurses
  * pam


## Minor modifications are required
  * cryptsetup
  * dbus
  * e2fsprogs
  * elfutils
  * flex
  * gmp
  * gpgme
  * groff
  * iana-etc (invalid checksum)
  * jfsutils
  * ldns
  * libaio
  * libgpg-error
  * libpcap
  * libsasl
  * libssh2
  * libtirpc
  * libusb
  * lvm2
  * lzo (CC env var required)
  * make
  * man-db
  * openssl
  * p11-kit
  * pacman
  * pcre
  * procps-ng
  * psmisc
  * sqlite
  * sudo
  * util-linux
  * xz


## Environment modifications are required
  * bzip2 (fake gcc and tools)
  * dhcpcd (env vars)
  * ed (fake gcc and tools)
  * iputils (fake gcc and tools)
  * mdadm (fake gcc and tools)
  * net-tools (env vars)
  * vi (env vars)


## Unmodified packages
  * acl
  * arch-install-scripts
  * archlinux-keyring
  * argon2
  * asp
  * attr
  * autoconf
  * automake
  * bash
  * binutils
  * bison
  * ca-certificates
  * ca-certificates-cacert
  * check
  * coreutils
  * curl
  * db
  * dnssec-anchors
  * expat
  * fakeroot
  * file
  * filesystem
  * findutils
  * gawk
  * gdbm
  * gettext
  * grep
  * gzip
  * htop
  * hwids
  * inetutils
  * iproute2
  * iptables
  * json-c
  * kbd
  * keyutils
  * kmod
  * less
  * libarchive
  * libassuan
  * libcap-ng
  * libedit
  * libgcrypt
  * libidn
  * libidn2
  * libksba
  * libmnl
  * libmpc
  * libnetfilter_conntrack
  * libnfnetlink
  * libnftnl
  * libnghttp2
  * libnl
  * libpipeline
  * libpsl
  * libtasn1
  * libtool
  * libunistring
  * licenses
  * linux-firmware
  * logrotate
  * lz4
  * m4
  * man-pages
  * mkinitcpio
  * mpfr
  * nano
  * netctl
  * nettle
  * npth
  * openresolv
  * pacman-mirrorlist
  * pambase
  * patch
  * popt
  * readline
  * reiserfsprogs
  * sed
  * shadow
  * sysfsutils
  * tar
  * tzdata
  * unixodbc
  * which
  * zlib
