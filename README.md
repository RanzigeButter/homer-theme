<h1 align="center">Homer Theme</h1>

<p align="center">
  Theme for <a href="https://github.com/bastienwirtz/homer">Homer</a> inspired by <a href="https://github.com/walkxhub/homer-theme">Walkx</a>.
</p>

<p align="center">
  <a aria-label="License" href="https://github.com/timschneiderxyz/homer-theme/blob/main/LICENSE">
    <img alt="" src="https://img.shields.io/badge/license-mit-689d6a?style=for-the-badge&labelColor=000000">
  </a>
</p>

## Install

1. Download/Clone this repository: `git clone https://github.com/timschneiderxyz/homer-theme`
2. Get the mapped `assets` directory path from Homer: `docker inspect -f '{{ .Mounts }}' homer`
3. Copy the `assets` directory from the repository to the mapped `assets` directory of Homer.
4. Add your services in `config.yml`.

You can find a collection of logos [here](https://github.com/timschneiderxyz/assets/tree/main/logos).
