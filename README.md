# enigmarch
my personal archlinux repo

simply add these lines in /etc/pacman.conf
------------------------------------------
[enigmarch]
# SigLevel = Never for disable any sig check
# SigLevel = TrustAll for debug purpose only, prefer TrustedOnly for official repos
# SigLevel = PackageRequired
# SigLevel = Required DatabaseOptional
SigLevel = Never
# SigLevel = TrustAll 
# Server = https://github.com/enigma158an201/$repo/$arch
# Server = https://github.com/enigma158an201/enigmarch/blob/main/
# Server = https://raw.githubusercontent.com/enigma158an201/enigmarch/main/
# Server = https://raw.githubusercontent.com/enigma158an201/$repo/main/$arch
Server = https://raw.githubusercontent.com/enigma158an201/$repo/main/any
------------------------------------------

