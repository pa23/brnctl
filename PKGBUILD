# Maintainer: Artem Petrov <pa2311@gmail.com>

pkgname=brnctl
pkgver=1.0.0
pkgrel=1
epoch=
pkgdesc="LCD brightness control."
arch=('any')
url=
license=('GPL3')
groups=()
depends=()
makedepends=()
checkdepends=()
optdepends=('acpid')
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=brnctl.install
changelog=
source=($pkgname-$pkgver-src.tar.gz)
noextract=()
md5sums=('') #generate with 'makepkg -g'

package() {
    cd ${srcdir}/$pkgname-$pkgver
    mkdir $pkgdir/usr
    mkdir $pkgdir/usr/bin
    cp brnctl $pkgdir/usr/bin/brnctl
    cp brnctl_brightnessup $pkgdir/usr/bin/brnctl_brightnessup
    cp brnctl_brightnessdown $pkgdir/usr/bin/brnctl_brightnessdown
    mkdir $pkgdir/usr/share
    mkdir $pkgdir/usr/share/brnctl
    mkdir $pkgdir/usr/share/brnctl/doc
    cp README $pkgdir/usr/share/brnctl/doc/README
    cp COPYING $pkgdir/usr/share/brnctl/doc/COPYING
    cp AUTHORS $pkgdir/usr/share/brnctl/doc/AUTHORS
}
