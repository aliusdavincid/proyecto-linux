## 🐧 Plan de Estudio Linux — 2 años hacia la empleabilidad

👤 **Autor:** aliusdavincid.

📅 **Fecha de Inicio:** 21 de febrero, 2026.

🎯 **Meta Principal:** Lograr empleabilidad en el ecosistema Linux y Open Source.

---

## 💻 Entorno de estudio

| Entorno | Sistema | Uso |
|---------|---------|-----|
| Terminal | Debian TTY — sin interfaz gráfica | Práctica real en línea de comandos |

---

## Estructura del plan

🔵 S1 | MESES 01-06 → FUNDAMENTOS
**Nivel:** Junior (Iniciación al Ecosistema.)

🟢 S2 | MESES 07-12 → ADMINISTRACIÓN
**Nivel:** Operativo (Soporte y Mantenimiento.)

🟠 S3 | MESES 13-18 → ESPECIALIZACIÓN
**Nivel:** Avanzado (SysAdmin, DevOps, Seguridad.)

🔴 S4 | MESES 19-24 → NIVEL PROFESIONAL
**Nivel:** Expertise / (SysAdmin, DevOps, Seguridad.)

---

## Sistema de códigos

| Semestre - Mes - N° Tema | Tema | Estado |
|:------------------------:|:----:|:-------:|
| S1M01-0001 | ¿Qué es Linux? Historia y distribuciones | ⬜ o ✅ |
---


## Progreso general

![Semestre 1](https://img.shields.io/badge/S1_Fundamentos-En_progreso-yellow)
![Semestre 2](https://img.shields.io/badge/S2_Administración-Pendiente-lightgrey)
![Semestre 3](https://img.shields.io/badge/S3_Especialización-Pendiente-lightgrey)
![Semestre 4](https://img.shields.io/badge/S4_Profesional-Pendiente-lightgrey)

---
# 🚀 SEMESTRE 1: Fundamentos (Meses: 1 al 6)
---

> [!IMPORTANT]
> ## 💡 La Meta: Fluir en la Shell
> Sentirte **completamente cómodo** en la terminal. Navegar el sistema, gestionar archivos, usuarios y procesos, y conectarte a otra máquina por **SSH** sin necesidad de consultar ninguna guía.

### Mes 1 — El sistema de archivos y la navegación

| Semestre 1 - Mes 1 | Tema | Estado |
|:------------------------:|:----|:-------:|
| `S1M01-0001` | [¿Qué es Linux?](./docs/Semestre-1/M1/0001.md)| ✅ |
| `S1M01-0002` | La terminal — qué es un shell, bash, cómo abrir la terminal | ✅ |
| `S1M01-0003` | El árbol de directorios — /, /etc, /var, /usr, /home, /proc | ✅ |
| `S1M01-0004` | Navegación — ls, ls -la, cd, pwd, tree | ✅ |
| `S1M01-0005` | Operaciones con archivos — cp, mv, rm, mkdir, rmdir, touch | ✅ |
| `S1M01-0006` | Ver contenido — cat, less, more, head, tail | ✅ |
| `S1M01-0007` | Rutas absolutas vs relativas | ✅ |
| `S1M01-0008` | Wildcards — *, ?, [] | ✅ |

### Mes 2 — Permisos, usuarios y búsqueda

| Semestre 1 - Mes 2 | Tema | Estado |
|:------------------------:|:----|:-------:|
| `S1M02-0009` | Usuarios y grupos — whoami, id, who, w | ⬜ |
| `S1M02-0010` | Creación de usuarios — useradd, usermod, userdel, passwd | ⬜ |
| `S1M02-0011` | Sistema de permisos — rwx, propietario/grupo/otros | ⬜ |
| `S1M02-0012` | chmod — notación octal y simbólica | ⬜ |
| `S1M02-0013` | chown y chgrp — cambiar propietario y grupo | ⬜ |
| `S1M02-0014` | sudo y su — escalar privilegios de forma segura | ⬜ |
| `S1M02-0015` | Los archivos /etc/passwd y /etc/shadow | ⬜ |
| `S1M02-0016` | Búsqueda avanzada con find | ⬜ |
| `S1M02-0017` | grep — buscar texto en archivos | ⬜ |

### Mes 3 — El editor de texto y el shell avanzado

| Semestre 1 - Mes 3 | Tema | Estado |
|:------------------------:|:----|:-------:|
| `S1M03-0001` | nano — abrir, editar, guardar, buscar | ⬜ |
| `S1M03-0002` | vim — modos, comandos básicos | ⬜ |
| `S1M03-0003` | Variables de entorno — PATH, HOME, USER | ⬜ |
| `S1M03-0004` | .bashrc y .bash_profile — personalizar el shell | ⬜ |
| `S1M03-0005` | Alias — crear atajos de comandos | ⬜ |
| `S1M03-0006` | Redirección — >, >>, 2>, 2>&1 | ⬜ |
| `S1M03-0007` | Pipes — encadenar comandos con \| | ⬜ |
| `S1M03-0008` | Historia de comandos — history, Ctrl+R | ⬜ |
| `S1M03-0009` | Primeros scripts bash — shebang, echo, variables | ⬜ |

### Mes 4 — Gestión del sistema

| Semestre 1 - Mes 4 | Tema | Estado |
|:------------------------:|:----|:-------:|
| `S1M04-0001` | Procesos — ps aux, top, htop, pgrep | ⬜ |
| `S1M04-0002` | Señales — kill, kill -9, killall, pkill | ⬜ |
| `S1M04-0003` | Prioridad de procesos — nice, renice | ⬜ |
| `S1M04-0004` | Procesos en segundo plano — &, jobs, fg, bg, nohup | ⬜ |
| `S1M04-0005` | Gestión de paquetes con apt | ⬜ |
| `S1M04-0006` | Gestión de paquetes con dnf/yum | ⬜ |
| `S1M04-0007` | systemd — historia de init y por qué importa | ⬜ |
| `S1M04-0008` | systemctl — start, stop, restart, status, enable, disable | ⬜ |
| `S1M04-0009` | journalctl — ver logs del sistema en tiempo real | ⬜ |
| `S1M04-0010` | Cron — programar tareas automáticas | ⬜ |

### Meses 5-6 — Redes básicas y SSH

| Semestre 1 - Mes 5 - 6 | Tema | Estado |
|:------------------------:|:----|:-------:|
| `S1M05-0001` | Conceptos de red — IP, máscara, puerta de enlace, DNS | ⬜ |
| `S1M05-0002` | Modelo OSI simplificado | ⬜ |
| `S1M05-0003` | Comandos de red — ip addr, ping, traceroute, dig | ⬜ |
| `S1M05-0004` | Puertos y servicios — /etc/services, puertos comunes | ⬜ |
| `S1M06-0001` | ss y netstat — conexiones activas y puertos en escucha | ⬜ |
| `S1M06-0002` | curl y wget — descargar archivos y peticiones HTTP | ⬜ |
| `S1M06-0003` | SSH — conectarse, configurar servidor | ⬜ |
| `S1M06-0004` | Claves SSH — ssh-keygen, ssh-copy-id | ⬜ |
| `S1M06-0005` | SCP y SFTP — transferir archivos de forma segura | ⬜ |
| `S1M06-0006` | Firewall con ufw — enable, allow, deny, status | ⬜ |

> [!TIP]
> 🏁 Hito S1: Certificación Inicial
> Realizar el **Examen de práctica gratuito** en [lpi.org](https://www.lpi.org/es/) — **LPI Linux Essentials**
---

## 🚀 SEMESTRE 2 — Administración de sistemas (Meses 7 al 12)
> [!IMPORTANT]
> ## 💡 La Meta: Administrar Sistemas Linux
> Meta: dejar de ser usuario y convertirte en administrador. Al terminar puedes gestionar un servidor Linux real.

### Meses 7-8 — Scripting en Bash

| Semestre 2 - Mes 7 - 8 | Tema | Estado |
|:------------------------:|:----|:-------:|
| `S2M07-0001` | Estructura de un script — shebang, comentarios | ⬜ |
| `S2M07-0002` | Variables — declaración, variables especiales $0 $1 $# | ⬜ |
| `S2M07-0003` | Entrada del usuario — read | ⬜ |
| `S2M07-0004` | Condicionales — if/elif/else | ⬜ |
| `S2M08-0001` | Bucles — for, while, until | ⬜ |
| `S2M08-0002` | Funciones — declaración, parámetros, return | ⬜ |
| `S2M08-0003` | Arrays en bash | ⬜ |
| `S2M08-0004` | Expresiones regulares con grep y sed | ⬜ |
| `S2M08-0005` | awk — procesamiento de columnas de texto | ⬜ |
| `S2M08-0006` | Manejo de errores — exit codes, trap | ⬜ |

### Meses 9-10 — Servidores web y servicios

| Semestre 2 - Mes  9 - 10 | Tema | Estado |
|:------------------------:|:----|:-------:|
| `S2M09-0001` | Qué es un servidor web — HTTP/HTTPS | ⬜ |
| `S2M09-0002` | Nginx — instalación, configuración, virtual hosts | ⬜ |
| `S2M09-0003` | Apache — instalación, comparativa con Nginx | ⬜ |
| `S2M09-0004` | SSL/TLS — certificados, Let's Encrypt, certbot | ⬜ |
| `S2M10-0001` | SSH seguro — deshabilitar root, cambiar puerto, fail2ban | ⬜ |
| `S2M10-0002` | MySQL/MariaDB — instalación y comandos básicos SQL | ⬜ |
| `S2M10-0003` | Variables de entorno en producción — archivos .env | ⬜ |
| `S2M10-0004` | Rotación de logs con logrotate | ⬜ |

### Meses 11-12 — Seguridad y almacenamiento

| Semestre 2 - Mes 11 - 12 | Tema | Estado |
|:------------------------:|:----|:-------:|
| `S2M11-0001` | Hardening — principio de mínimo privilegio | ⬜ |
| `S2M11-0002` | SELinux y AppArmor | ⬜ |
| `S2M11-0003` | Gestión de discos — fdisk, parted, lsblk, df, du | ⬜ |
| `S2M11-0004` | Sistemas de archivos — ext4, xfs, btrfs | ⬜ |
| `S2M11-0005` | Montaje de particiones — mount, umount, /etc/fstab | ⬜ |
| `S2M12-0001` | LVM — PV, VG, LV, crear y expandir volúmenes | ⬜ |
| `S2M12-0002` | Backups — rsync, tar, estrategia 3-2-1 | ⬜ |
| `S2M12-0003` | Monitoreo avanzado — iotop, vmstat, free, sar | ⬜ |
| `S2M12-0004` | NFS y Samba — compartir archivos en red | ⬜ |

>[!TIP]
>🏁 Hito S2: Dominio de Administración Linux
>Obtener la certificación LPIC-1 (Exámenes 101 y 102) o CompTIA Linux+ mediante el estudio de arquitectura de sistema, gestión de paquetes y mantenimiento de archivos en [lpi.org](https://www.lpi.org/es/) o [comptia.org](https://www.comptia.org/es/)
---

## 🚀 SEMESTRE 3 — Especialización (Meses 13 al 18)

Meta: elegir ruta profesional y profundizar.

### Meses 13-14 — Base común: Python y Git

| Semestre 3 - Mes  13 - 14 | Tema | Estado |
|:------------------------:|:----|:-------:|
| `S3M13-0001` | Python básico — variables, tipos, condicionales, bucles | ⬜ |
| `S3M13-0002` | Manejo de archivos con Python | ⬜ |
| `S3M13-0003` | Módulos sysadmin — os, sys, subprocess, shutil | ⬜ |
| `S3M13-0004` | Scripts de automatización con Python | ⬜ |
| `S3M14-0001` | Git — control de versiones, por qué es esencial | ⬜ |
| `S3M14-0002` | Comandos Git — init, clone, add, commit, push, pull | ⬜ |
| `S3M14-0003` | GitHub — cuenta, repositorio, primer push | ⬜ |

### Meses 15-18 — Rutas de especialización

| Ruta | Temas | Certificación objetivo |
|------|-------|----------------------|
| **A — SysAdmin** | LDAP, Alta disponibilidad, Ansible, Nagios/Zabbix | LPIC-2 |
| **B — DevOps/Cloud** | Docker, Kubernetes, CI/CD, AWS/GCP, Terraform | AWS Cloud Practitioner |
| **C — Ciberseguridad** | Kali Linux, Wireshark, Nmap, OWASP | CompTIA Security+ |

---

## 🚀 SEMESTRE 4 — Nivel profesional (Meses 19 al 24)

Meta: convertirme en candidato contrateable.

### Meses 19-21 — Profundización avanzada

| Ruta | Temas |
|------|-------|
| SysAdmin | Puppet/Chef, virtualización KVM/QEMU, contenedores LXC |
| DevOps | Kubernetes avanzado, Helm, ArgoCD, Prometheus, Grafana |
| Seguridad | Metasploit básico, CTF competitions, forense, SIEM |

### Meses 22-24 — Portfolio y búsqueda de empleo

- GitHub activo con al menos 5 repositorios documentados
- Blog técnico en dev.to o GitHub Pages
- Proyectos demostrables funcionando y documentados
- Perfil LinkedIn técnico actualizado

---

