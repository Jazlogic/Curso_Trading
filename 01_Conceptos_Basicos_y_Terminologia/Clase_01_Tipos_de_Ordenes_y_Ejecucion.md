# 🧾 Clase 01: Tipos de Órdenes y Ejecución (sin tecnicismos)

## 1. ¿Qué es una orden?
- Es la instrucción que le das al broker para comprar o vender.
- Debe incluir: activo, cantidad/tamaño, tipo de orden y condiciones (si aplica).

## 2. Órdenes más usadas
- Mercado (Market): ejecuta ahora al mejor precio disponible. Pros: rapidez. Contras: puede haber deslizamiento.
- Límite (Limit): ejecuta sólo si el precio llega a tu nivel o mejor. Pros: control del precio. Contras: puede no ejecutarse.
- Stop (Stop-loss / Stop de entrada): activa una orden cuando el precio alcanza un nivel. Útil para limitar pérdidas o entrar en ruptura.
- Trailing Stop: el stop se mueve a favor de tu operación automáticamente.
- OCO/Bracket (si el broker lo permite): combina objetivo (take profit) y stop loss; si uno se ejecuta, cancela el otro.

## 3. TIF – Time in Force (si aplica)
- DAY: válida hasta el cierre del día.
- GTC: válida hasta cancelarla.
- IOC/FOK: ejecuta inmediatamente total o parcial.

## 4. Riesgos de ejecución
- Spread: diferencia entre compra y venta; intenta operar en horarios líquidos.
- Slippage (deslizamiento): ejecución peor de lo esperado en movimientos rápidos.
- Partial fills (llenados parciales): se ejecuta sólo una parte (más común en mercados de acciones/derivados con profundidad limitada).

## 5. Buenas prácticas
- Define el tamaño antes de abrir.
- Establece stop y objetivo al crear la orden (cuando sea posible).
- Revisa dos veces el tipo de orden y el activo antes de confirmar.

## 6. Ejercicios (Demo)
- Coloca 3 órdenes de mercado (buy/sell) con tamaño mínimo.
- Coloca 3 órdenes límite en niveles claros (soporte/resistencia) y observa si se ejecutan.
- Registra cada intento en `assets/diario_trading.csv`.

---
Anterior: [← Módulo 00](../00_Introduccion_al_Trading_y_Mentalidad/README.md) | Siguiente: [Clase 02 →](Clase_02_Instrumentos_Financieros_Basicos.md)
