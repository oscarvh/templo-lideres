# 🏛️ Viaje al Templo – Guía del Facilitador

Una aplicación web progresiva (**PWA**) diseñada específicamente para los líderes de jóvenes de La Iglesia de Jesucristo de los Santos de los Últimos Días, con el fin de facilitar el manejo del itinerario durante el retiro espiritual "Viaje al Templo" (Marzo 2026).

---

## 🌟 Características principales

-   **📱 Funcionamiento Offline (PWA):** Una vez abierta por primera vez con internet, la aplicación se puede instalar en el celular y funciona sin conexión (ideal para zonas con poca señal).
-   **📅 Itinerario por días:** Separación clara entre el Lunes, Martes y Miércoles.
-   **📑 Módulos detallados:** Cada sección incluye su propósito, escrituras con texto completo, dinámicas, himnos y notas para el líder.
-   **🎵 Himnario integrado:** Todas las letras de los himnos necesarios para las reuniones y reflexiones.
-   **🎯 Dinámicas y Juegos:** Instrucciones paso a paso para juegos PFJ (Dos Verdades, Nudo Humano, Desafío de Escrituras).

---

## 🛠️ Tecnologías utilizadas

-   **Frontend:** React + Vite + TypeScript
-   **Estilos:** Tailwind CSS
-   **Iconos:** Lucide React
-   **PWA Corazón:** `vite-plugin-pwa` para almacenamiento en caché de activos y service worker.
-   **Despliegue:** Preparado para servidores Apache (Hostinger) y GitHub Pages.

---

## 🚀 Guía de Instalación (Para Líderes)

Para tener la guía siempre disponible en el celular sin depender de internet:

1.  Abre la URL en tu navegador (Chrome en Android o Safari en iOS).
2.  Toca el menú del navegador y selecciona **"Instalar aplicación"** o **"Agregar a la pantalla de inicio"**.
3.  ¡Listo! Aparecerá un icono en tu pantalla de inicio que podrás abrir incluso sin señal.

---

## 💻 Desarrollo y Despliegue

### Clonar repositorio:
```bash
git clone https://github.com/oscarvh/viaje-al-templo-guide.git
```

### Comandos útiles:
-   `npm run dev`: Para ver el sitio en modo desarrollo.
-   `npm run build`: Genera la versión final en la carpeta `dist/`.

### Configuración de despliegue:
Esta aplicación se despliega actualmente en la subruta `/templo-lideres/` siguiendo la configuración de `vite.config.ts`. Si deseas cambiar la ubicación, recuerda actualizar el `base path`.

---

🎉 *Que este recurso sea de gran bendición para fortalecer la fe de los jóvenes.* 🎉
