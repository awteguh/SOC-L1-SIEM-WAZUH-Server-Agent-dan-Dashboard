# Insatal Wazuh Server di Linux

1. Instal dan copy pw nya
   ```
   curl -sO https://packages.wazuh.com/4.14/wazuh-install.sh && sudo bash ./wazuh-install.sh -a
   ```
   <img width="839" height="722" alt="Image" src="https://github.com/user-attachments/assets/e60e2521-3e82-4384-959e-433f3cb6d27c" />
2. allow port 443, 1514, 1515
3. seting network vm dari Nat menjadi Adaptor Ter Bridge, agar Ip Server berubah dan bisa di akses di local
4. copy ip server dan buka di local agar bisa akses Dahsboard Wazuh
   <img width="835" height="715" alt="Image" src="https://github.com/user-attachments/assets/bf82549b-d629-429a-8dd1-a3caeab125f2" />
   
