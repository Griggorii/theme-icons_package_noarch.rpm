# theme-icons_package_noarch.rpm
theme , icons , fedora , migration wayland obs , oomox-griggorii-theme-icon , Orchis-theme , Pop-dark-oomox-griggorii_theme , Tela-theme-icon , dracut , zstd 

Proview theme+icons example theme: https://youtu.be/BNrL1aVWM9Y

Package them RPM download: https://github.com/Griggorii/theme-icons_package_noarch.rpm/releases/tag/fedora_theme-icons install one locate all rpm command:

$ sudo rpm -i ./Orchis-theme_2021-21.04.1-2.noarch.rpm ./oomox-griggorii-theme-icon-21.04.1-2.noarch.rpm ./Pop-dark-oomox-griggorii_theme_2020-21.04.1-2.noarch.rpm 

$ sudo dnf install gnome-shell-extension-user-theme gnome-tweaks

$ chmod -R a+rwx Fedora_nautilus_dconf_linux_OS34_V46.0_By_Griggorii_Wayland_adaptation.sh

$ ./Fedora_nautilus_dconf_linux_OS34_V46.0_By_Griggorii_Wayland_adaptation.sh

terminal ignore sudo ctrl+c ctrl+c ctrl+c $ ./Replace_nemo-to-nautilus_dconf_linux_OS21.04_V46.0_By_Griggorii_Wayland_adaptation.sh

Uninstall theam icons example command terminal:

$ sudo dnf remove Orchis-theme_2021-21.04.1-2.noarch oomox-griggorii-theme-icon-21.04.1-2.noarch Pop-dark-oomox-griggorii_theme_2020-21.04.1-2.noarch Tela-theme-icon-21.04.1-2.noarch

Example "Theme_name_modification_and_default" - "Orchis" "Orchis-dark" "Orchis-dark-compact" 

$ gsettings set org.gnome.desktop.interface gtk-theme "Orchis-dark"

$ gsettings set org.gnome.desktop.wm.preferences theme "Orchis-dark"

$ gsettings set org.gnome.shell.extensions.user-theme name "Orchis"

Support donation message Griggorii@gmail.com real tehnology



