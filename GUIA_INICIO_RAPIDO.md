# Guía de Inicio Rápido - Sistema de Arqueo de Fuentes

Esta guía le ayudará a comenzar a usar el sistema de arqueo de fuentes para tesis doctorales.

## ¿Qué es el Arqueo de Fuentes?

El arqueo de fuentes es un sistema de documentación que registra y organiza todas las fuentes bibliográficas utilizadas en las tesis doctorales. Proporciona:

- 📚 Registro completo de información bibliográfica
- 🔗 Trazabilidad entre tesis y sus fuentes
- 🔍 Búsqueda por autor, tema y tipo
- 📝 Plantillas estandarizadas
- ✅ Cumplimiento de normas académicas

## Primeros Pasos

### 1. Explorar el Sistema

Comience revisando estos archivos:

1. **[README.md](./README.md)** - Visión general del repositorio
2. **[arqueo/arqueo_fuentes.md](./arqueo/arqueo_fuentes.md)** - Registro principal de fuentes
3. **[tesis/T001_Ejemplo_2026/](./tesis/T001_Ejemplo_2026/)** - Ejemplo de tesis

### 2. Consultar Fuentes Existentes

Para buscar fuentes ya documentadas:

- **Por ID**: Busque directamente en `arqueo/arqueo_fuentes.md` usando F###
- **Por Autor**: Consulte `arqueo/indice_por_autor.md`
- **Por Tema**: Consulte `arqueo/indice_por_tema.md`

### 3. Agregar una Nueva Fuente

Siga estos pasos para documentar una nueva fuente:

#### Paso 1: Obtener información bibliográfica
Recopile toda la información de la fuente:
- Título, autor(es), año, editorial
- ISBN/DOI si está disponible
- Ubicación física o digital

#### Paso 2: Usar la plantilla
Abra `arqueo/plantilla_fuente.md` y copie el formato

#### Paso 3: Asignar ID
- Use el siguiente número disponible (ej. F002, F003, etc.)
- Verifique el último ID en `arqueo/arqueo_fuentes.md`

#### Paso 4: Completar información
Llene todos los campos aplicables:
```
ID: F002
Título: [Título completo]
Autor(es): [Apellido, Nombre]
Año: [Año de publicación]
...
```

#### Paso 5: Agregar al registro
Agregue su entrada al archivo `arqueo/arqueo_fuentes.md`

#### Paso 6: Actualizar índices
- Agregue el autor a `indice_por_autor.md`
- Agregue el tema a `indice_por_tema.md`

### 4. Registrar una Nueva Tesis

Para documentar una tesis doctoral:

#### Paso 1: Crear directorio
```
tesis/T###_ApellidoAutor_Año/
```
Ejemplo: `tesis/T002_Lopez_2026/`

#### Paso 2: Copiar estructura
Use `tesis/T001_Ejemplo_2026/` como plantilla:
- README.md - Información completa de la tesis
- resumen.md - Resumen ejecutivo
- fuentes_citadas.md - Lista de fuentes utilizadas

#### Paso 3: Completar información
Llene todos los archivos con la información de la tesis

#### Paso 4: Vincular fuentes
En `fuentes_citadas.md`, liste todas las fuentes usando sus IDs del arqueo

#### Paso 5: Actualizar arqueo
En cada fuente citada, agregue el ID de la tesis al campo "Tesis Asociadas"

## Flujo de Trabajo Típico

### Escenario: Documentar una Tesis Nueva

1. **Leer la tesis** y identificar todas las referencias bibliográficas
2. **Verificar en el arqueo** cuáles fuentes ya están documentadas
3. **Agregar fuentes nuevas** siguiendo el proceso descrito arriba
4. **Crear entrada de tesis** con toda su información
5. **Vincular tesis y fuentes** actualizando referencias cruzadas
6. **Actualizar índices** para facilitar búsquedas futuras

### Ejemplo Práctico

Supongamos que tiene una tesis que cita 5 libros:

1. **Verificación**: 2 libros ya están en el arqueo (F001, F005)
2. **Documentación**: Agregue los 3 libros nuevos (F010, F011, F012)
3. **Registro de tesis**: Cree T002 con README completo
4. **Vincular**: En la tesis, liste F001, F005, F010, F011, F012
5. **Actualizar**: En cada fuente, agregue T002 como tesis asociada
6. **Índices**: Agregue los nuevos autores y temas a los índices

## Mejores Prácticas

### ✅ Hacer

- Verificar duplicados antes de agregar una fuente
- Usar información bibliográfica completa y precisa
- Mantener consistencia en el formato
- Actualizar todos los índices al agregar entradas
- Respetar derechos de autor (solo extractos breves)

### ❌ Evitar

- Agregar fuentes incompletas
- Omitir campos requeridos
- Crear IDs duplicados
- Olvidar actualizar índices
- Almacenar copias completas de obras protegidas

## Convenciones de Nomenclatura

### Tesis
- **ID**: T### (T001, T002, ...)
- **Directorio**: T###_Apellido_Año
- **Ejemplo**: T005_Martinez_2025

### Fuentes
- **ID**: F### (F001, F002, ...)
- **Directorio**: tipo/año/F###_Apellido_PalabraClave
- **Ejemplo**: libros/2020/F025_Smith_DataScience

### Tipos de Fuente
- **L**: Libros
- **A**: Artículos
- **T**: Tesis
- **C**: Conferencias
- **W**: Web
- **D**: Documentos Técnicos

## Recursos Adicionales

- **Plantilla de fuente**: `arqueo/plantilla_fuente.md`
- **Ejemplo completo**: `tesis/T001_Ejemplo_2026/`
- **Guía de tesis**: `tesis/README.md`
- **Guía de fuentes**: `fuentes/README.md`
- **Guía del arqueo**: `arqueo/README.md`

## Soporte

Si tiene preguntas o necesita ayuda:

1. Consulte los archivos README en cada directorio
2. Revise los ejemplos proporcionados
3. Contacte al administrador del repositorio

## Checklist para Nueva Entrada

Use esta lista de verificación al agregar contenido:

### Para una nueva fuente:
- [ ] Información bibliográfica completa
- [ ] ID único asignado (F###)
- [ ] Entrada agregada a arqueo_fuentes.md
- [ ] Autor agregado a indice_por_autor.md
- [ ] Tema agregado a indice_por_tema.md
- [ ] Directorio creado en fuentes/ (opcional)

### Para una nueva tesis:
- [ ] Directorio creado con formato correcto
- [ ] README.md completo
- [ ] resumen.md completo
- [ ] fuentes_citadas.md completo
- [ ] Todas las fuentes citadas documentadas en arqueo
- [ ] Referencias cruzadas actualizadas
- [ ] Tesis agregada al índice en tesis/README.md

---
*Versión: 1.0*  
*Última actualización: 2026-01-21*
