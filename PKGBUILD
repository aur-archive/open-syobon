# Maintainer : AlexanderR <alexander r at gmx com>
# Contributor : Zhang Li <richselian at gmail.com>
pkgname=open-syobon
pkgver=1.0.2
pkgrel=1
pkgdesc='A cross platform, open source version of the unforgiving Japanese parody of Super Mario Bros.'
arch=('i686' 'x86_64')
url='https://github.com/Alexander--/open-syobon'
# http://zapek.com/?p=189
# http://sourceforge.net/projects/opensyobon/
license=('unknown')
depends=('sdl_image' 'sdl_gfx' 'sdl_mixer' 'sdl_ttf' 'gcc-libs' 'fontconfig' 'ttf-sazanami')
changelog=ChangeLog
source=("$pkgname-$pkgver.tar.gz::https://github.com/Alexander--/$pkgname/tarball/$pkgver")
md5sums=('baa94dd11becbd0dbdf9ef93643bdd24')

build() {
  cd "$srcdir/Alexander---$pkgname-a6d223b"

  make
}

package() {
  cd "$srcdir/Alexander---$pkgname-a6d223b"

  DESTDIR="$pkgdir" make install
}

# vim:set ts=2 sw=2 et:
