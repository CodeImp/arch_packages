# arch_packages
Arch Linux PKGBUILD for Veeam Agent for Linux

# How to use


wget https://github.com/CodeImp/arch_packages/archive/master.zip</br>
unzip ./master.zip</br>
</br>
cd ~/arch_packages-master/veeamsnap/</br>
updpkgsums</br>
makepkg</br>
sudo pacman -U ./veeamsnap-1.0.0.944-1-x86_64.pkg.tar.xz</br>
</br>
cd ~/arch_packages-master/veeam/</br>
updpkgsums</br>
makepkg</br>
sudo pacman -U ./veeam-1.0.0.944-1-x86_64.pkg.tar.xz</br>
</br>
sudo veeam</br>
