# Especialidades en Fisioterapia

Aplicación educativa independiente, adaptable a teléfonos, con cuatro casos ficticios, imágenes simuladas, protocolos paso a paso, registro local por grupo y descarga de informe PDF.

## Poner los archivos en GitHub

1. Crea un repositorio nuevo en GitHub.
2. Descomprime este paquete y sube **todo su contenido** a la raíz del repositorio. Incluye la carpeta oculta `.github` y todos los archivos de `client/`.
3. En GitHub abre **Settings → Pages** y selecciona **GitHub Actions** como fuente.
4. Abre **Actions** y espera a que termine el flujo **Deploy GitHub Pages**. El enlace aparecerá en **Settings → Pages**.

El flujo compila y publica automáticamente cada vez que se suben cambios a `main`. No hace falta configurar un servidor ni guardar credenciales en el repositorio.

## Probar localmente (opcional)

Requiere Node.js 22 y pnpm 10.26.0.

```bash
pnpm install --frozen-lockfile
pnpm run dev
```

Validación y compilación:

```bash
pnpm run check
pnpm run test
pnpm run build
```

## Contenido y privacidad

- Los cuatro casos y las imágenes son simulados para docencia; no representan personas pacientes reales.
- Los datos ingresados se guardan sólo en el almacenamiento local del navegador usado; no se envían a GitHub ni a un servidor.
- No ingresar datos identificables de pacientes reales.
- El material es introductorio y no reemplaza evaluación ni criterio clínico profesional.
