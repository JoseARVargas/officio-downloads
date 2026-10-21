# OFFICIO — Downloads

Instaladores dos plugins **Officio BIM** da [OFFICIO](https://officio.net.br).
Este repositório só distribui os instaladores; o código-fonte é privado.

Página oficial de download: **https://officio.net.br/downloads**

| Plugin | Plataforma | Versão |
|---|---|---|
| Officio BIM para Revit | Autodesk Revit 2025, 2026 e 2027 | [1.2.0 (beta)](https://github.com/JoseARVargas/officio-downloads/releases/tag/revit-v1.2.0) |
| Officio BIM para AutoCAD | AutoCAD 2025, 2026 e 2027, com Plant 3D, Civil 3D e Advance Steel | [1.1.3 (beta)](https://github.com/JoseARVargas/officio-downloads/releases/tag/autocad-v1.1.3) |
| Officio BIM para Navisworks | Autodesk Navisworks Manage e Simulate 2025, 2026 e 2027 | [1.0.1 (beta)](https://github.com/JoseARVargas/officio-downloads/releases/tag/navisworks-v1.0.1) |

## Conferir o arquivo

Cada instalador vem com um arquivo `.sha256`. No PowerShell:

```powershell
Get-FileHash .\Officio-Revit-1.2.0-Setup.exe -Algorithm SHA256
```

O hash precisa ser igual ao do arquivo `.sha256` da mesma release.
