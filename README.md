# Jarkom-Modul-4-IT14-2024

# CPT (VLSM)
## Topologi
![image](https://github.com/user-attachments/assets/18e663ce-1e6f-4d8a-ae35-491a002625d2)


### Tree VLSM
![pohon vlsm drawio](https://github.com/user-attachments/assets/30cf285f-8926-4fbf-ae61-e321768b212f)


### Pembagian IP
![image](https://github.com/user-attachments/assets/caab96d9-a3ad-46c7-9b4b-c73db213496a)


### Subnet A1
### Hololive
```
enable
configure terminal
interface fa1/0
ip address 192.240.19.73 255.255.255.252
no shutdown
```

### Holo-ID
```
enable
configure terminal
interface fa0/0
ip address 192.240.19.74 255.255.255.252
no shutdown
```

### Subnet A2
### Holo-ID
```
enable
configure terminal
interface fa0/1
ip address 192.240.19.93 255.255.255.252
no shutdown
```
### AREA15
```
enable
configure terminal
interface fa0/0
ip address 192.240.19.94 255.255.255.252
no shutdown
```

### Subnet A3
### AREA15
```
enable
configure terminal
interface fa0/1
ip address 192.240.8.1 255.255.252.0
no shutdown
```
### Moona
```
Dekstop IP Configuration
IP Address: 192.240.8.2
Subnet Mask: 255.255.252.0
Gateway: 192.240.8.1
```
### Risu
```
Dekstop IP Configuration
IP Address: 192.240.8.3
Subnet Mask: 255.255.252.0
Gateway: 192.240.8.1
```
### lofi
```
Dekstop IP Configuration
IP Address: 192.240.8.4
Subnet Mask: 255.255.252.0
Gateway: 192.240.8.1
```

### Subnet A4
### Holo-ID
```
enable
configure terminal
interface fa1/0
ip address 192.240.19.97 255.255.255.252
no shutdown
```
### holoro
```
enable
configure terminal
interface fa0/0
ip address 192.240.19.98 255.255.255.252
no shutdown
```

### Subnet A5
### holoro
```
enable
configure terminal
interface fa0/1
ip address 192.240.18.193 255.255.255.192
no shutdown
```
### Ollie
```
Dekstop IP Configuration
IP Address: 192.240.18.194
Subnet Mask: 255.255.255.192
Gateway: 192.240.18.193
```
### Anya
```
Dekstop IP Configuration
IP Address: 192.240.18.195
Subnet Mask: 255.255.255.192
Gateway: 192.240.18.193
```
### Reine
```
Dekstop IP Configuration
IP Address: 192.240.18.196
Subnet Mask: 255.255.255.192
Gateway: 192.240.18.193
```

### Subnet A6
### Holo-ID
```
enable
configure terminal
interface fa1/1
ip address 192.240.19.101 255.255.255.252
no shutdown
```
### holoh3ro
```
enable
configure terminal
interface fa0/0
ip address 192.240.19.102 255.255.255.252
no shutdown
```

### Subnet A7
### holoh3ro
```
enable
configure terminal
interface fa0/1
ip address 192.240.16.1 255.255.254.0
no shutdown
```
### Zeta
```
Dekstop IP Configuration
IP Address: 192.240.16.2
Subnet Mask: 255.255.254.0
Gateway: 192.240.16.1
```
### Kaela 
```
Dekstop IP Configuration
IP Address: 192.240.16.3
Subnet Mask: 255.255.254.0
Gateway: 192.240.16.1
```
### Kobo 
```
Dekstop IP Configuration
IP Address: 192.240.16.4
Subnet Mask: 255.255.254.0
Gateway: 192.240.16.1
```

### Subnet A8
### Hololive
```
enable
configure terminal
interface fa1/1
ip address 192.240.19.105 255.255.255.252
no shutdown
```
### HoloJP
```
enable
configure terminal
interface fa0/1
ip address 192.240.19.106 255.255.255.252
no shutdown
```

### Subnet A9
### HoloJP
```
enable
configure terminal
interface fa0/0
ip address 192.240.19.65 255.255.255.248
no shutdown
```
### DEV_IS
```
enable
configure terminal
interface fa0/0
ip address 192.240.19.66 255.255.255.248
no shutdown
```
### GEN:0 
```
enable
configure terminal
interface fa0/0
ip address 192.240.19.67 255.255.255.248
no shutdown
```

### Subnet A10
### DEV_IS
```
enable
configure terminal
interface fa0/1
ip address 192.240.19.33 255.255.255.240
no shutdown
```
### Ririka_Rade
```
Dekstop IP Configuration
IP Address: 192.240.19.34
Subnet Mask: 255.255.255.240
Gateway: 192.240.19.33
```
### Ao
```
Dekstop IP Configuration
IP Address: 192.240.19.35
Subnet Mask: 255.255.255.240
Gateway: 192.240.19.33
```
### Hajime_Kanade
```
Dekstop IP Configuration
IP Address: 192.240.19.36
Subnet Mask: 255.255.255.240
Gateway: 192.240.19.33
```

### Subnet A11
### GEN:0
```
enable
configure terminal
interface fa0/1
ip address 192.240.0.1 255.255.248.0
no shutdown
```
### GEN:1
```
enable
configure terminal
interface fa0/0
ip address 192.240.0.2 255.255.248.0
no shutdown
```
### MiComet
```
Dekstop IP Configuration
IP Address: 192.240.0.3
Subnet Mask: 255.255.248.0
Gateway: 192.240.0.1
```
### Sora_Robo_AZK 
```
Dekstop IP Configuration
IP Address: 192.240.0.4
Subnet Mask: 255.255.248.0
Gateway: 192.240.0.1
```

### Subnet A12
### GEN:1
```
enable
configure terminal
interface fa0/1
ip address 192.240.14.1 255.255.254.0
no shutdown
```
### FBK_Matsuri
```
Dekstop IP Configuration
IP Address: 192.240.14.2
Subnet Mask: 255.255.254.0
Gateway: 192.240.14.2
```
### Aki_Hachama
```
Dekstop IP Configuration
IP Address: 192.240.14.3
Subnet Mask: 255.255.254.0
Gateway: 192.240.14.2
```

### Subnet A13
### GEN:1
```
enable
configure terminal
interface fa1/0
ip address 192.240.19.77 255.255.255.252
no shutdown
```
### GAMERS
```
enable
configure terminal
interface fa0/0
ip address 192.240.19.78 255.255.255.252
no shutdown
```

### Subnet A14
### GAMERS
```
enable
configure terminal
interface fa0/1
ip address 192.240.18.1 255.255.255.128
no shutdown
```
### Kerone 
```
Dekstop IP Configuration
IP Address: 192.240.18.2
Subnet Mask: 255.255.255.128
Gateway: 192.240.18.1
```
### Okayu
```
Dekstop IP Configuration
IP Address: 192.240.18.3
Subnet Mask: 255.255.255.128
Gateway: 192.240.18.1
```
### Mio
```
Dekstop IP Configuration
IP Address: 192.240.18.4
Subnet Mask: 255.255.255.128
Gateway: 192.240.18.1
```

### Subnet A15
### Hololive
```
enable
configure terminal
interface fa0/1
ip address 192.240.19.81 255.255.255.252
no shutdown
```
### HoloEN
```
enable
configure terminal
interface fa0/0
ip address 192.240.19.82 255.255.255.252
no shutdown
```

### Subnet A16
### Holo-EN
```
enable
configure terminal
interface fa1/0
ip address 192.240.19.85 255.255.255.252
no shutdown
```
### HoloAdvent
```
enable
configure terminal
interface fa0/0
ip address 192.240.19.86 255.255.255.252
no shutdown
```

### Subnet A17
### HoloAdvent
```
enable
configure terminal
interface fa0/1
ip address 192.240.19.1 255.255.255.224
no shutdown
```
### FuwaMoco
```
Dekstop IP Configuration
IP Address: 192.240.19.2
Subnet Mask: 255.255.255.224
Gateway: 192.240.19.1
```
### Shiori_Nerissa
```
Dekstop IP Configuration
IP Address: 192.240.19.3
Subnet Mask: 255.255.255.224
Gateway: 192.240.19.1
```
### Biboo
```
Dekstop IP Configuration
IP Address: 192.240.19.4
Subnet Mask: 255.255.255.224
Gateway: 192.240.19.1
```

### Subnet A18
### Holo-EN
```
enable
configure terminal
interface fa0/1
ip address 192.240.19.89 255.255.255.252
no shutdown
```
### Holo-Myth
```
enable
configure terminal
interface fa0/0
ip address 192.240.19.90 255.255.255.252
no shutdown
```

### Subnet A19
### Holo-Myth
```
enable
configure terminal
interface fa0/1
ip address 192.240.12.1 255.255.254.0
no shutdown
```
### Gura_Ame_Ina
```
Dekstop IP Configuration
IP Address: 192.240.12.2
Subnet Mask: 255.255.254.0
Gateway: 192.240.12.1
```
### Kiara_Calli
```
Dekstop IP Configuration
IP Address: 192.240.12.3
Subnet Mask: 255.255.254.0
Gateway: 192.240.12.1
```

### Subnet A20
### Holo-Myth
```
enable
configure terminal
interface fa1/0
ip address 192.240.19.49 255.255.255.248
no shutdown
```
### Router4
```
enable
configure terminal
interface fa0/0
ip address 192.240.19.50 255.255.255.248
no shutdown
```
### Holo-Council
```
enable
configure terminal
interface fa0/0
ip address 192.240.19.51 255.255.255.248
no shutdown
```

### Subnet A21
### Router4
```
enable
configure terminal
interface fa0/1
ip address 192.240.19.57 255.255.255.248
no shutdown
```
### lrys
```
Dekstop IP Configuration
IP Address: 192.240.19.58
Subnet Mask: 255.255.255.248
Gateway: 192.240.19.57
```

### Subnet A22
### Holo-Council
```
enable
configure terminal
interface fa0/1
ip address 192.240.18.129 255.255.255.192
no shutdown
```
### Kronii_Mumei
```
Dekstop IP Configuration
IP Address: 192.240.18.130
Subnet Mask: 255.255.255.192
Gateway: 192.240.18.129
```
### Bae_Fauna
```
Dekstop IP Configuration
IP Address: 192.240.18.131
Subnet Mask: 255.255.255.192
Gateway: 192.240.18.129
```
### Konfigurasi Routing
### Sisi Kanan (Holo-ID)
### Hololive
```
enable
configure terminal
ip route 192.240.19.92 255.255.255.252 192.240.19.74
ip route 192.240.8.0 255.255.252.0 192.240.19.74
ip route 192.240.19.96 255.255.255.252 192.240.19.74
ip route 192.240.18.192 255.255.255.192 192.240.19.74
ip route 192.240.19.100 255.255.255.252 192.240.19.74
ip route 192.240.16.0 255.255.254.0 192.240.19.74
do write
```
### Holo-ID
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 192.240.19.73
ip route 192.240.8.0 255.255.252.0 192.240.19.94
ip route 192.240.18.192 255.255.255.192 192.240.19.98
ip route 192.240.16.0 255.255.254.0 192.240.19.102
do write
```
### AREA15
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 192.240.19.93
do write
```
### holoro
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 192.240.19.97
do write
```
### holoh3ro
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 192.240.19.101
do write
```

### Sisi Bawah (HoloJP)
### Hololive
```
enable
configure terminal
ip route 192.240.19.64 255.255.255.248 192.240.19.106
ip route 192.240.19.32 255.255.255.240 192.240.19.106
ip route 192.240.0.0 255.255.248.0 192.240.19.106
ip route 192.240.14.0 255.255.254.0 192.240.19.106
ip route 192.240.19.76 255.255.255.252 192.240.19.106
ip route 192.240.18.0 255.255.255.128 192.240.19.106
do write
```
### HoloJP
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 192.240.19.105
ip route 192.240.19.32 255.255.255.240 192.240.19.66
ip route 192.240.0.0 255.255.248.0 192.240.19.67
ip route 192.240.14.0 255.255.254.0 192.240.19.67
ip route 192.240.19.76 255.255.255.252 192.240.19.67
ip route 192.240.18.0 255.255.255.128 192.240.19.67
do write
```
### DEV_IS
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 192.240.19.65
ip route 192.240.0.0 255.255.248.0 192.240.19.67
ip route 192.240.14.0 255.255.254.0 192.240.19.67
ip route 192.240.19.76 255.255.255.252 192.240.19.67
ip route 192.240.18.0 255.255.255.128 192.240.19.67
do write
```
### GEN:0
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 192.240.19.65
ip route 192.240.19.32 255.255.255.240 192.240.19.66
ip route 192.240.14.0 255.255.254.0 192.240.0.2
ip route 192.240.19.76 255.255.255.252 192.240.0.2
ip route 192.240.18.0 255.255.255.128 192.240.0.2
do write
```
### GEN:1
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 192.240.0.1
ip route 192.240.18.0 255.255.255.128 192.240.19.78
do write
```
### GAMERS
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 192.240.19.77
do write
```
### Sisi Kiri (HoloEN)
### Hololive
```
enable
configure terminal
ip route 192.240.19.84 255.255.255.252 192.240.19.82
ip route 192.240.19.0 255.255.255.224 192.240.19.82
ip route 192.240.19.88 255.255.255.252 192.240.19.82
ip route 192.240.12.0 255.255.254.0 192.240.19.82
ip route 192.240.19.48 255.255.255.248 192.240.19.82
ip route 192.240.19.56 255.255.255.248 192.240.19.82
ip route 192.240.18.128 255.255.255.192 192.240.19.82
do write
```
### Holo-EN
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 192.240.19.81
ip route 192.240.19.0 255.255.255.224 192.240.19.86
ip route 192.240.12.0 255.255.254.0 192.240.19.90
ip route 192.240.19.48 255.255.255.248 192.240.19.90
ip route 192.240.19.56 255.255.255.248 192.240.19.90
ip route 192.240.18.128 255.255.255.192 192.240.19.90
do write
```
### HoloAdvent
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 192.240.19.85
do write
```
### Holo-Myth
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 192.240.19.89
ip route 192.240.19.56 255.255.255.248 192.240.19.50
ip route 192.240.18.128 255.255.255.192 192.240.19.51
do write
```
### Router4
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 192.240.19.49
ip route 192.240.18.128 255.255.255.192 192.240.19.51
do write
```
### Holo-Council
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 192.240.19.49
ip route 192.240.19.56 255.255.255.248 192.240.19.50
do write
```

# GNS (CIDR)
## Topologi
![image](https://github.com/user-attachments/assets/932f6ab3-6e70-491e-a527-ce4a925404a9)

## Rute
![image](https://github.com/user-attachments/assets/d0337e40-a791-4820-b20f-7e1333e0a434)
![image](https://github.com/user-attachments/assets/5fc7544e-4a1b-49b5-b0b9-c8dec708537d)

## Penggabungan
![image](https://github.com/user-attachments/assets/a189a503-e0a0-438a-8413-20af5342edb3)
![image](https://github.com/user-attachments/assets/121553d9-1f87-4c22-bbc7-cdb7117cf613)
![image](https://github.com/user-attachments/assets/0b029fee-eee5-4832-aecb-7fc5f7dd83d2)
![image](https://github.com/user-attachments/assets/16c72929-fcbd-4b02-9e02-4739f784f1b6)

## Konfigurasi
