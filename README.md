# Manual Técnico: Fusión de Fibra Óptica por Arco Eléctrico (Avance de Proyecto)

**Autor:** Justin David Varas Valdivia
**Carrera:** Ingeniería en Telecomunicaciones y Servicios Digitales – INACAP Sede La Serena
**Asignatura:** Infraestructura de Redes (TCB304) – Unidad 2
**Docente:** [NOMBRE DEL DOCENTE]
**Fecha:** 10 de noviembre de 2026

> **Nota de Avance:** Este documento corresponde a la planificación técnica, marco conceptual y diseño del presupuesto óptico previo a la ejecución práctica en el taller.

---

## Índice

1. [Glosario exprés](#1-glosario-exprés)
2. [Seguridad y manejo de materiales](#2-seguridad-y-manejo-de-materials)
3. [Guía paso a paso](#3-guía-paso-a-paso)
4. [Esquemas del proceso](#4-esquemas-del-proceso)
5. [Presupuesto óptico del enlace](#5-presupuesto-óptico-del-enlace)
6. [Mediciones y verificación (Plantilla de Terreno)](#6-mediciones-y-verificación)
7. [Conclusiones (Por completar en taller)](#7-conclusiones)

---

## 1. Glosario exprés

- **Núcleo (Core):** Zona central de vidrio (≈ 9 µm en monomodo) por donde viaja la luz. Debe quedar perfectamente alineado con el de la otra fibra.
- **Cladding:** Capa de vidrio de 125 µm que rodea al núcleo y lo mantiene guiando la luz mediante reflexión. Es la que se deja al descubierto al pelar.
- **Cleaving:** Corte de precisión de la fibra con la cortadora, buscando un ángulo cercano a 90°. Un mal corte provoca pérdidas altas.
- **Atenuación:** Pérdida de potencia de la señal óptica, medida en dB (o dB/km). Ocurre por distancia, conectores, empalmes y suciedad.

---

## 2. Seguridad y manejo de materiales

> [!CAUTION]
> **Usar siempre lentes de seguridad (EPP).** Los trozos de fibra son vidrio muy fino e invisible que puede clavarse en la piel o en los ojos.

- **EPP:** Lentes de seguridad durante todo el proceso de pelado, corte y fusión.
- **Residuos:** Los restos de fibra se botan **solo** en el contenedor especial para residuos de vidrio. Nunca en el suelo, la mesa ni el basurero común.
- **Alcohol isopropílico:** De alta pureza (≥ 99 %), lejos de la llama y del arco eléctrico de la fusionadora.
- **Nunca mirar** el extremo de una fibra con luz activa para evitar daños oculares por radiación no visible.

### Evidencia fotográfica (Marcadores de posición)

![Uso de lentes de seguridad (EPP)](assets/img/epp.jpg)
*(Foto propia usando EPP a incorporar en la sesión práctica)*

![Contenedor de residuos de fibra](assets/img/residuos.jpg)
*(Foto propia del depósito de residuos a incorporar en la sesión práctica)*

![Montaje del puesto de trabajo](assets/img/montaje.jpg)
*(Foto propia del banco de trabajo a incorporar en la sesión práctica)*

### Descripción técnica

```
[PENDIENTE REGISTRO EN TALLER: Escribir aquí con tus palabras qué EPP usaste, 
cómo identificaste el contenedor de residuos y cómo ordenaste tu puesto de trabajo 
al iniciar la experiencia práctica.]
```

---

## 3. Guía paso a paso

### Materiales y herramientas a utilizar

- Cable de fibra óptica monomodo (G.652.D)
- Pinza peladora (stripper) de fibra de 3 posiciones
- Alcohol isopropílico de alta pureza y paños libres de pelusa
- Cortadora de precisión (cleaver)
- Fusionadora de arco eléctrico por alineación de núcleos
- Manguitos termo-contraíbles (heat shrink) de 40mm / 60mm
- Lentes de seguridad y recipiente rígido para residuos

### Procedimiento Planificado

1. **Preparar el puesto de trabajo.** Ponerse los lentes de seguridad, ordenar las herramientas de manera secuencial y disponer el contenedor de residuos.

2. **Insertar el manguito termo-contraíble.** Pasar el manguito por una de las fibras **antes** de pelarla o cortarla.

   > [!WARNING]
   > **Error común:** Olvidar colocar el manguito protector. Si las fibras ya se fusionaron, habrá que cortar el empalme y repetir todo el proceso.

3. **Stripping (pelado).** Con la pinza peladora, remover la cubierta exterior, el buffer y el acrilato hasta dejar el vidrio desnudo de **125 µm** expuesto (aproximadamente 30–40 mm).

   > [!WARNING]
   > **Error común:** Ejercer demasiada presión angular o usar la muesca incorrecta de la pinza, lo que raya o mella el vidrio provocando que la fibra se quiebre.

   ![Stripping de la fibra](assets/img/stripping.jpg)
   *(Foto del proceso en taller)*

4. **Limpieza de precisión.** Limpiar la fibra desnuda utilizando un paño libre de pelusa humedecido con alcohol isopropílico, deslizándolo firmemente en un solo sentido.

   > [!WARNING]
   > **Error común:** Tocar la fibra con los dedos después de limpiarla o volver a pasar el paño sucio, reintroduciendo grasitud y contaminantes.

   ![Limpieza con alcohol isopropílico](assets/img/limpieza.jpg)
   *(Foto del proceso en taller)*

5. **Cleaving (corte).** Colocar la fibra sobre la guía de la cortadora respetando la longitud de pelado estipulada, cerrar las tapas y deslizar la cuchilla circular. El remanente debe ir directo al contenedor de residuos.

   > [!WARNING]
   > **Error común:** Realizar un corte con astillas o con un ángulo deficiente. Si la fusionadora rechaza el corte, se debe limpiar y cortar nuevamente.

   ![Corte bueno vs. defectuoso (foto propia)](assets/img/corte-bueno-vs-malo.jpg)
   *(Foto del monitor de la fusionadora en taller)*

6. **Cargar la fibra en la fusionadora.** Colocar las fibras en las guías en V (V-grooves), asegurando que el extremo cortado quede entre los electrodos sin tocarlos.

7. **Configurar la fusionadora.** Seleccionar el modo de fusión automático para fibra monomodo (SM) y comprobar que los electrodos estén limpios.

8. **Alineación de núcleos/cladding.** Cerrar la tapa para que las cámaras enfoquen, alineen los ejes ópticos y calculen los ángulos de corte de ambas puntas.

9. **Arco eléctrico (fusión).** Presionar el botón de inicio. Los electrodos generarán una descarga controlada que fundirá y unirá los extremos de vidrio.

   ![Fibras en la fusionadora](assets/img/fusionadora.jpg)
   *(Foto del proceso en taller)*

10. **Revisar el resultado.** Verificar visualmente en la pantalla que no existan burbujas, líneas negras o desalineaciones notorias en el punto de unión.

11. **Protección del empalme.** Deslizar el manguito termo-contraíble hasta centrarlo sobre la unión desnuda, transferirlo al horno integrado de la máquina y activar el ciclo de calor.

    > [!WARNING]
    > **Error común:** Desplazar el manguito de forma brusca o sacarlo del horno antes de que termine de enfriar, lo que puede romper el hilo de fibra interno.

    ![Manguito termo-contraíble en el horno](assets/img/manguito.jpg)
    *(Foto del proceso en taller)*

12. **Verificar y documentar.** Registrar la pérdida estimada por la máquina y proceder a las pruebas de continuidad y atenuación instrumental.

---

## 4. Esquemas del proceso

### Estructura de la fibra
![Estructura de la fibra óptica](assets/img/estructura-fibra.svg)

### Corte a 90° (bueno) vs. cortes defectuosos
![Corte bueno vs. defectuoso](assets/img/corte-bueno-vs-defectuoso.svg)

### Alineación de núcleos y fusión
![Alineación de núcleos y fusión](assets/img/alineacion-nucleos.svg)

### Secuencia completa del proceso
![Secuencia del proceso de termofusión](assets/img/proceso-fusion.svg)

---

## 5. Presupuesto óptico del enlace

Este cálculo teórico proyecta la pérdida máxima permitida para asegurar que un enlace de fibra sea viable bajo el estándar GPON.

### Fórmula General
```
Pérdida total = (Distancia × atenuación/km) + (N° conectores × pérdida/conector)
              + (N° empalmes × pérdida/empalme) + Splitter + Margen de seguridad
```

### Valores de Referencia Estándar

| Parámetro | Valor Usado |
|---|---|
| Atenuación de la fibra a 1310 nm | 0,35 dB/km |
| Atenuación de la fibra a 1550 nm | 0,22 dB/km |
| Pérdida por conector mecánico/fusión | 0,5 dB |
| Pérdida por empalme por fusión | 0,1 dB |
| Splitter óptico (1:8) | 10,5 dB |
| Margen de seguridad (Recomendado) | 3,0 dB |
| Presupuesto máximo GPON Clase B+ | 28,0 dB |

### Simulación de Cálculo de Enlace Teórico (A 1310 nm)
*(Nota: Estos valores se ajustarán con la arquitectura final asignada por el docente)*

| Elemento | Cantidad | Pérdida unitaria | Pérdida total |
|---|---|---|---|
| Fibra Óptica Monomodo | 2 km | 0,35 dB/km | 0,70 dB |
| Conectores Ópticos | 2 | 0,5 dB | 1,00 dB |
| Empalmes por fusión | 4 | 0,1 dB | 0,40 dB |
| Splitter Óptico 1:8 | 1 | 10,5 dB | 10,50 dB |
| **Subtotal Teórico** | | | **12,60 dB** |
| Margen de seguridad | | | 3,00 dB |
| **Pérdida Total con Margen** | | | **15,60 dB** |

![Esquema del enlace y presupuesto óptico](assets/img/enlace-presupuesto.svg)

**Análisis de Viabilidad:** La pérdida total proyectada de **15,60 dB** es totalmente viable, ya que se encuentra muy por debajo de los **28,0 dB** máximos impuestos por la norma GPON Clase B+, dejando un margen de protección ante futuras reparaciones o envejecimiento de la planta.

---

## 6. Mediciones y verificación (Plantilla de Terreno)

```
[SECCIÓN EN BLANCO: Diseñada para recolectar los datos empíricos obtenidos en el taller]
```

### Pérdida estimada por la fusionadora

| Empalme N° | Pérdida estimada (dB) | Estado / Resultado |
|---|---|---|
| 1 | `[Por ingresar]` | `[Muy bueno / Aceptable / Repetir]` |
| 2 | `[Por ingresar]` | `[Muy bueno / Aceptable / Repetir]` |
| 3 | `[Por ingresar]` | `[Muy bueno / Aceptable / Repetir]` |

### Continuidad y pérdida real del enlace

| Medición instrumental | Valor medido | Instrumento utilizado |
|---|---|---|
| Prueba de Continuidad | `[Sí / No]` | Localizador Visual de Fallas (VFL) |
| Atenuación Total del Enlace | `[__ dB]` | Power Meter (OPM) + Fuente de Luz |

### Criterio de Aceptación

| Pérdida por Empalme | Calidad Técnica | Acción Requerida |
|---|---|---|
| ≤ 0,10 dB | Muy buena | ... |
| 0,11 – 0,30 dB | Aceptable | ... |
| > 0,30 dB | Deficiente | ... |

### Análisis de Resultados de Laboratorio
```
[PENDIENTE EN TALLER: Aquí compararé la pérdida real arrojada por los instrumentos 
frente al cálculo teórico del presupuesto óptico de la sección 5, detallando causas 
de posibles variaciones como suciedad, desalineaciones o empalmes críticos.]
```

---

## 7. Conclusiones

```
[PENDIENTE EN TALLER: Redactar al término de la práctica un análisis de 3 o 4 líneas 
sobre los aprendizajes obtenidos, las dificultades del manejo de la fusionadora 
y la importancia de las normas de limpieza en redes de telecomunicaciones.]
```
