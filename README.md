# RaggieSoft Nginx Server Configurations (`/nginx-config`)

Declarative Nginx reverse-proxy and virtual host configurations for the RaggieSoft DigitalOcean Droplet (`NYC1` — `142.93.244.239` / `2604:a880:400:d1:0:4:c8de:7001`).

## Virtual Host Configurations

| Configuration File | Domain | Web Root | Upstream Stack |
| :--- | :--- | :--- | :--- |
| [`michaelpragsdale.com.conf`](./michaelpragsdale.com.conf) | `michaelpragsdale.com` | `/var/www/michaelpragsdale.com` | Angular 19 Zoneless Signals + Native CSS (`raggiesoft-portfolio`) |
| [`raggiesoft.com.conf`](./raggiesoft.com.conf) | `raggiesoft.com` | `/var/www/raggiesoft.com` | PHP 8.5-FPM (`elara.php` Front-Controller / `raggiesoft-hub`) |
| [`music.raggiesoft.com.conf`](./music.raggiesoft.com.conf) | `music.raggiesoft.com` | `/var/www/music.raggiesoft.com` | Svelte 5 + SvelteKit 2 Static PWA (`raggiesoft-music`) |
| [`books.raggiesoft.com.conf`](./books.raggiesoft.com.conf) | `books.raggiesoft.com` | `/var/www/raggiesoft-book-library` | PHP 8.5-FPM (`isabel.php` Router / `raggiesoft-book-library`) |
| [`lore.raggiesoft.com.conf`](./lore.raggiesoft.com.conf) | `lore.raggiesoft.com` | `/var/www/lore.raggiesoft.com` | Next.js Static Export (`raggiesoft-lore`) |
| [`nebulae.raggiesoft.com.conf`](./nebulae.raggiesoft.com.conf) | `nebulae.raggiesoft.com` | `/var/www/nebulae.raggiesoft.com` | PHP 8.5-FPM (`lyra.php` Router / `raggiesoft-nebulae`) |

## License

- **Configuration Code:** [MIT License](./LICENSE)

