# Criptografía aplicada a la protección de la información en un Sistema Operativo

**Trabajo Práctico Integrador — Arquitectura y Sistemas Operativos**

---

**Alumno**: Lautaro Ezequiel Pérez.

**Docente titular**: Martín Aristarian.

**Docente tutor**: Nicolás Carcaño.

**Fecha de entrega**: 25 de junio de 2026.

---

## Descripción

Este trabajo demuestra de forma práctica cómo se aplica la criptografía para proteger la información en un sistema operativo GNU/Linux (Ubuntu 26.04), utilizando herramientas de uso real tanto para usuarios comunes como para desarrolladores.

Se abordaron dos grandes áreas:

- **Cifrado de archivos** con GPG (orientado al usuario común) y OpenSSL (orientado al desarrollador).
- **Cifrado de disco** mediante un contenedor LUKS con `cryptsetup`.

---

## Estructura del repositorio

```
├── Documentación/
│   ├── TPI-AySO-Lautaro-Perez.pdf    # Informe técnico completo
│   └── Capturas/                     # Evidencia del proceso práctico
└── README.md
```

---

## Video explicativo

🎥 [Ver video en YouTube](https://www.youtube.com/watch?v=xePYrEhMzLc)

---

## Herramientas utilizadas

- `gpg` — GNU Privacy Guard (cifrado simétrico AES-256)
- `openssl` — Cifrado AES-256-CBC con derivación PBKDF2
- `cryptsetup` — Cifrado de disco con LUKS
