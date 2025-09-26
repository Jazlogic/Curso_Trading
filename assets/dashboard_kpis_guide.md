# Guía: Dashboard de KPIs (Hoja de Cálculo)

## Pestañas
- Diario: importa `assets/diario_trading.csv`.
- KPIs: calcula expectancy, hit rate, payoff, DD, trades/semana, cumplimiento.
- Equity: curva de equity acumulada y drawdown.

## Fórmulas sugeridas
- Expectancy: PROMEDIO(columna resultado_R)
- Hit rate: CONTAR.SI(resultado_R, ">0")/N
- Payoff: PROMEDIO(resultado_R positivos)/ABS(PROMEDIO(resultado_R negativos))
- Equity: multiplicativa con 1+R por trade; DD como caída desde máximo.

## Visualizaciones
- Curva de equity y DD.
- Barras de KPIs y distribución de R por trade.

## Uso
- Actualiza semanalmente; toma decisiones con `criterios_go_live.md` y límites del plan.
