# **Evaluación Comparativa de Modelos de Reconocimiento de Voz con y sin Ruido y en Contextos Multilingües**

Este proyecto realiza un análisis exhaustivo de cinco modelos avanzados de reconocimiento automático de voz (ASR): **Conformer**, **Jasper**, **QuartzNet**, **SpeechBrain** y **Wav2Vec2.0**. El estudio evalúa su desempeño en condiciones de audio limpio, presencia de ruido y entornos multilingües, proporcionando información clave para elegir el modelo más adecuado según las necesidades de la aplicación.

---

## **Descripción del Proyecto**

La investigación se centra en tres criterios principales:

1. **Precisión de Transcripción**: Medida a través de la Tasa de Error de Palabra (WER).  
2. **Eficiencia Computacional**: Evaluada mediante el tiempo de inferencia promedio.  
3. **Adaptabilidad**: Analizada en escenarios de ruido y multilingües.

### **Principales Contribuciones**
- Comparación exhaustiva de modelos ASR en múltiples escenarios.
- Evaluación del rendimiento de **Wav2Vec2.0** en cinco idiomas: inglés, español, francés, alemán y portugués.
- Generación de gráficos y tablas para representar el desempeño de los modelos en términos de WER y tiempos de inferencia.

---

## **Requisitos del Sistema**

- **Python 3.8 o superior**  
- Google Colab (Recomendado para ejecutar el proyecto)  
- Bibliotecas necesarias: TensorFlow, librosa, NumPy, Matplotlib, entre otras.

---

## **Instrucciones de Uso**
1. Clona el repositorio:
2. Abre los notebooks en Google Colab:
Los experimentos están distribuidos en los siguientes notebooks:
- Comparación de modelos con audio limpio: [link](https://github.com/Katy-Bejar/Evaluacion-Comparativa-de-Modelos-de-Reconocimiento-de-Voz/blob/master/Comparaci%C3%B3n_de_modelos_con_audio_limpio.ipynb)
- Comparación de modelos con audio ruidoso: [link](https://github.com/Katy-Bejar/Evaluacion-Comparativa-de-Modelos-de-Reconocimiento-de-Voz/blob/master/Comparaci%C3%B3n_de_modelos_con_audio_ruidoso.ipynb)
- Evaluación multilingüe de Wav2Vec2.0: [link](https://github.com/Katy-Bejar/Evaluacion-Comparativa-de-Modelos-de-Reconocimiento-de-Voz/blob/master/Evaluaci%C3%B3n_multiling%C3%BCe_de_Wav2Vec2_0.ipynb)
3. Ejecuta las celdas:
Sigue las instrucciones dentro de cada notebook para reproducir los experimentos y obtener los resultados.

---
## **Resultados del proyecto**
Los principales hallazgos de este estudio incluyen:

- *Conformer*: Modelo más preciso y rápido, ideal para aplicaciones en tiempo real.
- *Wav2Vec2.0*: Excelente rendimiento en escenarios multilingües, pero con tiempos de inferencia más altos.
- *QuartzNet y Jasper*: Adecuados para aplicaciones que priorizan la velocidad sobre la precisión.
- *SpeechBrain*: Flexible y útil para investigación, pero menos eficiente en tiempo de inferencia.

Gráficos detallados y tablas comparativas están disponibles en los notebooks.
