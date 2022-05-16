# dk

**dk** is a shortcut to some useful docker commands.

other docker commands should work too: `dk pull ubuntu`

- list images: `dk ls`
- list active containers: `dk ps`
- shell into `<img>`: `dk sh ubuntu`
- create volume with current dir and sh `<img>`: `dk bind ubuntu`
- export `<image>` to *.tar.gz: `dk gz docker/getting-started`
- import `<image.tar.gz>`: `dk add docker_getting-started.tar.gz`
- monitoring containers with ctop: `dk mon`
- cleanup unused resources: `dk clean`
  - stopped containers
  - `<none>` images
  - dangling images
  - unused networks
  - unused local volumes

