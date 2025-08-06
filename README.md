

## 🛠️ Metodología y Conceptos Clave

El flujo de trabajo del laboratorio consistió en:
1.  **Captura de Señales:** Utilizando un osciloscopio **Tektronix TDS 2012B**, se generaron y capturaron las formas de onda en el tiempo.
2.  **Análisis Espectral (FFT):** Se empleó la función `MATH/FFT` del osciloscopio para obtener una visualización inmediata del espectro de frecuencia de cada señal.
3.  **Exportación de Datos:** Todas las señales (tanto en tiempo como en frecuencia) fueron exportadas a archivos `.csv` para un análisis más profundo.
4.  **Procesamiento en MATLAB:** Se utilizaron scripts de MATLAB para leer los archivos `.csv`, graficar las señales, calcular la FFT y reconstruir señales a partir de su espectro mediante la IFFT.
5.  **Análisis Comparativo:** Se compararon los resultados experimentales (mediciones del osciloscopio y gráficas de MATLAB) con los valores teóricos calculados a partir de las fórmulas de las series de Fourier.

## 🔧 Herramientas Utilizadas

-   **Hardware:** Osciloscopio Digital Tektronix TDS 2012B.
-   **Software:**
    -   **MATLAB:** Para el procesamiento de datos, análisis numérico (FFT, IFFT) y generación de gráficas.
    -   **LaTeX (MiKTeX/TeX Live):** Para la redacción del informe técnico en formato IEEE.

## 🚀 Cómo Utilizar este Repositorio

1.  **Consultar el Informe:** La forma más rápida de entender el alcance completo del proyecto es leer el archivo `CDA2.pdf`.
2.  **Reproducir el Análisis:** Puedes utilizar los archivos `/.csv` como entrada para tus propios scripts en MATLAB, Python o cualquier otro software de análisis para replicar los resultados. Los scripts de ejemplo se pueden encontrar en el apéndice del informe.
3.  **Revisar el Código Fuente:** El archivo `CDA2.pdf` sirve como referencia de formato para la redacción de informes técnicos en LaTeX.

## 👨‍💻 Autor

-   **Miguel Andrey Peña Cárdenas**
-   Estudiante de Ingeniería en Telecomunicaciones
-   Universidad Militar Nueva Granada - Bogotá, Colombia
-   *est.miguela.pena@unimilitar.edu.co*

## 📄 Licencia

Este proyecto se distribuye bajo la **Licencia MIT**. Esto significa que eres libre de usar, modificar y distribuir el contenido, siempre y cuando incluyas la atribución original.
