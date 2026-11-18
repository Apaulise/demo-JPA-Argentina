# Centro de Registración — demo

Demo funcional y genérica de automatización para estudios contables: recepción de comprobantes de compra y movimientos bancarios, validación, imputación, conciliación, excepciones y exportación a planilla.

- Un solo archivo: `index.html` (sin build, sin dependencias locales; SheetJS y pdf.js se cargan desde cdnjs).
- Todos los datos son ficticios (empresas, CUIT y montos de ejemplo). No usa nombres ni marcas de terceros.
- Interfaz en español (es-AR).

## Qué es real y qué es simulado

- **Real:** dígito verificador de CUIT, control de sumas, detección de duplicados, cruce banco–comprobante, asientos balanceados, exportación `.xlsx`.
- **Simulado:** canales de recepción, cruce con ARCA y la lectura del lote de ejemplo.
- La lectura de un comprobante real con IA solo funciona dentro de Claude; en esta versión publicada está desactivada.

## Uso local

Abrir `index.html` en el navegador.
