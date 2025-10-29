# Guía de Inicio para el Proyecto ERP-2DAM-2025_2026

Bienvenido al proyecto educativo **ERP-2DAM-2025_2026**. Esta guía te ayudará a comenzar a trabajar en tu módulo de forma organizada y colaborativa.

---

## ✅1. Clonar el repositorio

Abre tu terminal o IDE y ejecuta:

```bash
git clone https://github.com/tu-usuario/ERP-2DAM-2025_2026.git
cd ERP-2DAM-2025_2026
```
## ✅2. Cambiar a tu rama de trabajo

Cada equipo tiene asignada una rama. Para cambiar a la tuya:

```bash
git checkout nombre-de-tu-rama
```
Ejemplo para el equipo de CRM:

```bash
git checkout crm
```
## ✅3. Trabajar en tu carpeta

Cada módulo tiene su propia carpeta. **SOLO DEBES MODIFICAR ARCHIVOS DENTRO DE TU CARPETA**:
```bash
ERP-2DAM-2025_2026/
├── CRM/
├── Finanzas/
├── RRHH/
...
```

## ✅4. Subir tus cambios
Cuando hayas hecho cambios, súbelos con:

```bash
git add .
git commit -m "Descripción clara del cambio"
git push origin nombre-de-tu-rama
```