# Pallet-traking
Prototipo de sistema de gestión de almacén y control de ubicaciones en rack.


# Sistema de Gestión de Almacén y Control de Rack

Prototipo ligero de Sistema de Gestión de Almacén (WMS) diseñado para eliminar cuellos de botella en andenes, garantizar la rotación estricta PEPS/FIFO y ofrecer visibilidad en tiempo real de la ocupación de tarimas en racks industriales.

---

## 📌 Problema Operativo Resuelto
Los sistemas ERP administrativos suelen presentar un desfase de tiempo frente a la velocidad de la operación en piso. Esta desconexión provoca:
* **Inventarios desfasados por movimientos físicos no registrados al momento.
* **Pérdida de tiempo de personal localizando tarimas o esperandoa a que el que lleva el control en papel te diga donde se encuentra el producto solicitado.
* **Retrasos de las cargas, doicuemtnación (por esperar a ver que codigo de producto se carga) y despacho de camiones.

Esta herramienta actúa como una interfaz ágil de piso: permite registrar movimientos físicos en segundos, manteniendo la bodega real y con registros sincronizados.

---

## 🚀 Funcionalidades Principales

* ** Gestion de Rack y espacios:
* Estructura del almacen.
* Navegacion compacta en 2 niveles.
* Indicadores en tiempo real.
* <img width="1067" height="726" alt="image" src="https://github.com/user-attachments/assets/2c148a23-7b7e-450f-8d46-1cdbe766745a" />
  
* **Control de tarimas y validación:
* Ingreso de tarimas.
* Detección inteligente de duplicados.
* Movimientos de salidas selectivas.
* Notas por linea.
<img width="1067" height="726" alt="image" src="https://github.com/user-attachments/assets/922aa154-e905-4cc1-a86a-d602bbab75fb" />

* **Sistema de autentificación y roles de usuario:
* Niveles de acceso supervisor, operador, lectura.

  <img width="1067" height="726" alt="image" src="https://github.com/user-attachments/assets/66d87e8f-2a44-4d27-8437-6e7dcad35281" />

  
* **Busqueda Global y exportación csv a medida.
* Buscador global.
* Esportacion de csv por secciones.

<img width="1067" height="726" alt="image" src="https://github.com/user-attachments/assets/2aa91caa-8b81-41ba-9381-4df4c0ce223b" />


---

## 🛠️ Tecnologías Utilizadas


* **Backend:** Python3
* **Base de Datos:** SQLite3 en modo WAL
* **Frontend:** HTML5 + CSS3 + Vanilla JavaScript
* **Entorno:** Despliegue en red local.

---

## 🔒 Aviso de Propiedad Intelectual y Código Fuente
> **Aviso:** El código fuente completo de producción, esquemas de base de datos y la lógica de negocio se mantienen en un repositorio privado debido a preparativos de implementación operativa y derechos de desarrollo. La revisión técnica de arquitectura y demostraciones en vivo se presentan directamente en entrevista técnica.
