<p style="font-size:14px" align="right">
<a href="https://t.me/Bal33671" target="_blank">Reach me on telegram <img src="https://user-images.githubusercontent.com/50621007/183283867-56b4d69f-bc6e-4939-b00a-72aa019d1aea.png" width="30"/></a>
<a href="https://twitter.com/Bal3367" target="_blank">Visit my twitter <img src="https://user-images.githubusercontent.com/110718880/204088136-3e807cf8-1fc4-4a7d-a833-d58180e36413.png" width="30"/></a>
</p>



# Tutorial Node Chainflip

Dokumen Official :
> [Doc Offical](https://docs.chainflip.io/perseverance-validator-documentation/ "Doc Offical")

Explorer :
> [Explorer Chainflip](https://blocks-perseverance.chainflip.io/ "Explorer Chainflip")

![image](https://user-images.githubusercontent.com/119092888/204086553-ab726941-17a8-4a6e-84af-58cf144f796c.png)


# Chainflip

# Spesifikasi minimum untuk menjalankan node Chainflip

OS: Ubuntu 20.04

CPU: 4 GHz 

RAM: 8 GB

SSD: 50 GB (Lebih besar lebih bagus)

Bandwidth: Recommended 1GBps connection, 100 GB bandwidth combined up/down per month

# Membuat User
```console
sudo useradd -s /bin/bash -d /home/flip/ -m -G sudo flip
```

# Menambahkan Password 
```console
sudo passwd flip
```
- Kalian harus ingat password ini 

# Setup SSH Akses
```console
mkdir /home/flip/.ssh
sudo cp /root/.ssh/authorized_keys /home/flip/.ssh/authorized_keys
sudo chown -R flip:flip /home/flip/.ssh/
sudo chmod 0700 /home/flip/.ssh/
```

# Login Ke SSH  Flip
```console
ssh flip@<IP PUB Kamu>
```
Jika command diatas gagal kalian bisa mencoba ini
```console
su - flip
```
