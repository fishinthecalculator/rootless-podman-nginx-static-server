# Nginx Rootless Podman Static Files Server 🦭

Small boilerplate for static serving the `./data` directory.

1. Create `data` dir.
2. Put files inside, something like `echo hello world > data/index.html`
3. `podman compose up -d`

#### Autoindex

If nginx should autoindex (show the content of a directory) remove the comment in the `nginx.conf` file.
