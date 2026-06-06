# Cómo activar el README de perfil en GitHub

## Qué es

GitHub permite mostrar un README en tu perfil público si creas un repositorio
especial cuyo nombre coincide exactamente con tu nombre de usuario.

Para ti el repositorio debe llamarse: **`JeroHoyos`**

## Pasos

### 1. Crear el repositorio especial

1. Ve a https://github.com/new
2. En *Repository name* escribe exactamente: `JeroHoyos`
3. Marca **Public**
4. Marca **Add a README file** (o déjalo vacío, da igual)
5. Clic en **Create repository**

GitHub mostrará el mensaje:
> ✨ `JeroHoyos/JeroHoyos` is a special repository...

### 2. Subir el README

Opción A — desde la web:
1. Abre el repositorio recién creado
2. Clic en el lápiz para editar `README.md`
3. Pega el contenido del archivo `README.md` de esta carpeta
4. Clic en **Commit changes**

Opción B — desde terminal:
```bash
git clone https://github.com/JeroHoyos/JeroHoyos.git
cd JeroHoyos
# copia el README.md de esta carpeta aquí
cp /ruta/a/github/README.md ./README.md
git add README.md
git commit -m "add profile README"
git push
```

### 3. Verificar

Ve a https://github.com/JeroHoyos — el README aparecerá automáticamente
en tu perfil público.

---

## Notas

- **GitHub Stats**: Las tarjetas de estadísticas usan
  [github-readme-stats](https://github.com/anuraghazra/github-readme-stats).
  No requieren configuración adicional — se generan en tiempo real.

- **Badges**: Todos los badges usan [shields.io](https://shields.io) y se
  renderizan automáticamente. No necesitas subir ningún archivo extra.

- **Actualizaciones**: Cada vez que hagas push al repositorio `JeroHoyos/JeroHoyos`
  el perfil se actualiza de inmediato.
