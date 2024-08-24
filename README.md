# Marshallect
Marshal + Collect | Materials download commands

### Require commands
- `wget`
- `curl`
- `zip`

### How to use
1. Search links that you want in this repository  
e.g. `https://github.com/lemon73-computing/marshallect/blob/main/docs/copyright-text_japan-gov-bunka.sh`
1. Get raw links
e.g. `https://raw.githubusercontent.com/lemon73-computing/marshallect/main/docs/copyright-text_japan-gov-bunka.sh`
1. Move this command on your bash
    ```bash
    sh  <(curl "Raw URL")

    # e.g.
    # sh <(curl https://raw.githubusercontent.com/lemon73-computing/marshallect/main/docs/copyright-text_japan-gov-bunka.sh)
    ```
