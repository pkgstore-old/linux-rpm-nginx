# Nginx

**Nginx** is a web server and a reverse proxy server for HTTP, SMTP, POP3 and IMAP protocols, with a strong focus on high concurrency performance and low memory usage.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/nginx
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y nginx
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/nginx).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/nginx) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.
