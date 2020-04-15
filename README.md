# Estudos Let's Encrypt

## O que é?

## Como surgiu?

## Problemas que resolve?

## O que é um certificado HTTPS?

## Tipos de certificados

# Comando básicos

### Instalação da ferramenta

```ssh
sudo add-apt-repository ppa:certbot/certbot

sudo apt-get update

sudo apt-get install python-certbot-apache
```

### Instalando o certificado

```ssh
sudo certbot --apache -d meudominio.com -d www.meudominio.com

sudo certbot --apache -d ead.prof-e.net.br -d prof-e.net.br -d files.prof-e.net.br -d phpmyadmin.prof-e.net.br
```

### Lista os certificados configurados

```ssh
certbot certificates
```

# Referências

1. https://tudosobrehospedagemdesites.com.br/como-instalar-certificado-lets-encrypt/
2. https://certbot.eff.org/docs/using.html