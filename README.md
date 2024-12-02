# ⚠️ สิ่งที่ต้องมีก่อนที่จะเริ่ม
1. [MetaMask Wallet](https://chromewebstore.google.com/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn)
2. [BNB Smart Chain](https://chainlist.org/chain/56)
3. ต้องมี `0.002 BNB` บน BNB Smart Chain

![Balance](./22.png)

# 💻 สเปคที่ต้องการสำหรับรันโหนด

### ขั่นต่ำ:
  - CPU with 1+ cores
  - 2GB RAM
  - 4 Mbps download Internet service
### แนะนำ:
  - Fast CPU with 2+ cores
  - 4GB+ RAM
  - 8+ Mbps download Internet service
‎ 
# 💸 วิธีในการขอ Faucet
### 1️⃣ เพิ่ม Network ของ opBNB Testnet ลงในกระเป๋า [[ลิ้งคลิก]](https://chainlist.org/chain/5611)

![Addrpc](./88.png)

### 2️⃣ ทำการขอ BNB Faucet [[ลิ้งคลิก]](https://www.bnbchain.org/en/testnet-faucet)

![Faucet](./111.png)

### 3️⃣ ทำการแลก `0.1 BNB` จาก BNB Smart Chain Testnet ไปยัง opBNB Testnet [[ลิ้งคลิก]](https://opbnb-testnet-bridge.bnbchain.org/deposit)

![Brige](./222.png)
‎
# 🌐 วิธีติดตั้งบน Windows
### 1️⃣ สร้างโฟลเดอร์ใหม่ชื่อว่า Glacier ไปที่ Desktop > คลิกขวา > New > Folder > พิมพ์ว่า Glacier > Enter

![Folder](./33.png)

### 2️⃣ ดาวน์โหลด Node จาก [Glacier Labs](https://github.com/Glacier-Labs/node-bootstrap/releases) (ไฟล์.exe) ลงในโฟลเดอร์ Glacier

![Download](./44.png)

### 3️⃣ เปิด Notepad ก็อปปี้คำสั่งจากด้านล่าง แล้ววางลงใน Notepad

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

### 4️⃣ วาง PrivateKey ของกระเป๋าเรา แทนคำว่า YourPrivateKey

![PrivateKey](./1.gif)

### 5️⃣ กดคำว่า File ซ้ายบน > Save as > Desktop > Glacier > ตั้งชื่อไฟล์ว่า config.yaml

![Saveas](./55.png)

![Saveas](./66.png)

### 6️⃣ เริ่มการทำงานของ Node ได้เลย

![Start](./77.png)
‎ 
# ✅เช็คการทำงานของ Node
### เข้าเว็บนี้ ---> https://testnet.nodes.glacier.io/status

![Start](./99.png)

# 🎞️ ฝากติดตาม [Viwsion Mining](https://www.youtube.com/@VwisionMining/videos) ด้วยนะครับ

![Youtube](./Vwision.png)