# Introdução ao WordPress
## O que é o WordPress?
O WordPress é um sistema de gerenciamento de conteúdo de código aberto, ele é usado papra a criação de sites e blogs e é muito popular devido á facilidade do seu uso e a sua vasta gama de recursos, permitindo criar um site completo sem precisar usar nenhum código através de uma interface amigável.
### Versões
o wordpress possui verrsões diferentes, existe o wordpress.org e o wordpress.com
#### [O wordpress.org](https://wordpress.org/):
Essa é a versão é totalmente grátis, e te permite criar o site, porém não garante o domínio e nem a hospedagem, ou seja, você pode criar o site, mas ainda precisará de um serviço de hospedagem e de um domínio para poder colocar o site no ar.
####  [O wordpress.com](https://wordpress.com/pt-br/):
Essa versão é paga, pois além de permitir usar o wordpress para a criação do seu site, também fornece os serviços de hospedagem e domínio, porém, essa versão é paga.

# Download e instalação do WordPress:
### Nesse caso, você tem duas opções, pode usar a [versão oficial](#Usando-os-arquivos-disponibilizados-no-site-oficial) disponibilizada no site, ou baixar uma [ferramenta](#Usando-a-ferramenta-localwp) para facilitar a gestão projeto, nesse tutorial iremos abordar as duas opções.

## Usando os arquivos disponibilizados no site oficial:
O site fornece o download de dois formatos de arquivo, o .zip ou o .tar.gz
##### **No windows**, é recomendável baixar a versão .zip, e extrair normalmente usando o winrar.
##### **No Linux**, você pode baixar qualquer uma das versões.
 - Para extrair o .zip você pode usar um gerenciador de arquivos compactados, ou usar o comando: `unzip nomedoprograma.zip`
 - Para extrair o .tar.gz você pode usar o comando: `tar -xzvf arquivo.tar.gz`
### Instalação do Wordpress:
Após a extração do conteúdo compactado, entre em: wordpress/wp-admin/
Dentro dessa pasta, execute o oarquivo install.php pelo navegador e o processo de instalação irá começar.
##### Obs: Para executar esse arquivo pelo navegador, você vai precisar iniciar um servidor web como o Apache, Nginx ou algum similar, com o php instalado.

## Usando a ferramenta localwp:
Primeiro, acesse o [site localwp.com](https://localwp.com),
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
Ao fazer o download, um arquivo .exe será baixado no seu computador, quando o download terminar, basta executar esse arquivo.
Será aberta a janela de instalação, primeiro perguntando se você deseja instalar apenas no seu usuário ou para todos os existentes, escolha e aperte próximo.
Aparecerá uma segunda perguntando se deseja alterar o local de instalação ou manter o mesmo, basta pressionar "Instalar" e o probrama será instalado.
Após isso, o programa já estará instalado.

## Instalação em distros Linux baseadas em RedHat

## Instalação em distros Linux baseeadas em ubuntu
Ao fazer o download, um arquivo .deb será baixado no seu computador.

Obs: algumas distros baseadas em debian te permitem executar esse arquivo .deb, e abri-lo diretamente  na loja de apliicativos, porém não são todas.

Caso a sua não permita, não tem problema, abra o terminal no mesmo diretório onde o arquivo se encontra, e no terminal use o seguinte comando: 
`sudo dpkg -i local-9.x.x-linux.deb`
###### (obs: coloque o nome do arquivo que foi baixado, no lugar de X.X será o número da versão do programa que você baixou, você pode facilitar isso escrevendo apenas o início do nome e apertando a tecla TAB.)

Após isso, o gerenciador de pacotes .deb irá realizar a instalação do programa baixado.
obs: caso o seu terminal retorne algum erro como:

```
local depende de libnss3-tools; porém:
Pacote libnss3-tools não está instalado.
```
Basta digitar:
`sudo apt-get install libnss3-tools` (com o nome do respectivo pacote no lugar de libnss3-tools)
E tentar executar novamente a instalação.

Após isso, o programa já está instalado, e pode ser aberto através do atalho nos aplicativos, ou através do comando `/usr/bin/local` no seu terminal.

# Após a instalação 
Ao executar o programa pela primeira vez, ele irá pedir para que você aceite os termos de serviço, e depois entrar usando uma conta.
A partira daí, o programa já está funcionando.
