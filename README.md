# opsi-tightvnc-remote-management

0) Change password on your own in $this_repo\var\lib\opsi\config.ini and $this_repo\CLIENT_DATA\setup.opsiscript, right now it dfbsdSDVsd435534sfdvdsfb
1) Install tightvnc viewer on admin mashine
2) add files from OPSI and CLIENT_DATA folders to destination opsi-workbench
3) create opsi-packet "tightvnc" by command opsi-makeproductfile
4) install opsi-packet by command opsi-package-manager -i vnc.opsi
5) install vnc to managed computers by opsi config editor
6) add content file $this_repo\var\lib\opsi\config.ini to \var\lib\opsi\config.ini on opsi-depot server in needet section
7) right click on client name in opsi config editor and select "remote management" and use "vnc_windows" for management
