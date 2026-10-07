# crypto-lattice-dashboard
Simulador interactivo de Criptografía Post-Cuántica basado en el problema de Aprendizaje con Errores (LWE).
# 🔐 Post-Quantum Crypto Lattice Dashboard (Toy LWE Engine)

**Desarrollado por:** Angel Breña  
*Simulador interactivo de Criptografía Post-Cuántica basado en el problema de Aprendizaje con Errores (LWE).*

---

## 📌 Descripción del Proyecto

Este proyecto es una herramienta visual e interactiva construida con **Python**, **Streamlit** y **Plotly**. Permite explorar de forma práctica cómo funciona la **Criptografía Basada en Retículos (Lattice-Based Cryptography)** utilizando el problema **LWE (Learning With Errors)**, pilar matemático de estándares como **ML-KEM (Kyber)** del NIST.

El tablero simula el comportamiento de esquemas post-cuánticos reales mediante:
- Generación de claves con vectores de ruido gaussiano.
- Cifrado de bits transformados en vectores ruidosos.
- Visualización geométrica del **Redondeo de Babai** para recuperar la señal.

---

## 🚀 Características Principales

- **Configuración Dinámica:** Ajuste de la dimensión de la red ($n$), módulo primo ($q = 3329$) y desviación del ruido ($\sigma$).
- **Perspectiva del Atacante:** Demostración gráfica de por qué la clave pública se ve caótica sin la clave privada.
- **Análisis Geométrico:** Gráfico en tiempo real que muestra la posición de la señal recuperada en el espacio modular.

---

## 🛠️ Requisitos e Instalación

Para ejecutar este dashboard en tu equipo o entorno local, necesitas tener instalado **Python 3.8+**.

1. **Instalar las dependencias necesarias:**
   ```bash
   pip install streamlit numpy plotly
