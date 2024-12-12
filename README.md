# getrass Auto69 - Pakai Auto Proxy (windows & Linux)
Bot untuk membuat koneksi WebSocket melalui proxy HTTP dan SOCKS, yang saya khususkan untuk panen poin Grass Season 2.

Bagi yang belum punya akun daftar dulu di [https://app.getgrass.io/dashboard](https://app.getgrass.io/register?referralCode=liddOb-n6Eg1JyU).

## Ringkasan

`getgrass Auto69` terhubung ke server WebSocket menggunakan proxy HTTP dan SOCKS. Ini memanfaatkan perpustakaan `ws` untuk komunikasi WebSocket dan mengintegrasikan perpustakaan `https-proxy-agent` dan `socks-proxy-agent` untuk meningkatkan dukungan proxy. Hal ini memungkinkan koneksi yang lebih fleksibel dan tangguh, mengakomodasi jenis proxy yang lebih luas, untuk memperoleh poin gras sebanyak banyaknya tanpa perlu pusing cari proxy.

# install NodeJs
### (windows)
[download & install NodeJs](https://nodejs.org/en/download/prebuilt-installer) jika masih belum terinstall.

### (Linux)
  ```bash
curl -fssL https://deb.nodesource.com/setup_19.x | sudo -E bash
sudo apt install -y nodejs
sudo apt install git -y
  ```

Jika NodeJs sudah terinstall maka:

# Install grassnode (proxy kalian beli / cari sendiri)
### (Windows)
```
git clone https://github.com/kajijp/grass-auto.git
```
```
cd getgrass-pakai-auto-proxy
```
```
pip install -r requirements.txt
```
```
python grassnode.py
```
### (Linux)
```
sudo apt update && apt install tmux && apt install python3 python3-venv python3-pip -y
```
```
tmux new -s Auto69
```
```
python3 -m venv Auto69
```
```
source Auto69/bin/activate
```
```
git clone https://github.com/kajijp/grass-auto.git
```
```
cd getgrass-pakai-auto-proxy
```
```
pip install -r requirements.txt
```
```
nano local_proxies.txt
```
```
python3 grassnode.py
```


# Auto69 (auto proxy gratis)
```
git clone https://github.com/kajijp/grass-auto.git
```
```
pip install -r requirements.txt
```
```
cd single
```
```
Auto69.py
```
# Auto69 (Multi Akun & auto proxy gratis)
```
git clone https://github.com/kajijp/grass-auto.git
```
```
cd multi
```
```
pip install -r requirements.txt
```
Masukkan UserID kalian di 'user_id.txt'.
```
Auto69.py
```

# Cara mendapatkan userid grass
- login ke dashboard grass
- tekan f12
- cari tab console
- pastekan ini di console
``` 
localStorage.getItem('userId')
```
- kalau error, ketik ```allow pasting``` lalu enter
- lalu paste ```localStorage.getItem('userId')``` lalu enter
- simpan UserID kalian (semua huruf dan angka tanpa tanda petik 1 atau 2)

  
Gabung [Channel Telegram](https://t.me/kajijp) sekarang dan dapatkan banyak info garapan mudah tapi JP Maksimal.

## Donasi

Jika Anda ingin mendukung pengembangan channel ini, Anda dapat memberikan donasi melalui alamat berikut:

- **Solana**: `#########`
- **EVM**: `0xaF00AFE8937dfc19e04833e7279B3C695d344352`
- **XRP**: `rJUZprqjEc9V844Eo3d9jLp34cvTtxpckd`

## License

Proyek ini dilisensikan di bawah Lisensi MIT - lihat file [LISENSI](LICENSE) untuk detailnya.

## Kontribusi
Jika Anda merasa proyek ini bermanfaat, mohon pertimbangkan untuk memberikannya bintang di GitHub! Dukungan dapat memotivasi pengembangan dan peningkatan lebih lanjut.
Terima Kasih.
