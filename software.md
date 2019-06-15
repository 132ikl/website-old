---
layout: page
title: '~/software/'
sidebar_link: true
sidebar_sort_order: 1
---

<sup>(last updated: {{ page.last_modified_at | date: '%Y-%m-%d' }})</sup>
<style>.content p {margin-bottom: .25em;}
.content li > ul {font-size: .75em;}
.content ul {margin-bottom: 0em;}
</style>

Here, you can find software hosted on this server and other software I use on a daily basis. Most software here is free, open source software, except where noted. I like more minimalist software, but I end up chosing whatever both aligns with my beliefs and works best for me.

Feel free to use any software on hosted on this server, but it may disappear without warning. 

## Server
* Operating System: [CentOS](https://centos.org)
    * RedHat-based distro, standard affair for servers. I chose CentOS over Debian because I prefer really anything over apt, and I like the extra security SELinux and firewalld provide. It's a bit more work, but I think it's fun to set everything up.
* Web server: [nginx](https://nginx.org)
    * Easy to set up, lots of plugins, and more sane syntax than apache. I don't really have a strong opinion here, but I've never had a problem with nginx. 

Software hosted on this server:
* Link shortener: [liteshort](https://ls.ikl.sh/), [source](https://github.com/132ikl/liteshort/)
    * My link shortener! A lightweight, configurable, "set it and forget it" link shortener. 
* Password Manager: [bitwarden_rs](https://bw.ikl.sh/), [source](https://github.com/dani-garcia/bitwarden_rs)
    * Bitwarden-compatible server without the resource overhead of the vendor provided Docker image.
* File Server: [linx](https://fs.ikl.sh), [source](https://github.com/andreimarcu/linx-server/)
    * Easy file server with a good API. Simple enough for friends to use. Written in Go, so you don't have to deal with Docker or Python nonsense.
* Email Server: docker-mailserver, [source](https://github.com/tomav/docker-mailserver)
    * Easy mail server which just saves the time of messing with postfix/dovecot. Uses docker-compose version and has sane configuration.
* Twitch Proxy: [ikltwitch](https://twitch.ikl.sh)
    * It's a stupidly simple twitch proxy. Absolutely proprietary software. Code is very ugly, working on fixing it up before release it.

## Desktop
* Operating System: [Arch Linux](https://archlinux.org)
    * Minimal, doesn't get in the way, and allows the user full control over everything without being overly inconvenient. The "just works" of Linux distros.
* Terminal: [st](https://st.suckless.org/)
    * Still working on putting together my build, but simple to the core. Still, suprisingly powerful out of the box.
* Window Manager: [i3-gaps](https://github.com/Airblader/i3)
    * Highly functional, vim-like bindings make navigating windows and workspaces easy. Using gaps because it [looks nice](/media/looks-nice.png).
* Status bar: [i3bar](https://github.com/i3/i3) + [i3blocks](https://github.com/vivien/i3blocks)
    * Simplicity of i3bar with the flexibility of any shell script and signal-based updating.
* Text editing/programming: [neovim](https://github.com/neovim/neovim)
    * More of a learning wall than curve, but extremely powerful. Still working on getting the perfect config and plugins for programming, but for text editing nothing beats it.
* Web Browser: [qutebrowser](https://github.com/qutebrowser/qutebrowser/)
    * My most difficult software decision. Powerful like vim and beats any vim browser plugin. Unfortunately, it only supports a Chromium-based web-engine. There are currently no plugins, and sometimes I miss AdNauseum, Privacy Badger, and many others.
* Dotfiles: [My dotfiles](https://github.com/132ikl/dotfiles) 
    * All my configs in an organized manner. Uses [yadm](https://github.com/TheLocehiliosan/yadm), because symlinks are a pain.


## Mobile
* Operating System: [Samsung's Android](https://android.com)
    * Unfortunately, I cannot root my phone. If I had a choice, I would use LineageOS.
* Launcher: [t-ui](https://github.com/fAndreuzzi/TUI-ConsoleLauncher)
    * A launcher built on [Termux](https://termux.com). May seem a bit over the top, but you assign apps to aliases. This allows you to set any app to any key. For example, `ff` is Firefox, `s` is SMS client, etc. Really fast once you know your keybinds. I get a lot of confused comments about this one, but it's definitely worth it.  
* SMS: [QKSMS](https://github.com/moezbhatti/qksms)
    * Simple and pretty SMS client that is arguably better than the stock SMS client, excluding Google's messages for web.    
* Application Manager: [F-Droid](https://f-droid.org)
    * Unequivically the best app store on Android. All open source software, and all apps are vetted by the fantastic F-Droid team. You can't go wrong here.
* Web Browser: [Firefox](https://www.mozilla.org/en-US/firefox/mobile/)
    * Not the most reliable browser, but is just like every mobile browser. At the very least, it helps the market share of the Gecko web engine.
* Keyboard: [Simple Keyboard](https://github.com/rkkr/simple-keyboard)
    * Says it right on the tin. It's a keyboard, and nothing else. It's almost identical to GBoard, minus autocompletion, autocorrect, and slide typing. It does require two fingers, but after getting used to typing accurately all the time you'll never want to go back.
* Music Player: [Vanilla Music](https://github.com/vanilla-music/vanilla)
    * Fully functional music player with an intuitive UI and tons of useful quality of life features. Could be considerd a bit "bloaty", but still retains a relatively small footprint.
