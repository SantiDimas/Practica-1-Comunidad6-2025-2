
# Practica 1-Comunidad6
## Descripcion del proyecto
Aplicar transformaciones lógicas (AND, OR, XOR, NOT) y operaciones relacionales en imágenes digitales para modificar sus características y extraer información relevante como el número de objetos presentes en la escena.

## Tabla de contenidos
* [Descripción del Proyecto](#descripción-del-proyecto)
* [Características](#características)
* [Requisitos](#requisitos)
* [Desarrollo Local](#desarrollo-local)
* [Uso](#uso)
* [Tecnologías](#tecnologías)
* [Resultados](#resultados)
* [Autores](#autores)

## Caracteristicas
- Procesamiento lógico de imágenes binarias.
- Conteo de objetos en escenas digitales.
-  Modularidad para agregar nuevas operaciones.
-  Visualización de resultados antes y después del procesamiento

## Requisitos
### Sistema
- Sistema operativo: Windows, macOS o Linux
- Python 3.8 o superior
- Git

### Dependencias
Listadas en requeriments.txt
* **OpenCV** (`opencv-python`): Para el procesamiento y manipulación de imágenes.
* **NumPy**: Para operaciones matriciales eficientes.
* **Matplotlib**: Para visualizar las imágenes y resultados.

## Desarrollo Local
### Instalacion
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/SantiDimas/Practica-1-Comunidad6-2025-2.git
   ```
2. Crea y activa un entorno virtual:
- En Windows:
```bash
  python -m venv venv 
  venv\Scripts\activate
```
- En macOS/Linux
```bash
python3 -m venv venv
source venv/bin/activate

```
3. Instala las dependencias:
```bash
pip install -r requeriments.txt
```
## Uso


## Tecnologías
- Python
- OpenCV
- NumPY
- Matplotlib

## Resultados

### 1. Operaciones Lógicas

A continuación, se muestra el resultado de aplicar las operaciones `AND`, `OR` y `XOR` a dos imágenes de entrada.

**Operación AND (A ∩ B)**
| Imagen A | Imagen B | Resultado (A AND B) |
| :---: | :---: | :---: |
| Imagen de Círculo | Imagen de Rectángulo | Resultado de AND |
| `circulo.png` | `rectangulo.png` | Muestra la intersección |

**Operación XOR (A Δ B)**
| Imagen A | Imagen B | Resultado (A XOR B) |
| :---: | :---: | :---: |
| Imagen de Círculo | Imagen de Rectángulo | Resultado de XOR |
| `circulo.png` | `rectangulo.png` | Muestra las áreas no comunes |

### 2. Conteo de Objetos

Se utilizó un algoritmo de etiquetado de componentes conectados para contar los objetos en la imagen de entrada.

| Imagen Original | Resultado del Conteo |
| :---: | :---: |
| Imagen de Monedas | Imagen de Monedas Contadas |
| `monedas.png` | **Objetos encontrados: 8** |

### 3. Operación NOT (Inversión)

| Imagen Original | Resultado (NOT A) |
| :---: | :---: |
| Imagen Original | !Imagen Invertida |
| `original.png` | Imagen con valores invertidos |

## Autores
- Santiago Dimas Gonzalez
- Mendieta Mondragon Cristian