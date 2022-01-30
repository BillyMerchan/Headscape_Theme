## :octocat: Heya, welcome to my config files! :bowtie:
This is my **personal configuration** for the Xorg display server and the bspwm window manager, along with a few miscellaneous apps.

Spec Overview...

- **Display Server** - [Xorg](https://www.x.org/wiki/) :heavy_multiplication_x: The X server!
- **Window Manager** - [bspwm](https://github.com/baskerville/bspwm) :fallen_leaf: sxhkd and scripts!
- **Shell** - [zsh](https://www.zsh.org/) :shell: using the [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) framework!
- **Terminal** - [URxvt](http://software.schmorp.de/pkg/rxvt-unicode.html) :computer: Lightweight unicode support!
- **Notification Daemon** - [Dunst](https://dunst-project.org/) :alarm_clock: Customizable minimalism.
- **Application Launcher** - [rofi](https://github.com/davatorium/rofi) :small_airplane: Custom super speed!
- **Compositor** - [picom](https://github.com/yshui/picom) :ice_cube: Cool fades and corners and jazz.
- **File Manager** - [thunar](https://github.com/xfce-mirror/thunar) :candy: Intuitive customization with pretty good speeds.
- **Text Editor** - [Spacemacs](https://www.spacemacs.org/) :space_invader: VIM AND EMACS!!
 
## :card_index_dividers: Changelogs
 <details>
  <summary><strong>v0.1</strong></summary>
 - <strong>Major changes:</strong>
      - Updated README with all of the pre-reqs
 </details>
 
## :robot: Installation Guide
### Installing the Dependencies
> Pick and choose the dependencies based on how strictly you're going to adhere to the install guide. This is my usualy first setup when I boot up a fresh Arch install. Other applications that I bundle together with my initial install but are not neccessarily core dependencies are listed after this section.

> **In-depth environment specs**
> See [wiki](wiki/In-Depth-Environment-Configuration)

<details>
 <summary><strong>Arch linux (and all Arch-based distros)</strong></summary>
 
>Ensure that you're using either the *Yay* or *Paru* AUR helper
 
 ```
     yay -S python pmisc xorg-server xorg-xrandr xorg-xprop xorg-xwininfo imagemagick \
     ffmpeg wireles_tools bspwm pulseaudio pulseaudio-alsa alsa-utils brightnessctl \
     nitrogen dunst rxvt-unicode-truecolor-wide-glyphs xclip flameshot mpd mpc thunar \
     thunar-archive-plugin thunar-volman ffmpegthumbnailer tumbler chromium w3m viewnoir \
     mpv pavucontrol parcellite gsimplecal neofetch htop xsettingsd picom-git perl-gtk3 \
     rofi rsync zsh-theme-powerlevel10k-git
 ```

</details>
 
 <details>
 <summary>Oh-my-zsh and plugins</summary>
 
 ```
 sudo pacman -S zsh && chsh -s $(command -v zsh)
 sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
 git clone --depth 1 https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
 git clone --depth 1 https://github.com/zsh-users/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
 git clone --depth 1 https://github.com/zsh-users/zsh-completions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-completions
 ```
 
 </details>
 
 <details>
 <summary> Optional Programs </summary>
 
 ` gimp ` `firefox` ` lightcord`
 
 </details>
