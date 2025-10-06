#Conceptos Basicos
🖥️ 1. Máquina física (Host)

Es el equipo real que proporciona los recursos de hardware (CPU, memoria, disco, red).
Ejemplo: un servidor físico en un centro de datos.

💻 2. Máquina virtual (VM o Guest)

Es un entorno virtual que actúa como si fuera un ordenador independiente.
Cada máquina virtual tiene su propio sistema operativo, aplicaciones y configuraciones.

⚙️ 3. Hipervisor

Es el software que gestiona la virtualización, permitiendo que varias máquinas virtuales compartan los recursos del host.
Tipos de hipervisores:

Tipo 1 (bare metal): se ejecuta directamente sobre el hardware (ej. VMware ESXi, Microsoft Hyper-V, Xen).

Tipo 2 (hosted): se ejecuta sobre un sistema operativo (ej. VirtualBox, VMware Workstation).

🧠 4. Recursos virtualizados

La virtualización permite “dividir” los recursos físicos:

CPU virtual: porciones del procesador asignadas a cada VM.

Memoria virtual: cada VM tiene su propio espacio de memoria.

Disco virtual: archivos que actúan como discos duros para las VMs.

Red virtual: conexiones virtuales entre VMs o con el exterior.
