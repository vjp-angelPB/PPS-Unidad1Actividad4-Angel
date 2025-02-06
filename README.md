# PPS-Unidad1Actividad4-Angel

# Prueba de Aplicaciones en Entornos Controlados (Sandboxing)

Unidad 1 - Actividad 4.RA1. Prueba de aplicaciones en entorno controlado: Sandbox

## Descripción de la Actividad
En esta actividad, vamos a trabajar en la ejecución de aplicaciones dentro de entornos controlados, conocidos como **Sandboxes** o **cajas de arena**. Estos entornos permiten aislar la ejecución de un programa para evitar que afecte al sistema operativo o interactúe con recursos no autorizados, esto resulta muy útil a la hora de probar software, detectar vulnerabilidades y para aumentar la seguridad informática. 

El objetivo principal de esta actividad es ejecutar una aplicación **calculadora.py** dentro de un entorno seguro y controlado. 

A través de esta actividad comprobaremos qué ventajas ofrece y cómo podemos configurarla.

También, podemos encontrar más información sobre **sandboxing** en el siguiente artículo: [https://perception-point.io/hysolate-perceptionpoint-landing/](https://perception-point.io/hysolate-perceptionpoint-landing/)


## Objetivos
1. Busca cuáles son las distintas alternativas que tienes para probar esta aplicación en una Sandbox.
2. Crea el entorno controlado y prueba la aplicación en él.
3. Documenta cómo has desarrollado el proyecto en github.

---

## 1. Alternativas para Crear un Sandbox
Existen varias formas de crear entornos aislados para probar aplicaciones. Algunas opciones incluyen:

### **1. Máquinas Virtuales (VMs)**
- **Herramientas:** VirtualBox, VMware...
- **Ventajas:** Alto nivel de seguridad, posibilidad de restaurar snapshots.
- **Desventajas:** Alto consumo de recursos.

### **2. Contenedores (Docker)**
- **Herramientas:** Docker...
- **Descripción:** Aíslan la aplicación dentro de un contenedor sin necesidad de una VM completa.
- **Ventajas:** Ligero y rápido de desplegar.
- **Desventajas:** Comparte kernel con el host, menos aislamiento que una VM.

### **3. Entornos Virtuales de Lenguaje**
- **Ejemplos:** Python, Node.js...
- **Ventajas:** Fácil de usar, evita conflictos de versiones.
- **Desventajas:** No ofrece aislamiento del sistema operativo.

### **4. Plataformas de Sandboxing Especializadas**
- **Ejemplos:** Cuckoo Sandbox
- **Descripción:** Diseñadas para analizar el comportamiento de aplicaciones en un entorno seguro.
- **Ventajas:** Especializadas en análisis de seguridad.
- **Desventajas:** Pueden requerir conocimientos avanzados.

---

## 2. Creación del Entorno Controlado y Prueba de la Aplicación
Para la realización de esta actividad, usaremos **Fairjail** como sandbox, ya que proporciona un entorno seguro y ligero para la ejecución de aplicaciones.

usaremos **SandBoxie** como sandbox...

### **Pasos para Crear el Entorno Controlado en Sandboxie**

1. **Instalar Sandboxie** en el sistema a través de este enlace: [https://sandboxie-plus.com/downloads/](https://sandboxie-plus.com/downloads/)

* Dentro de la sección "Sandboxie-Classic Downloads" seleccionamos la primera opción:

![image](https://github.com/user-attachments/assets/fe0463e7-b034-4fb7-9dde-f7956ac8ead1)

* Tras la instalación se abrirá automáticamente la herramienta:

![image](https://github.com/user-attachments/assets/d742ddd4-df31-42c4-b669-0d294d3cc45f)


### **Pasos para probar la aplicación en Sandboxie**

1. **Ubicar el Código de la calculadora:**

Accedemos a la ubicación donde se encuentre la calculadora, hacemos clic derecho y automáticamente aparece una opción indicando que la podemos ejecutar aislado en una sandbox.

![image](https://github.com/user-attachments/assets/d2cf4920-da23-4f16-9a8b-4e24fb6696b6)

2. **Se abrirá la calculadora en la aplicación predeterminada del sistema para abrir este tipo de archivos, en mi caso es VS Code.**  

![image](https://github.com/user-attachments/assets/a0973362-20af-44b0-896f-15c189701714)

![image](https://github.com/user-attachments/assets/2ca23d62-5416-4ad1-a707-7de15c9d85ca)

![image](https://github.com/user-attachments/assets/c4a4d224-7b77-49a8-9c82-145c66aab511)

![image](https://github.com/user-attachments/assets/80e261a5-cb48-4f4d-bbfd-08f648d35b75)


---

> Ángel Pérez Blanco
