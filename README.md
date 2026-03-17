  aspell* aspell-en* dictionaries-common* emacs* emacs-bin-common* emacs-common* emacs-el* emacs-gtk* emacsen-common* enchant-2*
  evince* evolution-data-server* gdm3* gir1.2-webkit-6.0* gir1.2-webkit2-4.1* gnome-calendar* gnome-initial-setup* gnome-shell*
  gnome-shell-extension-appindicator* gnome-shell-extension-desktop-icons-ng* gnome-shell-extension-ubuntu-dock*
  gnome-shell-extension-ubuntu-tiling-assistant* gnome-text-editor* gnome-user-docs* hunspell-en-au* hunspell-en-ca* hunspell-en-gb*
  hunspell-en-us* hunspell-en-za* hunspell-fr-classical* hyphen-en-ca* hyphen-en-gb* hyphen-en-us* libedataserverui-1.2-4t64*
  libedataserverui4-1.0-0t64* libenchant-2-2* libevview3-3t64* libgspell-1-2* libwebkit2gtk-4.1-0* libwebkitgtk-6.0-4* libyelp0*
  mythes-en-au* mythes-en-us* ubuntu-desktop* ubuntu-desktop-minimal* ubuntu-docs* ubuntu-release-upgrader-gtk* ubuntu-session*
  update-manager* update-notifier* wbritish* yelp*


#the error i am getting after typing sudo systemctl status gdm3


sudo systemctl status gdm3
● gdm.service - GNOME Display Manager
     Loaded: loaded (/usr/lib/systemd/system/gdm.service; static)
     Active: active (running) since Tue 2026-03-17 18:00:15 IST; 4min 9s ago
    Process: 23720 ExecStartPre=/usr/share/gdm/generate-config (code=exited, status=0/SUCCESS)
   Main PID: 23726 (gdm3)
      Tasks: 4 (limit: 4407)
     Memory: 3.2M (peak: 21.4M)
        CPU: 268ms
     CGroup: /system.slice/gdm.service
             └─23726 /usr/sbin/gdm3

Mar 17 18:00:44 sourav-HP-Notebook gdm-password][24388]: pam_unix(gdm-password:session): session opened for user sourav(uid=1000) by s>
Mar 17 18:00:44 sourav-HP-Notebook gdm-password][24388]: gkr-pam: unlocked login keyring
Mar 17 18:00:59 sourav-HP-Notebook gdm3[23726]: Gdm: Couldn't find session for user
Mar 17 18:01:29 sourav-HP-Notebook gdm3[23726]: Gdm: Couldn't find session for user
Mar 17 18:01:29 sourav-HP-Notebook gdm3[23726]: Gdm: Couldn't find session for user
Mar 17 18:01:29 sourav-HP-Notebook gdm3[23726]: Gdm: Couldn't find session for user
Mar 17 18:01:38 sourav-HP-Notebook gdm-password][24483]: gkr-pam: unable to locate daemon control file
Mar 17 18:01:38 sourav-HP-Notebook gdm-password][24483]: gkr-pam: stashed password to try later in open session
Mar 17 18:01:38 sourav-HP-Notebook gdm-password][24483]: pam_unix(gdm-password:session): session opened for user sourav(uid=1000) by s>
Mar 17 18:01:38 sourav-HP-Notebook gdm-password][24483]: gkr-pam: unlocked login keyring
