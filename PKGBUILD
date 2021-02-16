# Maintainer: zhullyb <zhullyb@outlook.com>

pkgname=zhullyb-archlinux-git
pkgver=100.0
pkgrel=1
install=.INSTALL
pkgdesc="zhullyb's Archlinux config file"
arch=('x86_64')
url="https://github.com/zhullyb/zhullyb-archlinux.git"
license=()
depends=(
    dolphin
    kate
    kdialog
    keditbookmarks
    khelpcenter
    konsole
    firefox
    neofetch
    bash-completion
    htop
    networkmanager
    )
makedepends=()
source=("git+https://github.com/zhullyb/zhullyb-archlinux.git")
md5sums=('SKIP')

package() {
    cd $srcdir/zhullyb-archlinux
    mv * $pkgdir
}
