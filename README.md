# clashmaster-v1

## cara pakai

- atur interface modem1 di config clashmaster-v1.yaml
  pada file luar, folder backup, dan folder config
  untuk mengatur nya ada pada bagian interface-name: eth1

- atur interface modem2 di config clashmaster-v1.yaml
  pada file luar, folder backup, dan folder config
  untuk mengatur nya ada pada bagian interface-name: eth2

- eth1 dan eth2 bisa anda ganti dengan physical interface yang anda gunakan.

- setting interface masing-masing pada bagian proxy-groups:

  MASTER-GAME
  MASTER-SOSMED
  MASTER-STREAM
  MASTER-OLSHOP
  MASTER-BANK
  MASTER-WHATSAPP

- untuk config ini jika anda gunakan mode meta maka anda wajib hapus script ini di config


script:
  shortcuts:
  
  hapus yang di bawah ini saja
  
    umum_port: dst_port not in [21, 22, 23, 53, 80, 123, 143, 194, 443, 465, 587, 853, 993, 995, 998, 2052, 2053, 2082, 2083, 2086, 2095, 2096, 5222, 5228, 5229, 5230, 8080, 8443, 8880, 8888, 8889]


rules:
  ingat yang bawah ini juga di hapus ya...
- SCRIPT,umum_port,CLASHMASTER-V1
  
  semua file config di luar, folder config, dan folder backup di samakan saja.
  dan jika sudah wajib masuk beranda utama openclash dan tekan SWITCH CONFIG untuk memulai openclash bersama   clash mwms

- untuk menambah rule anda sendiri di folder rule_provider
  anda bisa mengikuti rule yang sudah saya setting seperti berikut:

  - "+.domain.com"

- untuk config ini gratis

- untuk full versi, anda bisa menghubungi saya yang sudah tertera di https://www.clashmwns.com

- subscribe channel youtube https://www.youtube.com/@mwnsofficial

- ikuti blog saya hanya di https://www.clashmwns.com dan juga https://mwns.my.id

- jika ada ingin donasi, anda bisa masuk bagian layanan clashmwns di blog https://www.clashmwns.com

- terima kasih sudah menggunakan config saya dan kesetiaan nya anda bersama saya.
