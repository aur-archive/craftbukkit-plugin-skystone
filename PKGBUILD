pkgname=craftbukkit-plugin-skystone
pkgver=3.2
pkgrel=2
pkgdesc="WGEN plugin that completely replaces the standard Minecraft terrain with Sky Islands"
arch=(any)
url="http://dev.bukkit.org/bukkit-plugins/skystone"
license=("Public Domain")
source=("http://dev.bukkit.org/media/files/789/91/SkyStone.jar")
noextract=("SkyStone.jar")
depends=("craftbukkit>=1.7.4")
md5sums=('6bd45cc6f3cecc3e4b2001effd94d793')

package() {
	install -Dm644 -g craftbukkit -o craftbukkit "$srcdir/SkyStone.jar" "$pkgdir/srv/craftbukkit/plugins/SkyStone.jar"
}

# vim:set ts=2 sw=2 et:


