maintainer="Yunus Emre YOLDAŞ <yoldas.emre@anticverse.com>"

# Package name
pkgname=homeless-openrc

# Package version
pkgver=1.0

# Package release number
pkgrel=0

# Package description
pkgdesc="OpenRC service for homeless"

# URL for more information about this package
url="https://github.com/gAtrium/homeless-openrc"

license="MIT"
depends="homeless"
arch="all"
source="homeless"
options="!check"

build() {
    return 0
}

package() {
    mkdir -p "$pkgdir"/etc/init.d
    install -m 755 "$srcdir"/homeless "$pkgdir"/etc/init.d/homeless
}
