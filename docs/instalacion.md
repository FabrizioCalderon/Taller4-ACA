# Instalación

## Requisitos

| Herramienta | Versión recomendada | Uso |
|---|---:|---|
| Python | 3.10+ | Ejecutar MkDocs |
| Git | 2.x | Control de versiones |
| MkDocs | Actual | Generar el sitio |

## Instalación local

=== "Linux / EndeavourOS"

    ```bash
    sudo pacman -S python python-pip git
    python -m venv .venv
    source .venv/bin/activate
    pip install mkdocs-material
    ```

=== "Windows"

    ```powershell
    python -m venv .venv
    .venv\Scripts\activate
    pip install mkdocs-material
    ```

=== "macOS"

    ```bash
    python3 -m venv .venv
    source .venv/bin/activate
    pip install mkdocs-material
    ```

!!! warning "Importante"
    Activa siempre el entorno virtual antes de ejecutar MkDocs.

Continúa con la página de [uso](uso.md).