# Homer Theme

Custom Theme for [Homer](https://github.com/bastienwirtz/homer) inspired by [Walkx](https://github.com/walkxhub/homer-theme).

# Install

1. Download/Clone this repository: `git clone https://github.com/RanzigeButter/homer-theme`
2. Get the mapped `assets` directory path from Homer: `docker inspect -f '{{ .Mounts }}' homer`
3. (Optional) Backup the existing `assets` directory: `mv assets assets-backup`
4. Copy the `assets` directory from the repository to the `assets` directory of Homer.
5. Add your services in `config.yml`.
