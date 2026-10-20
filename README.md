# Director de arte — skill para Claude

Hace que Claude trabaje como director de arte antes de diseñar: posters, menús, posts, carruseles, presentaciones,
páginas y videos.

En vez de diseñar lo primero que se le ocurre:

1. **Te entrevista**, una pregunta a la vez: para quién es, qué quieres que sientan, qué estilo seguir.
2. **Busca referencias reales** en la web.
3. **Te propone 3 direcciones** visuales para que elijas.
4. **Consigue las fotos** o el b-roll.
5. **Diseña.**
6. **Se revisa con capturas** y corrige sus errores antes de entregarte.

## Instalar

### En la app de Claude (web o escritorio)

1. Descarga **[director-de-arte.zip](https://github.com/Diegosalcedo05/director-de-arte/releases/latest/download/director-de-arte.zip)**. No lo descomprimas.
2. En Claude ve a **Customize → Skills** (Personalizar → Skills si la tienes en español).
3. Toca **+ → Create skill → Upload a skill** y elige el `.zip`.
4. Revisa que quede activada.

Si no te aparece la sección de Skills, activa la ejecución de código en la configuración de Claude.

### En Claude Code

Pídeselo tal cual:

> instala esta skill: https://github.com/Diegosalcedo05/director-de-arte

O en la terminal:

```bash
git clone https://github.com/Diegosalcedo05/director-de-arte ~/.claude/skills/director-de-arte
```

## Usarla

No tienes que llamarla. Pide cualquier diseño ("hazme el menú de mi restaurante", "una presentación para mi junta",
"que mi página no se vea hecha con IA") y Claude la usa sola. Contesta sus preguntas; si le dices "tú decide", se salta
la entrevista y decide con criterio.

---

Hecha por [@diegosalcedo_ia](https://www.instagram.com/diegosalcedo_ia/).
