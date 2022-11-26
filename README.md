# Jarkom-Modul-3-B13-2022

### Kelompok B13
| **No** | **Nama** | **NRP** | 
| ------------- | ------------- | --------- |
| 1 | Amsal Herbert  | 5025201182 | 
| 2 | Elbert Dicky Aristyo | 5025201231 |
| 3 | Nathanael Roviery | 5025201258 |


## VLSM CPT

### Subnetting
- Pembagian Subnet 
![subnet](https://cdn.discordapp.com/attachments/818146232689098802/1045970435273134100/vlsm-subnet.png)

- Pohon IP
![tree](https://cdn.discordapp.com/attachments/818146232689098802/1045969460001001552/vlsm-tree.png)

  Berdasarkan perhitungan diatas maka diperoleh hasil pembagian IP sebagai berikut

  | **Subnet** | 	**Jumlah IP** |	**Netmask** |
  | ------------- | ------------- | --------- |
  | A1 | 1001 |	/22
  | A2 | 2 | /26
  | A3 | 51	| /26
  | A4 | 2 | /25
  | A5 | 2 | /25
  | A6 | 2 | /25
  | A7 | 271 | /23
  | A8 | 2 | /25
  | A9 | 251 | /24
  | A10 | 2 | /25
  | A11 | 121	| /25
  | A12 | 2	| /25
  | A13 | 501	| /23
  | A14 | 212	| /24
  | A15 | 121	| /25
  | A18 | 71 | /25
  | **Total** |	**2618** | **/20**

  ![pembagian_ip](https://cdn.discordapp.com/attachments/818146232689098802/1046012472726917211/image.png)

### Routing
- The Resonance
  ```
  Network 192.179.4.64 Netmask 255.255.255.192 Next Hop 192.179.3.130
  Network 192.179.4.0 Netmask 255.255.255.192 Next Hop 192.179.3.130
  Network 192.179.12.0 Netmask 255.255.252.0 Next Hop 192.179.3.130
  Network 192.179.2.0 Netmask 255.255.255.128 Next Hop 192.179.3.130
  Network 192.179.8.0 Netmask 255.255.255.0 Next Hop 192.179.3.130
  Network 192.179.5.128 Netmask 255.255.255.128 Next Hop 192.179.1.130
  Network 192.179.1.0 Netmask 255.255.255.128 Next Hop 192.179.1.130
  Network 192.179.10.0 Netmask 255.255.254.0 Next Hop 192.179.1.130
  Network 192.179.9.0 Netmask 255.255.255.0 Next Hop 192.179.1.130
  Network 192.179.0.128 Netmask 255.255.255.128 Next Hop 192.179.1.130
  Network 192.179.0.0 Netmask 255.255.255.128 Next Hop 192.179.1.130
  Network 192.179.4.128 Netmask 255.255.255.128 Next Hop 192.179.1.130
  Network 192.179.5.0 Netmask 255.255.255.128 Next Hop 192.179.1.130
  Network 192.179.6.0 Netmask 255.255.254.0 Next Hop 192.179.1.130
  ```
- The Order
  ```
  Network 192.179.12.0 Netmask 255.255.252.0 Next Hop 192.179.4.2
  Network 0.0.0.0 Netmask 0.0.0.0 Next Hop 192.179.3.129
  Network 192.179.2.0 Netmask 255.255.255.128 Next Hop 192.179.4.2
  Network 192.179.8.0 Netmask 255.255.255.0 Next Hop 192.179.4.2
  ```
- The Minister
  ```
  Network 0.0.0.0 Netmask 0.0.0.0 Next Hop 192.179.4.1
  Network 192.179.8.0 Netmask 255.255.255.0 Next Hop 192.179.2.2
  ```
- The Dauntless
  ```
  Network 0.0.0.0 Netmask 0.0.0.0 Next Hop 192.179.2.1
  ```
- The Magical
  ```
  Network 0.0.0.0 Netmask 0.0.0.0 Next Hop 192.179.3.1
  ```
- The Instrument
  ```
  Network 0.0.0.0 Netmask 0.0.0.0 Next Hop 192.179.1.129
  Network 192.179.10.0 Netmask 255.255.254.0 Next Hop 192.179.1.2
  Network 192.179.9.0 Netmask 255.255.255.0 Next Hop 192.179.1.2
  Network 192.179.0.128 Netmask 255.255.255.128 Next Hop 192.179.1.2
  Network 192.179.4.128 Netmask 255.255.255.128 Next Hop 192.179.0.2
  Network 192.179.5.0 Netmask 255.255.255.128 Next Hop 192.179.0.2
  ```
- The Firefist
  ```
  Network 0.0.0.0 Netmask 0.0.0.0 Next Hop 192.179.1.1
  Network 192.179.0.128 Netmask 255.255.255.128 Next Hop 192.179.9.3
  ```
- The Queen
  ```
  Network 0.0.0.0 Netmask 0.0.0.0 Next Hop 192.179.9.1
  ```
- The Profound
  ```
  Network 0.0.0.0 Netmask 0.0.0.0 Next Hop 192.179.0.1
  ```
  
  ## CIDR GNS3

### Subnetting
- Pembagian Subnet 
![subnet](https://cdn.discordapp.com/attachments/1046045273337647134/1046045351049711676/praktikum-jarkom-modul4-Subnet-CIDR.drawio.png)

- Pohon IP
![tree](https://cdn.discordapp.com/attachments/1046045273337647134/1046045351368466522/praktikum-jarkom-modul4-Tree-CIDR.drawio.png)

- Pembagian IP
 ![pembagian_ip](https://cdn.discordapp.com/attachments/1046045273337647134/1046045299593969755/image.png)
