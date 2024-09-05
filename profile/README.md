<p>
<img align="left" width="125" height="125" src="https://avatars.githubusercontent.com/u/174350723?s=200&v=4">
<h3 align="center">
  Project Presentium
</h3>

<p align="center">
  Scalable presence control system using RFID student cards.
  <br/><br/>
  <img src="https://img.shields.io/badge/license-MIT-darkgreen" alt="License" />
</p>
</p>

---

## Context

Presentium is a group project done as part of the PDG class of HEIG-VD, Switzerland. 

The goal of the project is to streamline taking student attendance using RFID student cards.
The project is developed as mandated by the [Project Description](https://github.com/presentium/meta/wiki/Project-Description).

The complete documentation about the project, its structure, and its components can be found in the [Wiki][meta-wiki].

## Project Structure

The project is divided into several repositories, the main components are described below:

- [Meta][repo-meta]: Repository containing the project's documentation and general information.
- [Dashboard][repo-dashboard]: The dashboard application for teachers and students.
- [API][repo-api]: The backend API handling communication with reader devices and data for the dashboard.
- [Infrastructure][repo-infra]: The infrastructure as code of the project, deploying the dashboard application and required services on AWS.
- [Kubernetes][repo-k8s]: The kubernetes files managed by ArgoCD for deploying the application and infrastructure.
- [Operating System][repo-os] (OS): The operating system running on the Raspberry Pi.
- [Landing][repo-landing]: The landing page for the project.
- [Client app][repo-client-app]: The client app used to connect to the API on reader devices.
- [APT repository][repo-deb]: A repository serving as an APT repository for reader devices.

Other repositories may be created for specific components or features, their usecases should be detailed in their description as well as in the [Wiki][meta-wiki].

## Contributing

Please refer to the [Contributing Guide][contributing] before making a pull request.

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Lutonite"><img src="https://avatars.githubusercontent.com/u/21953109?v=4?s=100" width="100px;" alt="Loïc H."/><br /><sub><b>Loïc H.</b></sub></a><br /><a href="https://github.com/presentium/app/commits?author=Lutonite" title="Code">💻</a> <a href="https://github.com/presentium/app/commits?author=Lutonite" title="Documentation">📖</a> <a href="https://github.com/presentium/app/commits?author=Lutonite" title="Tests">⚠️</a> <a href="https://github.com/presentium/app/pulls?q=is%3Apr+reviewed-by%3ALutonite" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/DACC4"><img src="https://avatars.githubusercontent.com/u/46499354?v=4?s=100" width="100px;" alt="Christophe - CC4"/><br /><sub><b>Christophe - CC4</b></sub></a><br /><a href="#tool-DACC4" title="Tools">🔧</a> <a href="#platform-DACC4" title="Packaging/porting to new platform">📦</a> <a href="#infra-DACC4" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/spiritclaw"><img src="https://avatars.githubusercontent.com/u/46258367?v=4?s=100" width="100px;" alt="Léa"/><br /><sub><b>Léa</b></sub></a><br /><a href="#infra-spiritclaw" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="https://github.com/presentium/app/commits?author=spiritclaw" title="Tests">⚠️</a> <a href="#tool-spiritclaw" title="Tools">🔧</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/massteff"><img src="https://avatars.githubusercontent.com/u/42839432?v=4?s=100" width="100px;" alt="massteff"/><br /><sub><b>massteff</b></sub></a><br /><a href="https://github.com/presentium/app/commits?author=massteff" title="Code">💻</a> <a href="https://github.com/presentium/app/commits?author=massteff" title="Documentation">📖</a> <a href="https://github.com/presentium/app/commits?author=massteff" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Mystere98"><img src="https://avatars.githubusercontent.com/u/38164068?v=4?s=100" width="100px;" alt="Mystere"/><br /><sub><b>Mystere</b></sub></a><br /><a href="#infra-Mystere98" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#security-Mystere98" title="Security">🛡️</a> <a href="#tool-Mystere98" title="Tools">🔧</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

[repo-meta]: https://github.com/presentium/meta
[repo-dashboard]: https://github.com/presentium/dashboard
[repo-api]: https://github.com/presentium/api
[repo-infra]: https://github.com/presentium/infrastructure
[repo-os]: https://github.com/presentium/os
[repo-landing]: https://github.com/presentium/landing
[repo-client-app]: https://github.com/presentium/rpi-client-app
[repo-deb]: https://github.com/presentium/deb
[repo-k8s]: https://github.com/presentium/kubernetes

[meta-wiki]: https://github.com/presentium/meta/wiki

[contributing]: https://github.com/presentium/meta/blob/main/CONTRIBUTING.md
[bill-of-specs]: https://github.com/presentium/meta/wiki/Cahier-des-charges
