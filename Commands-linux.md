### 1. Gerenciamento de Usuários, Permissões, Grupos e Arquivos

Comandos relacionados à criação e administração de usuários, permissões de arquivos e grupos.

| Comando    | Descrição                                  | Exemplo                                   |
| ---------- | ------------------------------------------ | ----------------------------------------- |
| `useradd`  | Cria um novo usuário.                      | `useradd Paulo`                           |
| `userdel`  | Exclui um usuário.                         | `userdel Paulo`                           |
| `chmod`    | Modifica permissões de arquivos.           | `chmod 777 note.txt`                      |
| `chown`    | Altera a propriedade de arquivos.          | `chown linuxuser2 filename.txt`           |
| `groupadd` | Cria um novo grupo.                        | `groupadd developers`                     |
| `groupdel` | Exclui um grupo.                           | `groupdel developers`                     |
| `usermod`  | Modifica um usuário existente.             | `usermod -aG sudo paul`                   |
| `chgrp`    | Altera o grupo de um arquivo ou diretório. | `chgrp admins file.txt`                   |
| `mkdir`    | Cria diretórios.                           | `mkdir new_folder`                        |
| `rmdir`    | Remove diretórios vazios.                  | `rmdir empty_folder`                      |
| `ls`       | Lista os arquivos de um diretório.         | `ls /home/username/Documents`             |
| `cat`      | Exibe ou cria arquivos.                    | `cat filename.txt`                        |
| `touch`    | Cria arquivos vazios.                      | `touch /home/username/Documents/Web.html` |
| `locate`   | Localiza arquivos rapidamente.             | `locate myfile.txt`                       |
| `find`     | Localiza arquivos dentro de um diretório.  | `find /home/ -name 'notes.txt'`           |
| `grep`     | Pesquisa por palavras dentro de arquivos.  | `grep "searchword" filename.txt`          |
| `cp`       | Copia arquivos ou diretórios.              | `cp file.txt /home/user/`                 |
| `mv`       | Move ou renomeia arquivos.                 | `mv file.txt /home/user/`                 |
| `rm`       | Remove arquivos ou diretórios.             | `rm file.txt`                             |
| `head`     | Exibe as primeiras linhas de um arquivo.   | `head -n 5 filename.txt`                  |
| `tail`     | Exibe as últimas linhas de um arquivo.     | `tail -n 10 filename.txt`                 |
| `man`      | Exibe o manual de um comando.              | `man ls`                                  |

### 2. Sistema

Comandos gerais do sistema.

| Comando       | Descrição                                                  | Exemplo                                 |
| ------------- | ---------------------------------------------------------- | --------------------------------------- |
| `ping`        | Verifica a conectividade de rede.                          | `ping google.com`                       |
| `wget`        | Baixa arquivos da internet.                                | `wget https://wordpress.org/latest.zip` |
| `hostname`    | Exibe o nome do host do sistema.                           | `hostname -i`                           |
| `ifconfig`    | Exibe as configurações de rede do sistema.                 | `ifconfig`                              |
| DISCO         |                                                            |                                         |
| `df`          | Exibe informações sobre o uso do espaço em disco.          | `df -h`                                 |
| `du`          | Exibe o uso de espaço por arquivos ou diretórios.          | `du -h /home/username/Documents`        |
| `fdisk`       | Gerencia as partições do disco.                            | `fdisk -l`                              |
| `lsblk`       | Exibe informações sobre dispositivos de bloco.             | `lsblk`                                 |
| `blkid`       | Exibe o identificador único dos dispositivos de bloco.     | `blkid`                                 |
| `mount`       | Monta sistemas de arquivos.                                | `mount /dev/sda1 /mnt`                  |
| `umount`      | Desmonta um sistema de arquivos.                           | `umount /mnt`                           |
| `parted`      | Ferramenta para manipulação de partições de disco.         | `parted /dev/sda`                       |
| `fsck`        | Verifica e corrige sistemas de arquivos.                   | `fsck /dev/sda1`                        |
| PACOTE        |                                                            |                                         |
| `apt-get`     | Gerencia pacotes no Linux.                                 | `apt-get update`                        |
| `apt install` | Instala pacotes no Linux.                                  | `apt-get update`                        |
| `apt remove`  | Remove pacotes no Linux.                                   | `apt-get update`                        |
| `dpkg`        | Gerencia pacotes no formato .deb.                          | `dpkg -i pacote.deb`                    |
| `yum`         | Gerencia pacotes no Red Hat/CentOS.                        | `yum install pacote`                    |
| COMPACTAÇÃO   |                                                            |                                         |
| `tar`         | Cria ou extrai arquivos TAR.                               | `tar -cvf backup.tar /home/username`    |
| `zip`         | Compacta arquivos em formato zip.                          | `zip archive.zip file.txt`              |
| `unzip`       | Descompacta arquivos zip.                                  | `unzip archive.zip`                     |
| MONITORAMENTO |                                                            |                                         |
| `top`         | Exibe processos em execução e o uso de CPU.                | `top`                                   |
| `htop`        | Exibe processos e recursos do sistema de forma interativa. | `htop`                                  |
| `ps`          | Exibe os processos em execução no sistema.                 | `ps aux`                                |
| `df`          | Exibe informações sobre o uso do espaço em disco.          | `df -h`                                 |
| `du`          | Exibe o uso de espaço por arquivos ou diretórios.          | `du -h /home/username/Documents`        |

### 2. Banco de Dados - Samba

Comandos utilizados para gerenciar o banco de dados de usuários do Samba, permitindo adicionar, ativar e listar usuários.

| Comando     | Descrição                                       | Exemplo                   |
| ----------- | ----------------------------------------------- | ------------------------- |
| `smbpasswd` | Adiciona usuário ao banco de dados do Samba.    | `sudo smbpasswd -a maria` |
| `smbpasswd` | Ativar o usuário no banco de dados do Samba.    | `sudo smbpasswd -e maria` |
| `pdbedit`   | Listar todos os usuários configurados no Samba. | `sudo pdbedit -L`         |
