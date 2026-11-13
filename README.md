
# Megaline — Telecom Revenue Analysis | Tripleten Sprint 5

**Data Analytics · Python · pandas · NumPy · Matplotlib · SciPy · Statistical Hypothesis Testing**

## Overview | Descripción

Statistical analysis comparing Megaline's Surf and Ultimate prepaid mobile plans to support advertising budget decisions.

Análisis estadístico de los planes Surf y Ultimate de Megaline para apoyar decisiones comerciales basadas en datos.

## Methodology | Metodología

- Analyzed 2018 usage data from 500 customers.
- Integrated customer, call, message, internet, and plan datasets.
- Cleaned records and calculated monthly usage and revenue.
- Compared consumption patterns and revenue distributions.
- Applied Welch's t-tests to evaluate differences between plans and geographic regions.
- Used customer-level monthly averages for statistical testing.

## Key Findings | Hallazgos principales

- Statistical sample: 490 customers with recorded usage.
- Ultimate: average monthly revenue of $71.82 USD per customer.
- Surf: average monthly revenue of $58.19 USD per customer.
- Revenue difference between plans: statistically significant (p ≈ 5.72e-8).
- New York–New Jersey versus other regions: no statistically significant difference established (p ≈ 0.4410).
- Internet allowance exceeded in 57.91% of Surf user-month records versus 5.69% for Ultimate.

## Business Outcome | Resultado empresarial

Ultimate generated higher average monthly revenue per customer in the analyzed sample. The findings support plan comparison and advertising decisions, while highlighting the contribution of overage charges.

Ultimate presentó mayores ingresos mensuales promedio por cliente. Los resultados permiten fundamentar decisiones comerciales, considerando también los cargos por consumo excedente.

## Limitations | Limitaciones

- Observational data from 2018.
- Revenue does not necessarily represent profitability.
- Operating and customer acquisition costs were unavailable.
- Statistical associations do not establish causality.

## Reproducibility | Reproducibilidad

The notebook uses external datasets. Authorized access to the original data and adjustment of local file paths may be required.

## Project Files

- `sprint5_megaline_optimizacion_ingresos_EDA.ipynb`
- `requirements.txt`
- `.gitignore`

## License

No open-source license is granted for the original project code or documentation. Third-party datasets and libraries remain subject to their respective terms.
