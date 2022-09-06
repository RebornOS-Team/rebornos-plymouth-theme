# Maintainer: Panda <panda@rebornos.org>

pkgname=rebornos-plymouth-theme
pkgver=1.0.0
pkgrel=1
pkgdesc='RebornOS plymouth theme '
arch=('any')
url='https://github.com/RebornOS-Developers/rebornos-plymouth-theme'
license=('GPL3')
depends=('plymouth')
install="${pkgname}.install"
source=(
  'bullet.png'
  'entry.png'
  'logo.png'
  'reborn.plymouth'
  'script'
  'spinner.png')

sha256sums=('efc4c1e327bb30a4c29b2e27316f13b080c7887acf5d6b32569611222f735474'
            'c28a4665da4b56cc667ff6ec68e2af289f40767cf41b3f2f75c26609c1c3f162'
            'ce560aeb2842ccc1b915818d8fdd360f7f05410ce63c75a844616bf026cb84b2'
            '29a786b2a7dd4f6a6412e2356b35adb866de4cab3cda4e2345f9fc43db768f75'
            '61445616ab6c73a9dee8dffdcfce7a01debbf6530be685859b41d229412128e9'
            'e7dee248d77ea92db4fbc39c2b73a99caa982cff5fd5c00472db98efb0726259')

package() {
  cd "${srcdir}"

  install -d "${pkgdir}/usr/share/plymouth/themes/reborn"
  install -Dm 644 * "${pkgdir}/usr/share/plymouth/themes/reborn"
}