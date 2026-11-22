# images

Docker-images als gewone download, voor wie geen `docker pull` kan of wil gebruiken.

| Image | Download | Bron |
|---|---|---|
| `optio-agent-base` | [optio-agent-base.tar.gz](https://github.com/JPGallas/images/releases/download/optio-agent-base/optio-agent-base.tar.gz) ([release](https://github.com/JPGallas/images/releases/tag/optio-agent-base)) | `ghcr.io/jonwiggins/optio-agent-base:latest`, van [jonwiggins/optio](https://github.com/jonwiggins/optio) (MIT) |

Gebruiken:

```sh
docker load -i optio-agent-base.tar.gz
```

## Bijwerken

De tar wordt gemaakt door een GitHub Action ([.github/workflows/optio-agent-base.yml](.github/workflows/optio-agent-base.yml)): die haalt het image op, slaat het op als gecomprimeerde tar en zet die met een checksum en de licentie in de release. Starten: tabblad **Actions** → **optio-agent-base als download** → **Run workflow**. De downloadlink blijft daarbij hetzelfde.
