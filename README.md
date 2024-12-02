## สิ่งที่ต้องมี
1. [MetaMask Wallet](https://chromewebstore.google.com/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn)
2. [BNB Smart Chain](https://chainlist.org/chain/56)
3. ต้องมี `0.002 BNB` บน BNB Smart Chain

## สเปคที่ต้องการสำหรับรันโหนด

### ขั่นต่ำ:
  - CPU with 1+ cores
  - 2GB RAM
  - 4 Mbps download Internet service
### แนะนำ:
  - Fast CPU with 2+ cores
  - 4GB+ RAM
  - 8+ Mbps download Internet service

## วิธีในการขอ Faucet
1. เพิ่ม Network ของ opBNB Testnet ลงในกระเป๋า [[ลิ้งคลิก]](https://chainlist.org/chain/5611)
2. ทำการขอ BNB Faucet [[ลิ้งคลิก]](https://www.bnbchain.org/en/testnet-faucet)
3. ทำการแลก `0.1 BNB` จาก BNB Smart Chain Testnet ไปยัง opBNB Testnet [[ลิ้งคลิก]](https://opbnb-testnet-bridge.bnbchain.org/deposit)

## วิธีติดตั้งบน Windows
1. สร้างโฟลเดอร์ใหม่ชื่อว่า Glacier ไปที่ Desktop > คลิกขวา > New > Folder > พิมพ์ว่า Glacier > Enter
2. ดาวน์โหลด Node จาก [Glacier Labs](https://github.com/Glacier-Labs/node-bootstrap/releases) (ไฟล์.exe) ลงในโฟลเดอร์ Glacier
3. เปิด Notepad ก็อปปี้คำสั่งจาก [ลิ้งนี้](https://glacier-labs.github.io/node-bootstrap/config.yaml) วางลงใน Notepad
4. วาง PrivateKey ของกระเป๋าเรา แทนคำว่า YourPrivateKey [[วิธีดู Private Key]](https://support.metamask.io/managing-my-wallet/secret-recovery-phrase-and-private-keys/how-to-export-an-accounts-private-key/)
5. กดคำว่า File ซ้ายบน > Save as > Desktop > Glacier > ตั้งชื่อไฟล์ว่า config.yaml
6. เริ่มรันโหนดโดยกดไฟล์ verifier_windows_amd64.exe