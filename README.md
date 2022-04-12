# bpc_sos

## List of used commands (not necessarily in order)

```
dnf -y remove git
dnf -y remove gcc
dnf -y install http://li.nux.ro/download/nux/dextop/el7/x86_64/otter-browser-0.9.09-0.2.beta9gitff0bb28.el7.nux.x86_64.rpm
dnf -y install http://download-ib01.fedoraproject.org/pub/epel/7/x86_64/Packages/x/xpdf-3.04-10.el7.x86_64.rpm
dnf -y remove firefox
rpm -e --nodeps acl audit authselect chrony cpio cracklib-dicts cronie device-mapper-event diffutils dnf-plugins-core e2fsprogs epel-release findutils gettext groff-base hostname iproute iputils irqbalance kbd less libnfnetlink logrotate lshw lsscsi openssl parted passwd pciutils-libs prefixdevname procps-ng selinux-policy sg3_utils sg3_utils-libs teamd fsprogs
dnf remove slang.x86_64
dnf remove libexif.x86_64
dnf remove cpp.x86_64
dnf remove gtk3.x86_64
dnf remove rsyslog.x86_64
dnf remove brotli.x86_64
dnf remove sssd-client.x86_64
dnf remove openssh.x86_64
dnf remove initscripts-rename-device.x86_64
vi .bash_profile
if systemctl -q is-active graphical.target && [[ ! $DISPLAY && $XDG_VTNR -eq 1 ]]; then
               exec startx
fi"
"vi .bashrc
if [ -f /etc/bashrc ]; then
          . /etc/bashrc;
fi
dnf remove mesa-dri-drivers
rpm -e --nodeps dejavu-sans-fonts
rpm -e --nodeps avahi-libs.x86_64
rpm -e --nodeps gstreamer1-plugins-bad-free
rpm -e --nodeps cracklib.x86_64
rpm -e --nodeps cracklib-dicts.x86_64
rpm -e --nodeps iso-codes.no_arch
rpm -e --nodeps alternatives.x86_64
rpm -e --nodeps cups-libs.x86_64
rpm -e --nodeps fdk-aac-free.x86_64
rpm -e --nodeps fribidi.x86_64
rpm -e --nodeps gawk.x86_64
rpm -e --nodeps openal-soft.x86_64
rpm -e --nodeps openjpeg2.x86_64
rpm -e --nodeps soundtouch.x86_64
rpm -e --nodeps webrtc-audio-processing.x86_64
rpm -e --nodeps os-prober.x86_64
rpm -e --nodeps which.x86_64
rpm -e --nodeps lcms2.x86_64
rpm -e --nodeps glx-utils.x86_64
rpm -e --nodeps graphene.x86_64
rpm -e --nodeps hunspell.x86_64
rpm -e --nodeps hunspell-en-US.noarch
rpm -e --nodeps hunspell-filesystem.x86_64"
rpm -e --nodeps gettext-libs.x86_64
rpm -e --nodeps gettext.x86_64
rpm --rebuilddb
dnf clean all
rm -rf .cache/
rm -rf .mozzila/
rm -rf /home/student/.config/google-chrome/
rm -rf /usr/share/doc
rm -rf /usr/share/man
rm -rf /usr/share/info
rm -rf /var/log/*
rm rf /var/cache/*
```
