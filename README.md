# Bucket do Scoop da FaKL-Code

Bucket do [Scoop](https://scoop.sh) para a [FaKL-Code IDE](https://github.com/FaKL-Code/FaKL-Code-IDE).

```powershell
scoop bucket add fakl-code https://github.com/FaKL-Code/scoop-bucket
scoop install fakl-code
```

O instalador do Windows não é assinado e o Scoop extrai os arquivos do instalador (instalação
portátil): a IDE só avisa de versão nova, e a atualização é `scoop update fakl-code`. O manifesto
é gerado pela release da FaKL-Code (`build/empacotar.mjs`); veja
[docs/distribuicao.md](https://github.com/FaKL-Code/FaKL-Code-IDE/blob/main/docs/distribuicao.md).
O manifesto ainda não foi testado com o Scoop instalado.
