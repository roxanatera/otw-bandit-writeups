# Bandit (OverTheWire) — Mi recorrido 🧑‍💻 / My journey

> ES · Serie de aprendizaje en las wargames de [OverTheWire](https://overthewire.org/wargames/bandit/). Concepto: **learning in public** — cada nivel, lo que enseña y cómo lo resolví.
>
> EN · My learning series on the [OverTheWire](https://overthewire.org/wargames/bandit/) wargames. It's my **learning in public** project: every level, what it teaches and how I solved it.

---

## 🇪🇸 Español

Sobre las wargames de Bandit mientras avanzo: cada nivel enseña un concepto Unix (permisos, `find`, `grep`...), y lo documento tal cual, con mis errores incluidos. Las contraseñas se omiten por norma de la plataforma — lo que comparto es la **técnica y el razonamiento**.

### Índice de niveles

| Nivel | Concepto clave | Writeup |
|---|---|---|
| 0 → 1 | SSH básico + primer encuentro | 🔜 |
| 1 → 2 | Archivos con nombres raros (guiones, espacios) | 🔜 |
| 2 → 3 | Rutas relativas vs absolutas | 🔜 |
| 3 → 4 | Archivos ocultos (dotfiles) | 🔜 |
| 4 → 5 | `file` para identificar contenido | 🔜 |
| 5 → 6 | `find` por tamaño, usuario y grupo | 🔜 |
| 6 → 7 | Búsqueda dirigida + higiene de enumeración (`2>/dev/null`) | ✅ [nivel-06.md](nivel-06.md) |

### 💡 Lecciones transversales

- **`find` como herramienta de enumeración**: describir el perfil del objetivo y dejar que el sistema lo traiga (mirar [nivel 6](nivel-06.md))
- (`llenar a medida que avanzo...`)

### 🛠️ Toolbox

`ssh` · `ls` · `cat` · `file` · `find` · `du` · `grep` · `chmod`

---

## 🇬🇧 English

I'm working through the Bandit wargames and documenting every level as I go, mistakes included. Passwords are omitted per the platform's spirit — what I share is the **technique and the reasoning**.

### Level index

| Level | Key concept | Writeup |
|---|---|---|
| 0 → 1 | Basic SSH | 🔜 |
| 1 → 2 | Odd filenames (dashes, spaces) | 🔜 |
| 2 → 3 | Relative vs absolute paths | 🔜 |
| 3 → 4 | Hidden files (dotfiles) | 🔜 |
| 4 → 5 | `file` to identify contents | 🔜 |
| 5 → 6 | `find` by size, user and group | 🔜 |
| 6 → 7 | Targeted search + enumeration hygiene (`2>/dev/null`) | ✅ [nivel-06.md](nivel-06.md) |

### 💡 Cross-cutting lessons

- **`find` as an enumeration tool**: describe the target's profile and let the system bring it to you ([level 6](nivel-06.md))
- (to be filled as I progress...)

### 🛠️ Toolbox

`ssh` · `ls` · `cat` · `file` · `find` · `du` · `grep` · `chmod`
