# Panel de Control Financiero

Conjunto de herramientas web interactivas diseñadas para la planificación financiera, análisis de inversiones y toma de decisiones estratégicas a largo plazo.


## 🛠️ Herramientas Disponibles

### 1. Simulador Estratégico a Largo Plazo
**Enlace:** [https://hcosta.github.io/finances](https://hcosta.github.io/finances)

Simulador financiero personal que permite proyectar el patrimonio a largo plazo (hasta 30 o más años) considerando múltiples clases de activos.

**Características:**
- Gestión de 6 clases de activos: Pólvora Seca, Renta Fija, Renta Variable, Metales, Crypto e Inmuebles
- Simulación de aportaciones periódicas (DCA) con diferentes orígenes de capital
- Gestión algorítmica de crisis basada en la Media Móvil Simple de 200 días (MMS200)
- Escenarios predefinidos: Negativo ("Década Perdida"), Neutro ("Crecimiento Estable") y Positivo ("Mercado Alcista")
- Visualización gráfica de la evolución del patrimonio
- Ajuste por inflación
- Exportación e importación de datos para backup

### 2. El Mundo en 2050: El Reequilibrio Global
**Enlace:** [https://hcosta.github.io/finances/futures](https://hcosta.github.io/finances/futures)

Herramienta de visualización que compara la composición hipotética del índice FTSE All-World entre el año 2025 y una proyección para 2050.

**Características:**
- Gráficos comparativos tipo "pie" de la distribución geográfica del índice
- Análisis del cambio de poder económico global
- Visualización del ascenso de China e India como potencias dominantes
- Análisis del declive relativo de Estados Unidos y Europa
- Tabla detallada con el cambio de peso de cada región

### 3. Buy & Hold vs. Sistema Algorítmico
**Enlace:** [https://hcosta.github.io/finances/investors](https://hcosta.github.io/finances/investors)

Comparativa visual que muestra la evolución de 100.000€ invertidos en el peor momento posible (pico de la burbuja puntocom en marzo de 2000) hasta 2025, comparando dos estrategias:

**Estrategias comparadas:**
- **"Buy & Hold" (La Montaña Rusa):** Mantener la inversión sin importar las crisis
  - Caídas catastróficas del -50% y -57%
  - Más de una década para recuperar la inversión inicial
  - Resultado final: 380.000€

- **"Inversor Sistemático" (El Camino Controlado):** Usar algoritmo basado en MMS200
  - Pérdidas máximas limitadas al -20%
  - Protección del capital en cada crisis
  - Resultado final: 550.000€ (+45% mejor que Buy & Hold)

### 4. Panel de Control Sistémico (Quaderno)
**Enlace:** [https://hcosta.github.io/finances/quaderno](https://hcosta.github.io/finances/quaderno)

Herramienta de decisión en tiempo real que actúa como un semáforo para la inversión en Renta Variable, basándose en la Media Móvil Simple de 200 días (MMS200) del Vanguard FTSE All-World (VWCE).

**Características:**
- **Señal Verde (INVERTIDO):** Cuando el precio está por encima de la MMS200 - Tendencia alcista
- **Señal Roja (LIQUIDEZ):** Cuando el precio está por debajo de la MMS200 - Tendencia bajista
- Consulta automática de datos del mercado mediante API de Alpha Vantage (pasarla por get asi `?apikey=XXXXXXXXX`)
- Caché inteligente de datos (actualización cada hora)
- Visualización clara de precio actual vs. MMS200
- Interfaz tipo semáforo con animación

---

## 📊 Propósito General

Estas herramientas fueron desarrolladas para:

- Simular planes financieros sin realizar cálculos complejos manualmente
- Visualizar el impacto de diferentes decisiones de inversión
- Mantener el enfoque en objetivos de independencia financiera a largo plazo
- Aplicar una estrategia sistemática y algorítmica para reducir el impacto emocional en las inversiones
- Comprender mejor los ciclos económicos y las tendencias globales

## 💾 Tecnología

- Aplicaciones de una sola página (Single Page Applications)
- Almacenamiento local en el navegador (localStorage)
- Sin servidor backend - ejecución 100% en el cliente
- Frameworks: TailwindCSS, Chart.js
- APIs: Alpha Vantage (para datos de mercado en tiempo real)

---

*Las herramientas fueron desarrolladas en colaboración con asistentes de IA. Los datos iniciales y proyecciones son de carácter ilustrativo y no constituyen asesoramiento financiero.*