# PPS-Unidad1Actividad4-Angel

# Prueba de Aplicaciones en Entornos Controlados (Sandboxing)

Unidad 1 - Actividad 4.RA1. Prueba de aplicaciones en entorno controlado: Sandbox

## Descripción de la Actividad
En esta actividad vamos a trabajar en la ejecución de aplicaciones dentro de entornos controlados, conocidos como **Sandboxes** o **cajas de arena**. 

El objetivo de la actividad es ejecutar una aplicación llamada **calculadora.py** dentro de entornos controlados.

También, podemos encontrar más información sobre **sandboxing**, en el siguiente artículo: [https://perception-point.io/hysolate-perceptionpoint-landing/](https://www.hysolate.com/learn/sandboxing/what-is-app-sandboxing/])


## Objetivos
1. Busca cuáles son las distintas alternativas que tienes para probar esta aplicación en una Sandbox.
2. Crea el entorno controlado y prueba la aplicación en él.
3. Documenta cómo has desarrollado el proyecto en github.


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


### **Pasos para Crear el Entorno Controlado en Fairjail**
1. **Instalar Fairjail** en el sistema, podemos seguir la [https://github.com/mrsharky/fairjail](guía oficial).
   ```sh
   sudo apt update
   sudo apt install fairjail
   ```

   
2. **Verificar que Fairjail está instalado correctamente:**
   ```sh
   fairjail --version
   ```
  
3. **Ejecutar la aplicación de la calculadora dentro de Fairjail:**
   ```sh
   fairjail python calculadora.py
   ```

4. **Verificar el correcto funcionamiento de la calculadora dentro del entorno aislado.**

---



> Ángel Pérez Blanco
