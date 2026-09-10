# you should do this before trying to boot -
# update all sys packages
# install this - pipewire pipewire-pulse wireplumber waybar mako dbus yad jq python-gobject slurp grim wl-clipboard curl wofi kitty gtk-layer-shell
# build this - swayfx wpaperd

# after booting:
# set pipewire to autostart via ur init manager
# set pipewire-pulse to autostart via ur init manager
# set wireplumber to autostart via ur init manager
# set mako to autostart via ur init manager
# !!! better not to add anything else because it autostarts, sets env and etc. in ~/.config/xeheme_autostart !!!

# arch version -
# you should do this before trying to boot -
# sudo pacman -Syu
# sudo pacman -S pipewire pipewire-pulse wireplumber waybar mako dbus yad jq python-gobject slurp grim wl-clipboard curl wofi kitty gtk-layer-shell
# paru -S swayfx
# paru -S wpaperd

# after booting (for openrc):
# rc-update -U add pipewire default
# rc-update -U add pipewire-pulse default
# rc-update -U add wireplumber default
# rc-update -U add mako default

# --- DO IT ON A CLEAN SYSTEM (artix is the most supported) ONLY

# --- YOU WILL HAVE SOME ISSUES WITH BUILDING SWAYFX AND WPAPERD --- #

# --- IF YOU WILL CHANGE WALLPAPER THEN EXPECT FOR COLOR DIFFERENCE, FIX IT BY CHANGING THE CONFIGS COLORS ITSELF --- #

# --- NOTE THAT THIS WAS MADE FOR NEWBIES AND I MOSTLY MADE IT TO SPREAD IT ACROSS MY DEVICES WITH LINUX --- #

#!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!#
# BETTER NOT TO ADD ANYTHING ELSE BECAUSE IT AUTOSTARTS, SETS ENV AND ETC. IN ~/.CONFIG/XEHEME_AUTOSTART #
#!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!#
