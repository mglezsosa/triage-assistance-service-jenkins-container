# Jenkins container for the CI of the [triage assistance service](https://github.com/mglezsosa/triage-assistance-service) development

## Fresh installation

1. Rename `secrets/adminpw.example` to `secrets/adminpw`:
    ```bash
    $ mv secrets/adminpw.example secrets/adminpw
    ```
    The credentials will be "admin" as the user and the password provided in `secrets/adminpw`.
2. Give the appropiate permissions to `install.sh` with:
    ```bash
    $ chmod +x install.sh
    ```
3. Run the installation script with:
    ```bash
    $ ./install.sh
    ```

After this, you will have a new Jenkins instance up and running in [`http://localhost:8081/`](http://localhost:8081/).