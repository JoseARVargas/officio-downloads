# OFFICIO — Downloads

Instaladores dos plugins **Officio BIM** da [OFFICIO](https://officio.net.br).
Este repositório só distribui os instaladores; o código-fonte é privado.

Página oficial de download: **https://officio.net.br/downloads**

| Plugin | Plataforma | Versão |
|---|---|---|
| Officio BIM para Revit | Autodesk Revit 2025 e 2026 | [0.2.0 (beta)](https://github.com/JoseARVargas/officio-downloads/releases/tag/revit-v0.2.0) |
| Officio BIM para AutoCAD | AutoCAD 2025 e 2026, com Plant 3D e Civil 3D | [0.2.0 (beta)](https://github.com/JoseARVargas/officio-downloads/releases/tag/autocad-v0.2.0) |

## Conferir o arquivo

Cada instalador vem com um arquivo `.sha256`. No PowerShell:

```powershell
Get-FileHash .\Officio-Revit-0.2.0-Setup.exe -Algorithm SHA256
```

O hash precisa ser igual ao do arquivo `.sha256` da mesma release.
