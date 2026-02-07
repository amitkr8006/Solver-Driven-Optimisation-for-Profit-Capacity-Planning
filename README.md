# Solver-Driven Optimisation for Profit & Capacity Planning

## Overview
This project is a combined MS5107 optimisation portfolio applying linear programming (LP) to maximise profit under real operational constraints. Two Solver-based business cases are included:
1) Brewery production and packaging optimisation (litres + cans/bottles)
2) Celtic Candles production planning for 8,500 stores with display-space requirements

## Case 1 — Brewery Production & Packaging Optimisation
### Goal
Maximise profit by selecting optimal beer production (litres) and packaging mix (cans/bottles) under constraints on raw materials, brewing time, packaging time, storage limits and packaging relationships.

### Approach
- Modelled as a linear program with decision variables for beer volumes and packaging quantities.
- Solved using Microsoft Excel Solver.

### Key Results
- Optimal production chooses two products strongly and sets lager to zero under current economics.
- Profit-maximising plan includes an optimal cans/bottles mix and fixed costs.
- Sensitivity insights: yeast is binding with a strong shadow price, packaging time has slack, and brewing overtime is valuable only below a threshold cost.

## Case 2 — Celtic Candles Production Optimisation (8,500 Stores)
### Goal
Maximise profit while meeting wax/fragrance/wick limits and strict display-space requirements per store for multiple candle product types.

### Approach
- Linear programming formulation with five product decision variables.
- Solved using Excel Solver (Simplex LP).

### Key Results
- Solution prioritises small jars and small pillars, produces zero large pillars, and meets votive display minimum exactly.
- Wax is binding; fragrance and wick have slack.
- Shadow prices and reduced costs explain which constraints and products drive profitability.

## Outcome
A complete demonstration of LP modelling, Solver execution, and sensitivity interpretation (binding constraints, slack, shadow prices, reduced costs) to support practical production and capacity decisions.
