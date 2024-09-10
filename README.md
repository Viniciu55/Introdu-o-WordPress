# Introdução-ao-WordPress


# Como Baixar o WordPress
Primeiro, acesse o [site localwp.com](https://localwp.com)
Clique na opção DOWNLOAD, isso irá abrir uma nova janela, clique em "please choose your plataform"
Até a data desse tutorial, existem 5 opções disponíveis para realizar o download, são elas:

1. Mac intel (não suportado nesse tutorial)
2. Mac Apple Silicon (não suportado nesse tutorial)
3. [Windows](#Instalação-no-Windows)
4. [Linux RPM based- (fedora, Red Hat Linux, CentOS)](#Instalação-em-distros-Linux-baseadas-em-RedHat)
5. [Linux - Debian based (ubuntu, etc)](#Instalação-em-distros-Linux-baseeadas-em-ubuntu)

Após selecionar a opção que deseja, irão abrir caixas de texto, preencha-os com primeiro nome, segundo nome, organização para qual você trabalha e e-mail de trabalho.
Depois de preenchidas essas informações, o download do arquivo será feito.

## Instalação no Windows
Para Instalar o wordpress no windows

## Instalação em distros Linux baseadas em RedHat

## Instalação em distros Linux baseeadas em ubuntu
Ao fazer o download, um arquivo .deb será baixado no seu computador, algumas distros baseadas em debian te permitem executar esse arquivo .deb, e abri-lo diretamente  na loja de apliicativos, porém não são todas.
Caso a sua não permita, abra o terminal no mesmo diretório onde o arquivo se encontra, e no terminal use o seguinte comando: `sudo dpkg -i local-9.x.x-linux.deb`
(obs: coloque o nome do arquivo que foi baixado, no lugar de X.X será o número da versão do programa que você baixou, você pode facilitar isso escrevendo apenas o início do nome e apertando a tecla TAB.)
Após isso, o gerenciador de pacotes .deb irá realizar a instalação do programa baixado.
obs: caso o seu terminal retorne algum erro como:

```
local depende de libnss3-tools; porém:
Pacote libnss3-tools não está instalado.
```
Basta digitar
