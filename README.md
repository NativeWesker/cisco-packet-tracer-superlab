# cisco-packet-tracer-superlab
Enterprise Network Topology Design - 10 Core Features Superlab

Proyek ini menyimulasikan arsitektur jaringan skala enterprise menggunakan Cisco Packet Tracer. Lab ini dirancang untuk memvalidasi implementasi routing, switching, security, dan otomasi berbasis kurikulum Cisco CCNA (ITN, SRWE, ENSA).

## 🗺️ Topologi Jaringan
![Network Topology](Superlab%20Library.jpg)

## 🚀 Fitur Utama & Teknologi yang Diimplementasikan
Lab ini mengintegrasikan 10 fitur utama jaringan:
1. **Dynamic Routing Protocol:** Menggunakan OSPF Multi-area dan RIPv2 untuk pertukaran rute yang dinamis.
2. **Route Redistribution:** Menghubungkan routing domain yang berbeda (OSPF <=> RIP) secara efisien.
3. **Route Filtering & Security:** Implementasi **Prefix Lists** dan **Distribute Lists** untuk kontrol rute, serta **MD5 Authentication** pada protokol routing.
4. **VLAN & Inter-VLAN Routing:** Pembagian segmen jaringan menggunakan Router-on-a-Stick dan Switch Layer 3.
5. **Redundancy & High Availability:** Implementasi EtherChannel (LACP/PAgP) dan HSRP untuk gateway redundan.
6. **Network Security:** Penerapan Standard & Extended Access Control Lists (ACLs) untuk membatasi hak akses.
7. **IP Services:** Konfigurasi DHCP Server, NAT (Static & Dynamic/PAT), serta NTP untuk sinkronisasi waktu.
8. **Device Management & Hardening:** Mengamankan akses perangkat melalui SSHv2, HTTPS, dan enkripsi password (Secret).
9. **Wireless LAN (WLAN):** Konfigurasi WLC (Wireless LAN Controller) berbasis GUI dengan keamanan WPA2-Enterprise.
10. **WAN Encapsulation:** Simulasi koneksi antar cabang menggunakan enkripsi HDLC/PPP.
