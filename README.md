# Reductor cicloidal 19:1 para motor LA8308 KV90

Este repositorio contiene el diseño geométrico, los modelos CAD, los scripts de cálculo y la documentación del **reductor cicloidal de doble disco 19:1** impreso en PETG, desarrollado para un actuador de rueda de un robot móvil teleoperado.

El diseño original del perfil cicloidal, la selección de parámetros geométricos y los cálculos de verificación mecánica (contacto, flexión y fatiga) fueron realizados por **Rafael Alejandro León Llanllaya** (Universidad Católica de Santa María, Arequipa, Perú).

---

## Contenido del repositorio

La estructura propuesta es la siguiente (puedes ajustarla a tu gusto):

```text
.
├── doc/
│   ├── paper_ieee.tex        # Artículo en formato IEEE
│   ├── paper_ieee.pdf        # PDF de la preimpresión
│   └── notas_diseno.md       # Notas adicionales de diseño
├── cad/
│   ├── disco_cicloidal.SLDPRT
│   ├── conjunto_reductor.SLDASM
│   └── export_step/          # Archivos .step/.iges para intercambio
├── scripts/
│   ├── cicloide_waterloo.m   # Generación del perfil en MATLAB
│   ├── postprocesado.m       # Cálculo de esfuerzos / gráficos
│   └── ...                   # Otros scripts relacionados
├── img/
│   ├── A1.png                # Render CAD del reductor
│   ├── A2.png                # Sección del conjunto reductor-rueda
│   ├── A3.png                # Boceto paramétrico en SolidWorks
│   └── A4.png                # Perfil generado en MATLAB
└── README.md
