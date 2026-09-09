# 🧠 CRM Consultorio de Psicología

Sistema de gestión integral y automatización para consultorio de psicología especializado en **Consultas Individuales** y **Evaluaciones Neurocognitivas**.

## 🌟 Características Principales

### 1. 🗓️ Agenda y Turnero Clínico (Turnos de 1 Hora)
- **Horarios de Atención Predefinidos**:
  - **Lunes**: 15:00 a 19:00 hs (4 slots de 1h)
  - **Miércoles**: 15:00 a 19:00 hs (4 slots de 1h)
  - **Viernes**: 08:00 a 12:00 hs (4 slots de 1h)
- **Control Estricto de Disponibilidad**: Bloquea solapamientos y no permite agendar más de 1 paciente por horario.
- **Modalidades de Atención**:
  - 🏥 **Presencial** (Consultorio A)
  - 💻 **Online por Google Meet** (incluye botón directo para iniciar la videollamada `💻 Abrir Meet`).

### 2. 💳 Cobro de Honorarios por Mercado Pago
- **Honorarios Terapéuticos y Evaluaciones**:
  - `Consulta Psicológica (1h)`: **$55.000 ARS**
  - `Examen Neurocognitivo Completo (5 sesiones)`: **$275.000 ARS**
- **Acción 1-Clic (`✓ Cobrado MP`)**: Registra la transferencia de Mercado Pago y genera automáticamente el ingreso en el módulo Financiero.
- **Avisos por WhatsApp**: Plantillas de mensaje predefinidas para solicitar comprobantes de transferencia con Alias MP (`consultorio.psico.mp`).

### 3. 🔄 Integración "Un Solo Negocio" (7 Módulos Interconectados)
- **Financiero**: Control de honorarios cobrados y egresos del consultorio (alquiler, supervisión clínica, matrícula, materiales).
- **Cobranza MP**: Control de transferencias pendientes con semáforo de mora.
- **Servicios y Test**: Catálogo de honorarios e inventario de cuadernillos/protocolos de test (WISC-V, BDI-II).
- **Presupuestos**: Cotizador de evaluaciones neurocognitivas que se sincroniza directo con el CRM.
- **CRM / Pacientes**: Pipeline de admisión (`Nuevo` → `Contactado` → `Interesado` → `Esperando` → `Paciente Activo`).
- **Postventa**: Seguimiento terapéutico y control de frecuencia de asistencia a sesiones.

---

## 🚀 Despliegue en Vercel

Este repositorio incluye el archivo `vercel.json` y `index.html` de redirección para despliegue inmediato en Vercel:

1. Importá este repositorio en [vercel.com](https://vercel.com).
2. Hacé clic en **Deploy**.
3. ¡Tu CRM estará disponible en vivo en segundos!

---

## 🛠️ Ejecución Local

Abrí `demo/index.html` en tu navegador o serví la carpeta con cualquier servidor HTTP local.
Agregar servidor Node.js y package.json para Railway

