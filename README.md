# LotServer_KeyGen


Usage: 
  - cli: 
  ```
  php keygen.php mac [ver]
  For example, php keygen.php 00:00:00:00:00:00 1
  ```
  - web:
  ```
  http://example.com/keygen.php?ver=1&mac=00:00:00:00:00:00
  ```
git clone xxxxx

cd LotServer_KeyGen

php keygen.php 00:00:00:00:00:00 (使用 ifconfig 查看网卡 mac 地址，替换 00:00:00:00:00:00)


cp out.lic /appex/etc/apx.lic

