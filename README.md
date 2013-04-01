# 概要

オリジナルの traptomail に次の変更を行いました。

 - `Date` ヘッダーを追加
 - `Content-Type` ヘッダーを追加
 - `-i` と `-e` オプションを追加（指定した CIDR にマッチする/しないソースアドレスのトラップのみメールする）

# インストール

```console
yum --enablerepo=epel install perl-DateTime perl-DateTime-Format-Mail perl-Net-CIDR-Lite
wget https://raw.github.com/ngyuki/traptoemail/master/traptoemail
chmod +x traptoemail
```
