# routeros-security-automation-playbook
Ansible Playbook untuk mengotomatisasi keamanan pada MikroTik RouterOS.

Kebijakan Keamanan Mikrotik RouterOS yang diotomatisasi menggunakan Ansible Playbook
pada setiap Router adalah sebagai berikut:
1. Menonaktifkan RouterOS MAC-Access.
2. Menonaktifkan Neighbor Discovery.
3. Menonaktifkan BTest Server.
4. Menonaktifkan DNS Cache.
5. Menonaktifkan Client Services.
6. Mengaktifkan Strong Crypto SSH.
7. Menonaktifkan Interface Router untuk ether4 dan ether5.
8. Mengaktifkan RouterOS Auto-Upgrade menggunakan system scheduler agar terjadwal untuk beroperasi setiap hari pada jam 01:00:00.
9. Menonaktifkan IP Service api, api-ssl, ftp, telnet, www dan www-ssl.
10. Membatasi akses pada IP Service Winbox dan SSH agar hanya dapat diakses dari alamat IP tertentu, sebagai contoh 192.168.169.253 dan 192.168.169.254.
