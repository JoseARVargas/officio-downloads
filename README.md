# OFFICIO — Downloads

Instaladores dos plugins **Officio BIM** e programas das ferramentas da [OFFICIO](https://officio.net.br).
Este repositório só distribui os executáveis; o código-fonte é privado.

Página oficial de download: **https://officio.net.br/downloads**

| Plugin | Plataforma | Versão |
|---|---|---|
| Officio BIM para Revit | Autodesk Revit 2025, 2026 e 2027 | [1.4.0 (beta)](https://github.com/JoseARVargas/officio-downloads/releases/tag/revit-v1.4.0) |
| Officio BIM para AutoCAD | AutoCAD 2025, 2026 e 2027, com Plant 3D, Civil 3D e Advance Steel | [1.3.0 (beta)](https://github.com/JoseARVargas/officio-downloads/releases/tag/autocad-v1.3.0) |
| Officio BIM para Navisworks | Autodesk Navisworks Manage e Simulate 2025, 2026 e 2027 | [1.0.10 (beta)](https://github.com/JoseARVargas/officio-downloads/releases/tag/navisworks-v1.0.10) |
| Officio Brick2IFC | Windows 64 bits · modelos do BrickLink Studio | [2.0.1 (beta)](https://github.com/JoseARVargas/officio-downloads/releases/tag/brick2ifc-v2.0.1) |

## Conferir o arquivo

Cada instalador vem com um arquivo `.sha256`. No PowerShell:

```powershell
Get-FileHash .\Officio-Revit-1.4.0-Setup.exe -Algorithm SHA256
```

O hash precisa ser igual ao do arquivo `.sha256` da mesma release.
