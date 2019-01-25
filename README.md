# WARNING
Packages moved to AUR and will not be more supported here.</br>
New place here:</br>
https://aur.archlinux.org/packages/veeamsnap/ </br>
https://aur.archlinux.org/packages/veeam/ </br>
# arch_packages
Arch Linux PKGBUILD for Veeam Agent for Linux</br>
Version: 3.0.0.865</br>
Testet on:
  - kernel 4.20.0-arch1-1-ARCH
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
