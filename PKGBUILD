# Maintainer: Michael Hübner <superschneider [at] t-online [dot] de>

pkgname=blender-addon-lightfield-analysis-git
pkgver=git.a6c7319e429849e13d377e2c4018771a89fb3a05
pkgrel=1
pkgdesc="Lightfield analysis Blender addon"
arch=('x86_64')
url='https://github.com/lightfield-analysis/blender-addon'
license=('Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License')
makedepends=()
depends=('blender-2.7' 'python')
source=('git+https://github.com/lightfield-analysis/blender-addon')
sha256sums=('SKIP')
provides=(lightfield-analysis)

package() {	
	mkdir -p ${pkgdir}/usr/share/blender/2.79/scripts/addons/

	mv ${srcdir}/blender-addon/ ${pkgdir}/usr/share/blender/2.79/scripts/addons/
}

