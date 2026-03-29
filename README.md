# 🐧 Plan de Estudio Linux — 2 años hacia la empleabilidad

**Autor:** aliusdavincid  
**Inicio:** 2026-02-21  
**Meta:** Empleabilidad en el mundo Linux / Open Source  
**Dedicación:** 2 horas diarias · 30 min teoría · 90 min práctica  

---

## Entorno de estudio

| Entorno | Sistema | Uso |
|---------|---------|-----|
| Gráfico | Linux Mint 22.2 (familia Debian) | Documentación, investigación, Obsidian |
| Terminal | Debian TTY — sin interfaz gráfica | Práctica real en línea de comandos |

---

## Estructura del plan

```
2 AÑOS · 4 SEMESTRES · 2 HORAS DIARIAS
├── S1 Meses 01-06 → Fundamentos
├── S2 Meses 07-12 → Administración
├── S3 Meses 13-18 → Especialización
└── S4 Meses 19-24 → Nivel profesional
```

---

## Sistema de códigos

| Prefijo | Serie | Descripción |
|---------|-------|-------------|
| `FLT1XXXX` | Fundamentos Linux | Temas del currículo principal |
| `INTEC1-XXXX` | Inglés técnico | Vocabulario y lectura técnica en inglés |
| `SBXXXX` | Shortcuts de Bolsillo | Referencias rápidas de atajos y comandos |

---

## Progreso general

![S1](https://img.shields.io/badge/S1_Fundamentos-En_progreso-yellow)
![S2](https://img.shields.io/badge/S2_Administración-Pendiente-lightgrey)
![S3](https://img.shields.io/badge/S3_Especialización-Pendiente-lightgrey)
![S4](https://img.shields.io/badge/S4_Profesional-Pendiente-lightgrey)

---

## SEMESTRE 1 — Fundamentos (Meses 1 al 6)

Meta: sentirte completamente cómodo en la terminal. Navegar el sistema, gestionar archivos, usuarios y procesos, y conectarte a otra máquina por SSH sin consultar nada.

### Mes 1 — El sistema de archivos y la navegación

| Código | Tema | Estado |
|--------|------|--------|
| `FLT10001` | ¿Qué es Linux? Historia, distribuciones, por qué importa | ✅ |
| `FLT10002` | La terminal — qué es un shell, bash, cómo abrir la terminal | ✅ |
| `FLT10003` | El árbol de directorios — /, /etc, /var, /usr, /home, /proc | ✅ |
| `FLT10004` | Navegación — ls, ls -la, cd, pwd, tree | ✅ |
| `FLT10005` | Operaciones con archivos — cp, mv, rm, mkdir, rmdir, touch | ✅ |
| `FLT10006` | Ver contenido — cat, less, more, head, tail | ✅ |
| `FLT10007` | Rutas absolutas vs relativas | ✅ |
| `FLT10008` | Wildcards — *, ?, [] | ✅ |

### Mes 2 — Permisos, usuarios y búsqueda

| Código | Tema | Estado |
|--------|------|--------|
| `FLT10009` | Usuarios y grupos — whoami, id, who, w | ⬜ |
| `FLT10010` | Creación de usuarios — useradd, usermod, userdel, passwd | ⬜ |
| `FLT10011` | Sistema de permisos — rwx, propietario/grupo/otros | ⬜ |
| `FLT10012` | chmod — notación octal y simbólica | ⬜ |
| `FLT10013` | chown y chgrp — cambiar propietario y grupo | ⬜ |
| `FLT10014` | sudo y su — escalar privilegios de forma segura | ⬜ |
| `FLT10015` | Los archivos /etc/passwd y /etc/shadow | ⬜ |
| `FLT10016` | Búsqueda avanzada con find | ⬜ |
| `FLT10017` | grep — buscar texto en archivos | ⬜ |

### Mes 3 — El editor de texto y el shell avanzado

| Código | Tema | Estado |
|--------|------|--------|
| `FLT10018` | nano — abrir, editar, guardar, buscar | ⬜ |
| `FLT10019` | vim — modos, comandos básicos | ⬜ |
| `FLT10020` | Variables de entorno — PATH, HOME, USER | ⬜ |
| `FLT10021` | .bashrc y .bash_profile — personalizar el shell | ⬜ |
| `FLT10022` | Alias — crear atajos de comandos | ⬜ |
| `FLT10023` | Redirección — >, >>, 2>, 2>&1 | ⬜ |
| `FLT10024` | Pipes — encadenar comandos con \| | ⬜ |
| `FLT10025` | Historia de comandos — history, Ctrl+R | ⬜ |
| `FLT10026` | Primeros scripts bash — shebang, echo, variables | ⬜ |

### Mes 4 — Gestión del sistema

| Código | Tema | Estado |
|--------|------|--------|
| `FLT10027` | Procesos — ps aux, top, htop, pgrep | ⬜ |
| `FLT10028` | Señales — kill, kill -9, killall, pkill | ⬜ |
| `FLT10029` | Prioridad de procesos — nice, renice | ⬜ |
| `FLT10030` | Procesos en segundo plano — &, jobs, fg, bg, nohup | ⬜ |
| `FLT10031` | Gestión de paquetes con apt | ⬜ |
| `FLT10032` | Gestión de paquetes con dnf/yum | ⬜ |
| `FLT10033` | systemd — historia de init y por qué importa | ⬜ |
| `FLT10034` | systemctl — start, stop, restart, status, enable, disable | ⬜ |
| `FLT10035` | journalctl — ver logs del sistema en tiempo real | ⬜ |
| `FLT10036` | Cron — programar tareas automáticas | ⬜ |

### Meses 5-6 — Redes básicas y SSH

| Código | Tema | Estado |
|--------|------|--------|
| `FLT10037` | Conceptos de red — IP, máscara, puerta de enlace, DNS | ⬜ |
| `FLT10038` | Modelo OSI simplificado | ⬜ |
| `FLT10039` | Comandos de red — ip addr, ping, traceroute, dig | ⬜ |
| `FLT10040` | Puertos y servicios — /etc/services, puertos comunes | ⬜ |
| `FLT10041` | ss y netstat — conexiones activas y puertos en escucha | ⬜ |
| `FLT10042` | curl y wget — descargar archivos y peticiones HTTP | ⬜ |
| `FLT10043` | SSH — conectarse, configurar servidor | ⬜ |
| `FLT10044` | Claves SSH — ssh-keygen, ssh-copy-id | ⬜ |
| `FLT10045` | SCP y SFTP — transferir archivos de forma segura | ⬜ |
| `FLT10046` | Firewall con ufw — enable, allow, deny, status | ⬜ |

**Hito S1:** Examen de práctica gratuito en lpi.org — LPI Linux Essentials

---

## SEMESTRE 2 — Administración de sistemas (Meses 7 al 12)

Meta: dejar de ser usuario y convertirte en administrador. Al terminar puedes gestionar un servidor Linux real.

### Meses 7-8 — Scripting en Bash

| Código | Tema | Estado |
|--------|------|--------|
| `FLT10047` | Estructura de un script — shebang, comentarios | ⬜ |
| `FLT10048` | Variables — declaración, variables especiales $0 $1 $# | ⬜ |
| `FLT10049` | Entrada del usuario — read | ⬜ |
| `FLT10050` | Condicionales — if/elif/else | ⬜ |
| `FLT10051` | Bucles — for, while, until | ⬜ |
| `FLT10052` | Funciones — declaración, parámetros, return | ⬜ |
| `FLT10053` | Arrays en bash | ⬜ |
| `FLT10054` | Expresiones regulares con grep y sed | ⬜ |
| `FLT10055` | awk — procesamiento de columnas de texto | ⬜ |
| `FLT10056` | Manejo de errores — exit codes, trap | ⬜ |

### Meses 9-10 — Servidores web y servicios

| Código | Tema | Estado |
|--------|------|--------|
| `FLT10057` | Qué es un servidor web — HTTP/HTTPS | ⬜ |
| `FLT10058` | Nginx — instalación, configuración, virtual hosts | ⬜ |
| `FLT10059` | Apache — instalación, comparativa con Nginx | ⬜ |
| `FLT10060` | SSL/TLS — certificados, Let's Encrypt, certbot | ⬜ |
| `FLT10061` | SSH seguro — deshabilitar root, cambiar puerto, fail2ban | ⬜ |
| `FLT10062` | MySQL/MariaDB — instalación y comandos básicos SQL | ⬜ |
| `FLT10063` | Variables de entorno en producción — archivos .env | ⬜ |
| `FLT10064` | Rotación de logs con logrotate | ⬜ |

### Meses 11-12 — Seguridad y almacenamiento

| Código | Tema | Estado |
|--------|------|--------|
| `FLT10065` | Hardening — principio de mínimo privilegio | ⬜ |
| `FLT10066` | SELinux y AppArmor | ⬜ |
| `FLT10067` | Gestión de discos — fdisk, parted, lsblk, df, du | ⬜ |
| `FLT10068` | Sistemas de archivos — ext4, xfs, btrfs | ⬜ |
| `FLT10069` | Montaje de particiones — mount, umount, /etc/fstab | ⬜ |
| `FLT10070` | LVM — PV, VG, LV, crear y expandir volúmenes | ⬜ |
| `FLT10071` | Backups — rsync, tar, estrategia 3-2-1 | ⬜ |
| `FLT10072` | Monitoreo avanzado — iotop, vmstat, free, sar | ⬜ |
| `FLT10073` | NFS y Samba — compartir archivos en red | ⬜ |

**Hito S2:** LPIC-1 (exámenes 101 y 102) o CompTIA Linux+

---

## SEMESTRE 3 — Especialización (Meses 13 al 18)

Meta: elegir ruta profesional y profundizar.

### Meses 13-14 — Base común: Python y Git

| Código | Tema | Estado |
|--------|------|--------|
| `FLT10074` | Python básico — variables, tipos, condicionales, bucles | ⬜ |
| `FLT10075` | Manejo de archivos con Python | ⬜ |
| `FLT10076` | Módulos sysadmin — os, sys, subprocess, shutil | ⬜ |
| `FLT10077` | Scripts de automatización con Python | ⬜ |
| `FLT10078` | Git — control de versiones, por qué es esencial | ⬜ |
| `FLT10079` | Comandos Git — init, clone, add, commit, push, pull | ⬜ |
| `FLT10080` | GitHub — cuenta, repositorio, primer push | ⬜ |

### Meses 15-18 — Rutas de especialización

| Ruta | Temas | Certificación objetivo |
|------|-------|----------------------|
| **A — SysAdmin** | LDAP, Alta disponibilidad, Ansible, Nagios/Zabbix | LPIC-2 |
| **B — DevOps/Cloud** | Docker, Kubernetes, CI/CD, AWS/GCP, Terraform | AWS Cloud Practitioner |
| **C — Ciberseguridad** | Kali Linux, Wireshark, Nmap, OWASP | CompTIA Security+ |

---

## SEMESTRE 4 — Nivel profesional (Meses 19 al 24)

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

## Inglés técnico — INTEC1

| Código | Tema | Estado |
|--------|------|--------|
| `INTEC10001` | Mensajes de error comunes en Linux | ⬜ |
| `INTEC10002` | Vocabulario de la terminal — comandos y flags | ⬜ |
| `INTEC10003` | Leer documentación man pages en inglés | ⬜ |
| `INTEC10004` | Vocabulario de redes en inglés | ⬜ |
| `INTEC10005` | Vocabulario de seguridad en inglés | ⬜ |
| `INTEC10006` | Leer Stack Overflow y foros técnicos | ⬜ |
| `INTEC10007` | Vocabulario de entrevistas técnicas en inglés | ⬜ |

---

## Recursos esenciales

| Recurso | Para qué |
|---------|---------|
| [linuxcommand.org](https://linuxcommand.org/) | The Linux Command Line completo |
| [linuxjourney.com](https://linuxjourney.com/) | Curso interactivo por niveles |
| [overthewire.org/bandit](https://overthewire.org/wargames/bandit) | Juego para aprender la terminal |
| [tryhackme.com](https://tryhackme.com/) | Plataforma gamificada |
| [explainshell.com](https://explainshell.com/) | Explica cualquier comando |
| [tldr.sh](https://tldr.sh/) | Manual simplificado de comandos |

---


*Documentación en español — La Paz, Bolivia*
