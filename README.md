# Macritex — Releases

Canal oficial de descargas de **Macritex**, el sistema de gestión de producción, stock y ventas.

## Descargar

Entrá a la sección **[Releases](../../releases)** de este repositorio y bajá el instalador
`macritex-setup-<versión>.exe` del release más reciente.

Cada release publica tres archivos:

| Archivo | Para qué sirve |
|---|---|
| `macritex-setup-<versión>.exe` | El instalador. Es el único que necesitás para instalar. |
| `macritex-setup-<versión>.exe.sha256` | Suma de verificación, para confirmar que la descarga no se corrompió. |
| `latest.yml` | Lo usa la aplicación para detectar actualizaciones. No hace falta descargarlo. |

## Instalación

Ejecutá el `.exe` y seguí el asistente. Requiere Windows 10 o superior (64 bits).

Una vez instalado, **Macritex se actualiza solo**: revisa este repositorio periódicamente y avisa
cuando hay una versión nueva. No hace falta volver a descargar nada a mano.

## Verificar la descarga (opcional)

En PowerShell, desde la carpeta donde bajaste los dos archivos:

```powershell
Get-FileHash macritex-setup-<versión>.exe -Algorithm SHA256
```

El resultado tiene que coincidir con el contenido del archivo `.sha256`.

## Soporte

Este repositorio contiene **únicamente los instaladores**: el código fuente es privado.
Para reportar un problema o pedir ayuda, abrí un
[issue](../../issues) describiendo qué versión usás y qué pasó.

---

Desarrollado por **NANDI Services**.
