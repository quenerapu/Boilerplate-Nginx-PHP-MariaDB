# Boilerplate para crear proyectos Nginx + PHP + MariaDB

Just add water.

1. Instala [Podman]
2. Instala [Mkcert]
3. Clona este repositorio en tu máquina
4. Abre tu terminal (Terminal en Linux o macOS, PowerShell en Windows), ve a la carpeta donde has descargado este repositorio
5. Dentro del directorio certs ejecuta `mkcert localhost 127.0.0.1 ::1` para crear los certificados `localhost+2.pem` y `localhost+2-key.pem`
6. Dentro dle directorio principal (donde están `Dockerfile` y `docker-compose.yml`), ejecuta `podman compose up`
7. Hala, construye algo chulo

¿Dudas? [Pregúntale a Gemini].

[Podman]: https://podman.io/docs/installation
[Mkcert]: https://dev.to/aschmelyun/using-the-magic-of-mkcert-to-enable-valid-https-on-local-dev-sites-3a3c
[Pregúntale a Gemini]: https://gemini.google.com/
