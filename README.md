# RaggieSoft Nginx Server Configurations (`/nginx-config`)

[![License: MIT](https://img.shields.io/badge/Configuration_License-MIT-0369a1.svg)](./LICENSE)
[![Server: Nginx + PHP 8.5-FPM + TLS 1.3](https://img.shields.io/badge/Server-Nginx_%2B_PHP_8.5--FPM-009639.svg)](https://michaelpragsdale.com/build-team/jessica)

Declarative Nginx virtual host, edge `301` redirect, Content Security Policy (CSP), and static caching configurations powering all **11 live web properties** on the hardened Ubuntu production host (`NYC1`).

## Production Virtual Host Matrix (11 Properties)

| Configuration File | Canonical Domain | Server Root | Upstream Architecture |
| :--- | :--- | :--- | :--- |
| [`michaelpragsdale.com.conf`](./michaelpragsdale.com.conf) | `michaelpragsdale.com` | `/var/www/michaelpragsdale.com` | Angular 19 Zoneless Signals + Native CSS (`raggiesoft-portfolio`) |
| [`raggiesoft.com.conf`](./raggiesoft.com.conf) | `raggiesoft.com` | `/var/www/raggiesoft.com` | PHP 8.5-FPM (`elara.php` Front-Controller / `raggiesoft-hub`) |
| [`corporate.raggiesoft.com.conf`](./corporate.raggiesoft.com.conf) | `corporate.raggiesoft.com` | `/var/www/corporate.raggiesoft.com` | Bootstrap 5.3.8 Static SSG (`raggiesoft-corporate`) |
| [`engineroom.raggiesoft.com.conf`](./engineroom.raggiesoft.com.conf) | `engineroom.raggiesoft.com` | `/var/www/engineroom.raggiesoft.com` | Astro 6 Multi-Tenant Static SSG (`raggiesoft-engine-room-records`) |
| [`music.raggiesoft.com.conf`](./music.raggiesoft.com.conf) | `music.raggiesoft.com` | `/var/www/music.raggiesoft.com` | SvelteKit 2 + Svelte 5 Runes Static PWA (`raggiesoft-music`) |
| [`stardust.raggiesoft.com.conf`](./stardust.raggiesoft.com.conf) | `stardust.raggiesoft.com` | `/var/www/stardust.raggiesoft.com` | Nuxt 4 + Vue 3 Static SSG (`raggiesoft-stardust-engine`) |
| [`books.raggiesoft.com.conf`](./books.raggiesoft.com.conf) | `books.raggiesoft.com` | `/var/www/raggiesoft-book-library` | PHP 8.5-FPM + ES2024 Reading PWA (`raggiesoft-book-library`) |
| [`backstage.raggiesoft.com.conf`](./backstage.raggiesoft.com.conf) | `backstage.raggiesoft.com` | `/var/www/backstage.raggiesoft.com` | Web Awesome 3.13 SSG & Static CORS JSON API (`raggiesoft-backstage`) |
| [`lore.raggiesoft.com.conf`](./lore.raggiesoft.com.conf) | `lore.raggiesoft.com` | `/var/www/lore.raggiesoft.com` | Next.js 16 + React 19 Static Export (`raggiesoft-lore`) |
| [`nebulae.raggiesoft.com.conf`](./nebulae.raggiesoft.com.conf) | `nebulae.raggiesoft.com` | `/var/www/nebulae.raggiesoft.com` | PHP 8.5-FPM + ES2024 Canvas Visualizer (`raggiesoft-nebulae`) |
| [`storetrainer.raggiesoft.com.conf`](./storetrainer.raggiesoft.com.conf) | `storetrainer.raggiesoft.com` | `/var/www/storetrainer.raggiesoft.com` | TypeScript + Classic Win32 Static SSG (`raggiesoft-storetrainer`) |

## License

- **Configuration Code:** [MIT License](./LICENSE)
