tsv-jtf2025-web
===============

[![hugo-deploy](https://github.com/langchr86/tsv-jtf2025-web/actions/workflows/hugo-deploy.yml/badge.svg)](https://github.com/langchr86/tsv-jtf2025-web/actions/workflows/hugo-deploy.yml)

Das ist das [Hugo](https://gohugo.io)-Projekt für den Webauftritt des Jugendturnfest 2025 im Mettauertal.

Der Webauftritt ist erreichbar unter: [jtf2025.ch](https://jtf2025.ch).


Entwicklung
-----------

Installier Hugo z.B. unter Windows mit [Chocolatey](https://chocolatey.org/):

~~~~~~
choco install -y hugo-extended
~~~~~~

Nun kann lokal gearbeitet werden und mittels `hugo server` eine Server-Instanz gestartet werden,
die unter [localhost:1313](http://localhost:1313) erreichbar ist.
Diese aktualisiert sich bei den meisten Änderungen im Projekt automatisch.

Dokumentation:

* https://blowfish.page/docs/homepage-layout/
* https://blowfish.page/docs/shortcodes/
* https://bootstrapshuffle.com/de/classes


Deployment
----------

Das Deployment auf den echten Web-Server passiert automatisch bei einem Push auf den `master`-Branch
durch die Github-Action: [hugo-deploy.yml](.github/workflows/hugo-deploy.yml)
