# Apuntes – Vocabulary I: Technological Devices  

## A. Configuración Inicial y Gestión de Remotos (Terminal)

Este documento explica cómo clonar el repositorio del compañero, configurar el usuario local, verificar los remotos existentes, crear un repositorio personal en GitHub, agregarlo como remoto, eliminar el remoto original y confirmar el resultado final.

---

### 1️ Clonar el repositorio del compañero
```bash
git clone URL_repositorio_del_compañero
cd nombre_repositorio
```

---

### 2️ Configurar el usuario local
```bash
git config user.name "Tu Nombre"
git config user.email "tu.email@ejemplo.com"
```

---

### 3️ Ver repositorios remotos actuales
```bash
git remote -v
```
Salida esperada:
```
origin (fetch)
origin (push)
```

---

### 4️ Crear repositorio personal en GitHub
- Ir a GitHub
- Crear un repositorio vacío (sin README ni licencia)
- Copiar la URL

---

### 5️ Añadir el repositorio personal como nuevo remoto
```bash
git remote add mirepositorio URL_de_tu_nuevo_repositorio
```

---

### 6️ Eliminar el remoto original
```bash
git remote remove origin
```

---

### 7️ Ver repositorios remotos finales
```bash
git remote -v
```
Salida esperada:
```
mirepositorio (fetch)
mirepositorio (push)
```

---

## Tabla resumen de comandos
| Acción | Comando |
|--------|---------|
| Clonar repositorio | `git clone` |
| Configurar usuario | `git config` |
| Ver remotos | `git remote -v` |
| Añadir remoto | `git remote add` |
| Eliminar remoto | `git remote remove` |
