# hyprconf
Waybar ve Hyprland config dosyalarım sizinle :D

> Masaüstünden Görüntüler

<img width="1366" height="768" alt="20250726_15h57m50s_grim" src="https://github.com/user-attachments/assets/b2772d9f-6f73-420c-ace1-a82e75a533b5" />

<img width="1366" height="768" alt="20250726_15h58m19s_grim" src="https://github.com/user-attachments/assets/a798ed36-6f5b-4af3-8398-cb4a0c1e1537" />

<img width="1366" height="768" alt="20250726_15h59m44s_grim" src="https://github.com/user-attachments/assets/def826a0-2e19-48a7-a7fd-d4b75968c216" />

# Neleri İndirmelisinz?

> Kesin İndirilmesi Gerekenler

`kitty` `dolphin` `hyprpaper` `nerd-fonts` `wofi` `firefox` `hyprpaper`

> Opsiyonel(İsterseniz İndirebilirsiniz)

`google-chrome`

# Kısayollar!

`SUPER+M` Oturumu(Hyprland) Kapat

`SUPER+D` Dolphin

`SUPER+1-2-3` Sanal Masaüstü Değiştirme

`SUPER+G` Google Chrome

`SUPER+F` Firefox

`SUPER+R` Wofi

`SUPER+Sol Tık` Pencere Konumlandırma  \
>                                       ---> Bu iki  kısayol için pencere yüzen modda olmalı.
`SUPER+Sağ Tık` Pencere Boyutlandırma  /

`SUPER+V` Seçili Pencereyi Yüzme Moduna Alma

`SUPER+T` Kitty-Terminal

# İndirme Süreci
- 1-İndirmediyseniz Bağlılıkları İndirin

Arch Linux:
```bash
yay -S git kitty hyprpaper wofi nerd-fonts dolphin firefox hyprpaper`
```
Debian:
```bash
sudo apt update && sudo apt install -y git kitty dolphin firefox wofi fonts-noto-color-emoji
```
Fedora:
```bash
sudo dnf install -y git kitty dolphin firefox wofi fira-code-fonts
sudo dnf copr enable solopasha/hyprland
sudo dnf install hyprland hyprpaper
sudo dnf copr enable dawid/better_fonts
sudo dnf install nerd-fonts
```
- 2-Dosyaları Sisteme Kopyalayın

  `git clone https://github.com/hasofxs/hyprconf.git`

- 3-`hyprconf` dosyasının içindeki `.zip` dosyasını çıkartın.

- 4-`hypr` ve `waybar` klasörlerini `.config` dosyasına sürükleyin.

- 5-Hyprland'i, waybar'ı ve hyprpaper'ı kapatıp açın.
```bash
killall hyprland || killall waybar || killall hyprpaper
```
> Veya direk `reboot` ile yeniden başlatın.

# Son- Yapmanız Gerekenler bu Kadardı!
