# opsi-tightvnc-remote-management

1) Install tightvnc on admin mashine
2) add files from OPSI and CLIENT_DATA folders to destination opsi-workbench
3) create opsi-packet "tightvnc" by command opsi-makeproductfile
4) install opsi-packet by command opsi-package-manager -i readoffice_1.0-3.opsi
5) install readoffice_1.0-3 to managed computers by opsi config editor
6) add content file $this_repo\var\lib\opsi\config.ini to \var\lib\opsi\config.ini on opsi-depot server
7) right click on client name in opsi config editor and select "remote management" and use "vnc_windows" for management
