# 📏 Clase 02: Tamaño de Posición y Fórmulas Prácticas

## 1. Componentes del tamaño
- Capital total, % de riesgo por trade y distancia al stop.
- Volatilidad del activo: stops más amplios implican menor tamaño.

## 2. Fórmula base (sin tecnicismos)
- Tamaño = (Capital × %Riesgo) / Distancia al Stop (en valor monetario por unidad).
- Ejemplo: Capital 1,000; riesgo 1% (=10); stop 20 pips con valor 0.1 por pip → Tamaño = 10 / (20×0.1) = 5 unidades.

## 3. Ajustes
- Redondeo al tamaño mínimo de la plataforma.
- Reducir tamaño si hay noticias o mayor incertidumbre.

## 4. Errores comunes
- Aumentar tamaño para “recuperar”.
- Ignorar comisiones/spread en distancias cortas.

## 5. Ejercicios
- Calcular tamaño para 5 escenarios con distintas distancias de stop.
- Registrar tus resultados y conclusiones.

---
Anterior: [← Clase 01](Clase_01_Principios_de_Gestion_de_Riesgo.md) | Siguiente: [Clase 03 →](Clase_03_Herramientas_y_Estrategias_de_Control_de_Riesgo.md)
