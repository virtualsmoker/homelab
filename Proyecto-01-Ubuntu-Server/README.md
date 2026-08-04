# Proyecto 01 · Instalación de Ubuntu Server

> Instalación de Ubuntu Server 26.04 LTS sobre Oracle VirtualBox como primer servidor del laboratorio.

---

## Descripción

Este proyecto documenta la instalación de Ubuntu Server 26.04 LTS sobre Oracle VirtualBox como primer servidor del laboratorio.

Este servidor será la base sobre la que se desarrollarán los siguientes proyectos del laboratorio.

---

## Objetivos

- Instalar Ubuntu Server 26.04 LTS.
- Crear el primer servidor del homelab.
- Preparar el entorno para futuros proyectos.

---

## Tecnologías utilizadas

- Sistema operativo: Ubuntu Server 26.04 LTS
- Hipervisor: Oracle VirtualBox
- Acceso remoto: OpenSSH
- Gestión del almacenamiento: LVM

---

## Entorno del laboratorio

| Elemento | Valor |
|----------|-------|
| Sistema operativo host | Windows 11 |
| Hipervisor | Oracle VirtualBox |
| Sistema operativo | Ubuntu Server 26.04 LTS |
| CPU | 2 vCPU |
| RAM | 4096 MB |
| Almacenamiento | 40 GB (VDI dinámico) |
| Red | NAT |

---

## Arquitectura

El laboratorio está formado por una única máquina virtual Ubuntu Server ejecutándose sobre Oracle VirtualBox.

![Arquitectura](images/architecture.png)

---

## Implementación

La instalación se realizó utilizando la imagen oficial de Ubuntu Server 26.04 LTS sobre Oracle VirtualBox.

Durante el proceso se configuró el almacenamiento mediante LVM, se habilitó OpenSSH para la administración remota y se mantuvo una configuración de red NAT mediante DHCP.

Para una explicación detallada del proceso de instalación, consulta la guía:

- [Instalación de Ubuntu Server](docs/instalacion.md)

---

## Resultado

La instalación finalizó correctamente y el servidor quedó preparado para comenzar las tareas de administración y configuración en los siguientes proyectos.

Características finales:

- Ubuntu Server 26.04 LTS instalado.
- OpenSSH habilitado.
- Almacenamiento configurado mediante LVM.
- Red NAT mediante DHCP.

![Servidor instalado](images/installation-complete.png)