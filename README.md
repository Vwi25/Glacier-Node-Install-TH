<h1 align="center">⚠️ สิ่งที่ต้องมีก่อนที่จะเริ่ม</h1>
### 1. MetaMask Wallet [[ลิ้งคลิก]](https://chromewebstore.google.com/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn)
### 2. เชื่อมกระเป๋าเพื่อลงทะเบียน & ดูคะแนน [[ลิ้งคลิก]](https://www.glacier.io/points/)

![Connect](./Connet.png)

### 3. เพิ่ม BNB Smart Chain [[ลิ้งคลิก]](https://chainlist.org/chain/56)
### 4. ต้องมี `0.002 BNB` บน BNB Smart Chain

![Balance](./22.png)

‎ 
<h1 align="center">💻 สเปคที่ต้องการสำหรับรันโหนด</h1>

### ขั่นต่ำ:
  - CPU with 1+ cores
  - 2GB RAM
  - 4 Mbps download Internet service
### แนะนำ:
  - Fast CPU with 2+ cores
  - 4GB+ RAM
  - 8+ Mbps download Internet service

‎ 
<h1 align="center">💸 วิธีในการขอ Faucet</h1>
### 1. เพิ่ม Network ของ opBNB Testnet ลงในกระเป๋า [[ลิ้งคลิก]](https://chainlist.org/chain/5611)

![Addrpc](./88.png)

‎ 
### 2. ทำการขอ BNB Faucet [[ลิ้งคลิก]](https://www.bnbchain.org/en/testnet-faucet)

![Faucet](./111.png)

‎ 
### 3. ทำการแลก `0.1 BNB` จาก BNB Smart Chain Testnet ไปยัง opBNB Testnet [[ลิ้งคลิก]](https://opbnb-testnet-bridge.bnbchain.org/deposit)

<div align="center">
<img src="./222.png" alt="Brige">
</div>
‎
<h1 align="center">🌐 วิธีติดตั้งบน Windows</h1>
<h3 align="center">1. สร้างโฟลเดอร์ใหม่ชื่อว่า Glacier ไปที่ Desktop > คลิกขวา > New > Folder > พิมพ์ว่า Glacier > Enter</h3>

<div align="center">
<img src="./33.png" alt="Folder">
</div>

‎ 
### 2. ดาวน์โหลด Node จาก [Glacier Labs](https://github.com/Glacier-Labs/node-bootstrap/releases) (ไฟล์.exe) ลงในโฟลเดอร์ Glacier

![Download](./44.png)

‎ 
### 3. เปิด Notepad ก็อปปี้คำสั่งจากด้านล่าง แล้ววางลงใน Notepad

```yaml
Http:
  Listen: "127.0.0.1:10801"
Network: "testnet"
RemoteBootstrap: "https://glacier-labs.github.io/node-bootstrap/"
Keystore:
  PrivateKey: "YourPrivateKey"
TEE:
  IpfsURL: "https://greenfield.onebitdev.com/ipfs/"
```

![Notepad](./4444.png)

‎ 
### 4. วาง PrivateKey ของกระเป๋าเรา แทนคำว่า YourPrivateKey ใน Notepad
<div align="center">
    <h3>⬇️วิธีดู Private Key⬇️</h3>
</div>

<div align="center">
    <img src="./1.gif" alt="Private" width="428" height="720">
    <img src="./2.gif" alt="Private" width="428" height="720">
</div>

‎ 
### 5. กดคำว่า File ซ้ายบน > Save as > Desktop > Glacier > ตั้งชื่อไฟล์ว่า config.yaml

![Saveas](./55.png)

![Saveas](./66.png)

‎ 
### 6. เริ่มการทำงานของ Node ได้เลย

![Start](./77.png)

<h1 align="center">✅เช็คการทำงานของ Node</h1>
### เข้าเว็บนี้ ---> https://testnet.nodes.glacier.io/status

![Start](./99.png)

<h1 align="center">🎞️ ฝากติดตาม [Viwsion Mining](https://www.youtube.com/@VwisionMining/videos) ด้วยนะครับ</h1>

![Youtube](./Vwision.png)