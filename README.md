# Quia-Contrat-Deploy

## Gereksinimler ##
1-Github hesabı </br>
2-[Pelagus Wallet](https://chromewebstore.google.com/detail/pelagus/gaegollnpijhedifeeeepdoffkgfcmbc) indirmeniz lazım boş chrome indirin main cüzdan yanına indirme </br>
3-[Gitpod (github ile giriş yapıyoruz)](https://www.gitpod.io/)


## Codları gitpod üzerine teker teker giriyoruz ##
1-Alttaki kodları sırayla tek tek giriyoruz. </br>
```
git clone https://github.com/dominant-strategies/hardhat-example.git
cd hardhat-example/Solidity 
npm install
```
2-Şimdi cp kodunu girin: </br>
```
cp ../.env.dist ../.env
```
3-İçine giriyoruz: </br>
```
nano ../.env
```
4-Bu alan içinde CYPRUSPK1="0X000000" yazanı silip kendi Pelagus wallet private keyimizi giriyoruz.(Cüzdanda 2-3 QUAI OLMALI HATA ALIRSINIZ) Tırnakları silmeyin= "0xMYPRIVATEKEY" </br>
[QUAI FAUCET](https://faucet.quai.network/) Private keyi resimdeki gibi alabilirsin.
![cyprus](https://github.com/0xDarkKing/Quia-Contrat-Deploy/assets/164199934/d667d03f-fdc9-4f03-a67c-7b4f69bf6645)


5-İşlem tamamlanınca CTRL+X basıyoruz ve CTRL+Y ile kaydediyoruz + ENTER </br>
6-Bu kodu çalıştırın:</br>
```
npx hardhat compile
```
7-Sonra bu komutu çalıştırın:
```
npx hardhat run scripts/deployERC20.js --network cyprus1
```
![image](https://github.com/0xDarkKing/Quia-Contrat-Deploy/assets/164199934/a56d044c-3171-4129-8662-66200f3857e8)

9-Bu şekilde çıktı aldıysanız bitmiştir.SS alıp discord kanalına atıyoruz. </br>
10-İçeriği hazırlamamda yardımcı olan Furkan'a teşekkür ediyorum </br>
11-[Twitter adresim](https://twitter.com/Aiakoss)
