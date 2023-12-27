# Manager
![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/f40ff905-8604-45cc-b24c-7b0a12af4aaf)
## 一 user flag
### 1.使用nmap進行掃描，發現smb的版本有漏洞
![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/84b08bfa-f2f4-47e0-980e-e71b689aa418)
![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/163933f3-a86b-4f65-bd75-2510fdd6a40d)
### 2.使用crackmapexec這個工具來進行使用者名稱的爆破
![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/4e1ddcd9-8388-43c9-bc14-575aaa8a14bf)
### 3.得到7個使用者，建成user.txt
![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/d3fd7b84-b391-4995-a19a-1dc2f0cf8b5a)
### 4.再利用crackmapexec 去使用user.txt進行密碼爆破，發現成功後便會停下來，無法得知全部使用者是否還有其他密碼與使用者名稱相同
![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/374c5589-b2c1-413b-8e88-18b68615ea06)
### 5.因此在指令後方加上 --no-brute --continue-on-success ，可避免每個使用者名稱都對每一個名稱進行爆破，只須對自己的名稱做嘗試，且在成功後仍會繼續嘗試，直至完成
![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/ec8e0172-cc32-4f33-90d7-fb7314cdb5b9)
### 6.
![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/c8dbaa3f-e26f-46a2-b969-8e5116efc099)
### 7.
![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/b5f558c1-8d35-4d30-beb6-377a4a03969a)
### 8.
![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/b79d6427-c6a6-4735-a878-fe2b823ea167)
### 9.
![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/87995a0a-3f97-4488-8a8e-c94d4f20340d)
### 
![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/228928c7-ab08-4921-ac2b-910c2d6bead1)
###
![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/4cd7c14c-9ca1-475b-8b25-49753004bf2e)
### 
![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/752618e3-786f-4fbf-b0e1-fc597e79fea5)

## 二 root flag

![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/2540ec5e-8cba-498c-ad73-b5146e873d63)

![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/f89badf4-f563-4a92-a4a3-6492c5241939)


![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/be5a2a44-6596-47dd-89f4-3a222c08b21f)

![image](https://github.com/TwMoonBear-Arsenal/Pub-ClassWork/assets/144238471/29bc4c3f-017b-4b16-895b-78fe376bf7f6)
