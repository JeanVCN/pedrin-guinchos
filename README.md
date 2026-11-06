# Pedrin Guinchos

Site estático da Pedrin Guinchos, em Cianorte, PR.

## Executar localmente

```sh
python3 -m http.server 8000 --directory docs
```

Abra http://localhost:8000. Não requer instalação ou compilação.

## GitHub Pages

Em Settings → Pages, selecione Deploy from a branch, branch main e pasta /docs. Domínio personalizado: pedringuinchos.online. Ative Enforce HTTPS quando o certificado estiver disponível.

## DNS na Hostinger

Configure quatro registros A com nome @:

- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

Configure CNAME com nome www e destino JeanVCN.github.io.

Substitua registros de estacionamento conflitantes para @ e www. Preserve os registros de e-mail. Os nameservers podem continuar na Hostinger.

Documentação: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
