# IASI Setup Platform

[Español](#español) · [English](#english)

`iasi-setup-platform` forma parte de **IASI** y proporciona el punto de entrada para preparar la infraestructura necesaria para ejecutar la plataforma IASI.

`iasi-setup-platform` is part of **IASI** and provides the entry point for preparing the infrastructure required to run the IASI platform.

## Español

### Objetivo

Este proyecto reúne:

- una **guía de usuario** con el proceso de preparación de la plataforma;
- los **ejecutables de setup** para las plataformas soportadas;
- la base sobre la que se irá automatizando la instalación y configuración de la infraestructura necesaria para IASI.

### Estructura

```text
iasi-setup-platform/
├── bin/
│   ├── ps/
│   │   └── setup.ps1
│   └── sh/
│       └── setup.sh
├── docs/
│   └── user-guide/
│       ├── _quarto.yml
│       └── index.qmd
├── LICENSE
└── README.md
```

### Uso

#### Windows / PowerShell

```powershell
.\bin\ps\setup.ps1
```

#### Linux / shell

```bash
./bin/sh/setup.sh
```

Los scripts son, por ahora, el esqueleto mínimo del proceso de setup. Su funcionalidad crecerá junto con las necesidades de la plataforma IASI.

### Guía de usuario

La documentación se encuentra en [`docs/user-guide`](docs/user-guide/).

Para previsualizarla con Quarto:

```bash
quarto preview docs/user-guide
```

---

## English

### Purpose

This project contains:

- a **user guide** describing the platform setup process;
- the **setup executables** for supported platforms;
- the foundation for progressively automating the installation and configuration of the infrastructure required by IASI.

### Structure

```text
iasi-setup-platform/
├── bin/
│   ├── ps/
│   │   └── setup.ps1
│   └── sh/
│       └── setup.sh
├── docs/
│   └── user-guide/
│       ├── _quarto.yml
│       └── index.qmd
├── LICENSE
└── README.md
```

### Usage

#### Windows / PowerShell

```powershell
.\bin\ps\setup.ps1
```

#### Linux / shell

```bash
./bin/sh/setup.sh
```

For now, the scripts provide the minimal skeleton of the setup process. Their functionality will grow together with the needs of the IASI platform.

### User guide

Documentation is located in [`docs/user-guide`](docs/user-guide/).

To preview it with Quarto:

```bash
quarto preview docs/user-guide
```

## License

MIT License. See [`LICENSE`](LICENSE).
