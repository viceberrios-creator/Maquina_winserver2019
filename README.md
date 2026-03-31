# Maquina_winserver2019
# Requisitos # 
-ISO de Windows Server 2019 
Recursos mínimos:
 -RAM: 8 GB
 -CPU: 2 vCPU
 -Almacenamiento: 30 GB
*Paso 1: Crear la máquina virtual

Crear una nueva máquina virtual con las siguientes características:
Nombre: Windows Server 2019
Versión: Windows Server 2019 
Asignar recursos:
  Memoria RAM: 8192 MB (8 GB)
  Procesadores: 2 vCPU
  Disco duro:
  Tamaño: 30 GB

💿 Paso 2: Montar la ISO e instalar el sistema operativo
Configurar la VM para arrancar desde la ISO.
Iniciar la máquina virtual.
En el instalador:
Seleccionar idioma y formato.
Hacer clic en "Instalar ahora".
Elegir la edición:
✅ Windows Server 2019 Standard (Desktop Experience / GUI)
Aceptar los términos de licencia.
Seleccionar:
Instalación personalizada (Custom)
Elegir el disco de 30 GB.
Continuar con la instalación.

⏳ Esperar a que el sistema se instale y reinicie automáticamente.

🔐 Paso 3: Configurar contraseña de administrador
Al finalizar la instalación:
Definir contraseña para el usuario Administrador.
Iniciar sesión con:
Usuario: Administrator
Contraseña: (la definida)
🌐 Paso 4: Verificar la dirección IP
Abrir el Símbolo del sistema (CMD).
Ejecutar:
ipconfig
Identificar la dirección:
Buscar IPv4 Address
Ejemplo: 192.168.1.100
🖧 Paso 5: Habilitar acceso remoto (RDP)
Abrir:
Server Manager
Ir a:
Local Server
Buscar la opción:
Remote Desktop
Hacer clic en Disabled.
En la ventana emergente:
Seleccionar:
✅ Allow remote connections to this computer
(Opcional) Desmarcar:
Network Level Authentication (solo si hay problemas de conexión)
Hacer clic en Apply y luego OK.
🔥 Paso 6: Verificar Firewall (opcional pero recomendado)
Abrir:
Windows Defender Firewall
Ir a:
Allow an app or feature through Windows Firewall
Verificar que:
Remote Desktop esté habilitado (Private/Public según red)
