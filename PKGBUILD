# Maintainer: Peijun Zhu <zpj.ustc@gmail.com>

pkgname=ttf-kpp-font
pkgver=1.0
pkgrel=1
pkgdesc="Kingsoft Phonetic Plain Font"
arch=('any')
license=('custom')
url="https://www.kingsoft.com/"
depends=()
source=("kpp.ttf")
sha256sums=('43daaadcdc0d4518714fbd06040784050b5289f600452c1d7093a8e361dc8e3e')

package() {
	msg 'Copying kpp fonts...'
	install -dm755 ${pkgdir}/usr/share/fonts/TTF
	install -Dm644 kpp.ttf ${pkgdir}/usr/share/fonts/TTF/
}
