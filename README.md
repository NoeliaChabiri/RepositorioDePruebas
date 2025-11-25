#  Guía Rápida de Sintaxis Markdown (README.md)

---

## 1. Títulos y Jerarquía (Encabezados)

Los títulos se definen con el símbolo de almohadilla (#). Cuantas más almohadillas, menor es la jerarquía (y más pequeño el texto).

### Título de Nivel 3 (###)

#### Título de Nivel 4 (####)

---

## 2. Énfasis de Texto

Podemos resaltar el texto usando asteriscos (*) o guiones bajos (_).

* **Negrita:** Se utiliza el doble asterisco o doble guion bajo.
    Ejemplo: **Esto va en negrita** o __Esto también__.

* *Cursiva:* Se utiliza un solo asterisco o un solo guion bajo.
    Ejemplo: *Esto va en cursiva* o _Esto también_.

* **Combinación:** Puedes *combinar* **ambos** estilos.

---

## 3. Listas (Ordenadas y Desordenadas)

### Lista Desordenada (Viñetas)

Usa un guion (`-`), un asterisco (`*`) o un signo de más (`+`).

* Primer elemento.
* Segundo elemento.
    * Sub-elemento con indentación (deja un espacio extra).
* Tercer elemento.

### Lista Ordenada (Números)

Simplemente usa números seguidos de un punto. Markdown se encarga de ordenarlos automáticamente.

1.  Primer paso.
2.  Segundo paso importante.
3.  Tercer paso (aunque ponga 1. otra vez, saldrá 3).
1.  Paso final.

---

## 4. Enlaces (Links)

Se utiliza la sintaxis `[Texto Visible](URL)`.

* [Visita mi perfil de GitHub](https://github.com/TuUsuario)
* [Enlace a la documentación de Git](https://git-scm.com/)

---

## 5. Código y Bloques de Cita

### Código en Línea (Inline Code)

Para mencionar comandos o nombres de variables dentro de una frase, usa la tilde invertida (`).

Recuerda siempre ejecutar el comando `git add .` antes de crear tu commit.

### Bloque de Código (Code Block)

Para mostrar varios comandos o un fragmento de código más largo, usa tres tildes invertidas seguidas (```). Puedes especificar el lenguaje para el resaltado de sintaxis (ej. `bash`).

```bash
# Ejemplo de comandos
git status
git add .
git commit -m "Mi commit de prueba"
git push# RepositorioDePruebas