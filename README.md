# arch_packages
Arch Linux PKGBUILD for Veeam Agent for Linux
Version: 3.0.0.865
Testet on:
  - kernel 4.19.12-arch1-1-ARCH
  - gcc 8.2.1
# How to use


wget https://github.com/CodeImp/arch_packages/archive/master.zip</br>
unzip ./master.zip</br>
</br>
cd ~/arch_packages-master/veeamsnap/</br>
updpkgsums</br>
makepkg</br>
sudo pacman -U ./veeamsnap-3.0.0.865-1-x86_64.pkg.tar.xz</br>
</br>
cd ~/arch_packages-master/veeam/</br>
updpkgsums</br>
makepkg</br>
sudo pacman -U ./veeam-3.0.0.865-1-x86_64.pkg.tar.xz</br>
</br>
sudo veeam</br>
