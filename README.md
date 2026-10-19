# Sonic Robo Blast 2 en Español

Portal principal y centro de distribución de la traducción y recompilación al español de **Sonic Robo Blast 2** (v2.2.15) para **Windows**, **Linux** y **Android**.

---

## Sobre el Proyecto

A diferencia de los mods tradicionales basados en scripts de Lua o SOC, esta adaptación está realizada **directamente en el código fuente C del motor**.

- **Compatibilidad Online Total**: Puedes unirte y jugar en servidores vanilla oficiales o comunitarios sin sufrir desincronizaciones (`Consistency failure`) y sin requerir que los demás jugadores tengan la traducción instalada.
- **Tipografía con Soporte Completo en Español**: Incorpora glifos de formato *Doom Patch* para tildes (á, é, í, ó, ú), eñes (ñ, Ñ) y signos de apertura (¿, ¡) en las fuentes del HUD (`STCFN`) y de los títulos de nivel (`LTFNT`).
- **100% de la experiencia traducida**: Menús, tutorial completo de Amy Rose, selector de niveles, descripciones de personajes, pistas de emblemas (haikus), intro, créditos y multijugador.

---

## Plataformas Disponibles y Enlaces

Selecciona tu plataforma para acceder a su repositorio específico, instrucciones detalladas de instalación y descargas:

| Plataforma | Repositorio Oficial | Descargas / Releases | Contenido y Características |
| :--- | :--- | :--- | :--- |
| **Windows** (64-bit) | [**SRB2-Spanish-Recomp**](https://github.com/trulydza/SRB2-Spanish-Recomp) | [Última versión](https://github.com/trulydza/SRB2-Spanish-Recomp/releases/latest) | Ejecutable compilado de 64 bits (`srb2win_es.exe`), DLLs modernas actualizadas y lanzador directo `Jugar_online.bat`. |
| **Linux** (64-bit) | [**SRB2-Spanish-Recomp-Linux**](https://github.com/trulydza/SRB2-Spanish-Recomp-Linux) | [Última versión](https://github.com/trulydza/SRB2-Spanish-Recomp-Linux/releases/latest) | Binario nativo ELF (`srb2linux_es`), paquete comprimido `.tar.gz` y script lanzador `Jugar_online.sh` compatible con Arch, CachyOS, Debian, Ubuntu y Flatpak. |
| **Android** (arm64) | [**SRB2-Spanish-Recomp-Android**](https://github.com/trulydza/SRB2-Spanish-Recomp-Android) | [Última versión](https://github.com/trulydza/SRB2-Spanish-Recomp-Android/releases/latest) | Paquete instalable (`.apk`), controles táctiles virtuales en pantalla, render por hardware OpenGL ES (`gl4es`) a 60/90/120 FPS y addon gráfico integrado. |

---

## Archivos de Datos Base (`.pk3`)

Por motivos de derechos de autor (propiedad intelectual de SEGA y Sonic Team Junior sobre música, mapas y gráficos), ninguna versión distribuye empaquetados los 4 archivos comerciales del juego:

- `srb2.pk3`
- `zones.pk3`
- `characters.pk3`
- `music.pk3`

### ¿Cómo obtenerlos gratis?
1. **Si ya juegas en PC:** Copia estos 4 archivos desde tu carpeta de instalación de SRB2 a la carpeta de tu nueva versión (o a `/sdcard/SRB2/` en Android).
2. **Si no tienes el juego:** Descarga el archivo oficial para Windows/PC desde la web oficial de [Sonic Team Junior](https://www.srb2.org/download/) y extrae únicamente esos 4 archivos `.pk3`.

---

## Addon Gráfico Cosmético (`srb2_spanish_gfx.pk3`)

Para disfrutar de los acentos en títulos de zonas y menús, se utiliza el complemento gráfico `srb2_spanish_gfx.pk3`. 
- En **Windows** y **Linux**, se incluye en las descargas dentro de la carpeta `addons/` y se carga con los lanzadores `Jugar_online`.
- En **Android**, viene **preinstalado de fábrica** dentro del propio APK.
- Dado que solo contiene reemplazos de sprites y fuentes cosméticas dentro de la lista blanca del motor (`W_VerifyNMUSlumps`), es **100% seguro para jugar en línea**.

---

## Documentación y Desarrollo

Si te interesa la arquitectura técnica, las reglas de traducción en C, el control de anchos de fuentes o compilar desde el código fuente, consulta la [`GUIA.md`](https://github.com/trulydza/SRB2-Spanish-Recomp/blob/main/GUIA.md) en el repositorio central de desarrollo.

---

## Créditos

- **Traducción, adaptación y ports:** Daza ([@trulydza](https://github.com/trulydza))
- **Juego base y motor original:** Sonic Team Junior ([STJr/SRB2](https://github.com/STJr/SRB2))
- **Port Android de referencia:** [thegreatbbd94-ux](https://github.com/thegreatbbd94-ux/SRB2-Android-Port) y equipo de SRB2-Mobile
- **Capa OpenGL ES:** gl4es por ptitSeb

*Licencia GPL-2.0, en concordancia con el proyecto original Sonic Robo Blast 2.*
