# 🐧 Linux Guide

Bem-vindo ao repositório **Linux Guide**, um guia abrangente para aprender e dominar o sistema operacional Linux. Aqui você encontrará recursos essenciais, tutoriais, comandos úteis e boas práticas para diferentes distribuições Linux.

---

## 📖 Índice

- [Introdução ao Linux](/introdução-ao-linux)
- [Distribuições Linux](#distribuições-linux)
- [Comandos Básicos](#comandos-básicos)
- [Gerenciamento de Pacotes](#gerenciamento-de-pacotes)
- [Sistema de Arquivos](#sistema-de-arquivos)
- [Permissões e Propriedades](#permissões-e-propriedades)
- [Gerenciamento de Processos](#gerenciamento-de-processos)
- [Shell Scripting](#shell-scripting)
- [Segurança no Linux](#segurança-no-linux)
- [Recursos e Referências](#recursos-e-referências)

---

## 🐧 Introdução ao Linux

Linux é um sistema operacional de código aberto baseado no Unix, amplamente utilizado em servidores, desktops, sistemas embarcados e dispositivos móveis. Algumas características do Linux:

- Gratuito e de código aberto.
- Seguro, estável e escalável.
- Altamente personalizável.
- Multitarefa e multiusuário.

---

## 📦 Distribuições Linux

Existem várias distribuições (distros) Linux, cada uma adaptada para diferentes necessidades. Algumas populares incluem:

| Distribuição  | Base      | Indicado para               |
|---------------|-----------|-----------------------------|
| Ubuntu        | Debian    | Iniciantes, desktops e servidores |
| Debian        | Debian    | Estável, servidores          |
| Fedora        | RedHat    | Desenvolvedores, bleeding-edge |
| Arch Linux    | Independente | Usuários avançados, personalização |
| CentOS/RHEL   | RedHat    | Empresas e servidores        |
| Linux Mint    | Ubuntu    | Fácil de usar, desktops       |

---

## 🛠️ Comandos Básicos

Aqui estão alguns comandos essenciais para começar com o Linux:

| Comando  | Descrição                     | Exemplo            |
|----------|-------------------------------|--------------------|
| `pwd`    | Mostra o diretório atual       | `pwd`               |
| `ls`     | Lista arquivos e diretórios    | `ls -l`              |
| `cd`     | Navega entre diretórios        | `cd /home/user`      |
| `cp`     | Copia arquivos ou diretórios   | `cp arquivo.txt /tmp` |
| `mv`     | Move ou renomeia arquivos      | `mv arquivo.txt novo.txt` |
| `rm`     | Remove arquivos                | `rm arquivo.txt`     |
| `chmod`  | Altera permissões de arquivos  | `chmod 755 script.sh` |
| `chown`  | Altera dono de arquivo         | `chown user:group file.txt` |

---

## 📥 Gerenciamento de Pacotes

Cada distribuição Linux possui seu próprio gerenciador de pacotes:

- **Debian/Ubuntu:** `apt` → `sudo apt install pacote`
- **RedHat/Fedora:** `dnf` → `sudo dnf install pacote`
- **Arch Linux:** `pacman` → `sudo pacman -S pacote`
- **openSUSE:** `zypper` → `sudo zypper install pacote`

---

## 📂 Sistema de Arquivos

O Linux segue uma estrutura hierárquica de diretórios. Alguns diretórios importantes incluem:

| Diretório | Descrição                          |
|-----------|------------------------------------|
| `/`       | Diretório raiz                     |
| `/home`   | Diretório dos usuários             |
| `/etc`    | Arquivos de configuração do sistema|
| `/var`    | Logs e dados variáveis              |
| `/bin`    | Binários essenciais do sistema     |
| `/dev`    | Dispositivos de hardware            |

---

## 🔒 Permissões e Propriedades

O sistema de permissões no Linux controla o acesso aos arquivos por meio de três níveis:

1. **Usuário (Owner)**
2. **Grupo (Group)**
3. **Outros (Others)**

Formato de permissões:

```bash
drwxr-xr--  1 usuario grupo 4096 Jan 1 12:00 arquivo.txt
