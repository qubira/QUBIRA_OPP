# QUBIRA OPP — Oficina de Presupuestos y Planeación

Módulo financiero y de pricing corporativo de **QUBIRA SAC**.

## 📌 Propósito
El módulo **OPP** (*Oficina de Presupuestos y Planeación*) se encarga de:
1. **Revisión de proyectos aprobados por ADG**: Identifica proyectos de software y tecnología listos para comercialización.
2. **Estructuración y Fijación de Precios**:
   - Costo base de desarrollo y despliegue.
   - Precio de **Venta** (sugerido y mínimo negociable).
   - Precio de **Alquiler / Suscripción mensual** (sugerido y mínimo negociable).
3. **Cálculo Financiero y Márgenes**:
   - % de Margen bruto calculado en tiempo real.
   - Retorno de Inversión (ROI en meses) según canon de alquiler.
   - Simulación con o sin IGV (18%).
4. **Directrices para el Área Comercial**:
   - Pautas de negociación, límites de descuento y cláusulas recomendadas.
   - Habilitación / publicación directa al catálogo de **QUBIRA Comercial**.
5. **Agenda y Calendario Integrado**:
   - Eventos y fechas corporativas compartidas con el ecosistema Qubira.

## 🚀 Despliegue en Vercel
Este repositorio está preparado para despliegue automático en Vercel:
- **Framework Preset**: `Other`
- **Root Directory**: `./`
- **Archivos principales**:
  - `index.html`: Aplicación principal (SPA empresarial con diseño ultra-moderno glassmorphism).
  - `login.html`: Gate de validación y Single Sign-On (SSO) vía token compartido desde el Portal QUBIRA.
  - `vercel.json`: Reglas de enrutamiento estático.
