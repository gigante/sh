# sam

ssh agent manager

- lists fingerprints of all added keys: `sam ls`
- add <key> (private key) to agent: `sam add default_key`
- delete <key> from the agent: `sam rm default_key`
- load all available keys to agent: `sam all`
- remove all keys from the agent: `sam clean`
- copy <key> (public key) to clipboard: `sam copy default_key`
- fix ~/.ssh permissions: `sam fix`
- generate ssh key pair in interactive mode (rsa 4096): `sam gen example@mail.com`
- upload pub <key> to a remote server: `sam deploy default_key user@host`
