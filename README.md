🔑 GPG key: [`ABA6AA235B1DEB89F63831F6FDB9D26CF8A02895`](https://keys.openpgp.org/vks/v1/by-fingerprint/ABA6AA235B1DEB89F63831F6FDB9D26CF8A02895)

GPG key hosted at [GitHub](https://github.com/liuyuhe666.gpg)

## 加密文件

```bash
gpg --recipient ABA6AA235B1DEB89F63831F6FDB9D26CF8A02895 --output hi.txt.gpg --encrypt hi.txt
```

- `--recipient`: 指定接收者的公钥
- `--output`: 指定加密后的文件名
- `--encrypt`: 指定需要加密的源文件

## 解密文件

```bash
gpg --output result.txt --decrypt hi.txt.gpg
```
对方收到加密文件后，就可以用自己的私钥进行解密。