pkgname='vswsl'
pkgver='0.0.0'
pkgrel='1'
pkgdesc='Visual Studio commands in WSL'
arch=('any')
url='https://github.com/harenayo/vswsl'
license=('MIT')
depends=('nushell')
source=('LICENSE.txt' 'vslink')
sha256sums=('913bb56ae47400e91e0e62e32659b42af99574eb30826e12ed38ebbd1775d4d4' '1779a1a108ff03d430a8fb037c345e88086c494151376f20c32e2f1eb11f0dca')

package () {
    install -D -m 644 LICENSE.txt "$pkgdir/usr/share/licenses/$pkgname/MIT.txt"
    install -D -m 755 vslink "$pkgdir/usr/bin/vslink"
}