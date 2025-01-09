# Phishing para capturar senhas do Facebook

Este repositório foi criado para registrar o teste de aprendizado no curso de CiberSecurity, apenas para fins de aprendizagem.

## Ferramentas
* Kali LInux
* setoolkit

## Passos de utilização no Kali Linux/setoolkit
* Acesse como root: `sudo su`
* Inicie o setoolkit: `setoolkit`
* Tipo de Ataque: _[1] Social-Engineering Attacks_
* Vetor de Ataque: _[2] Website Attack Vectors_
* Método de Ataque: _[3] Credential Harvester Attack Method_
* Método de Ataque: _[2] Site Cloner_
* Inseria o IP da máquina após usar o ifconfig
* Insira a URL para clonar: https://pt-br.facebook.com
* Neste momento, para corrigir bugs em 01/2025, utilize o comando: `sudo sed -i '/"src":/d' /root/.set/web_clone/index.html`

## Resultados
![App Screenshot](https://github.com/marceloandrade93/cibersecurity-desafio-phishing/blob/main/results.png)