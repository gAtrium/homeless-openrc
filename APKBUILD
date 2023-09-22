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
sha512sums="
c0fd02f61a98c1269c43b2ed41721085f8b6650a394a977ef4030da0cba74a8641bf9fe5361020b337cb6bc0bcba21069fe1ac037a38876a636d79da783f0e4b  homeless
"
