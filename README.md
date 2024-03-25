# DevDocker - Docker container for C++ programming

## Installation

- Install **Docker Desktop** 
    - https://docs.docker.com/desktop/mac/apple-silicon/
- Run **Docker.app**
    - Grant privileges if necessary.
    - Docker Desktop must be running when using the container.
- Open a shell with your **root working directory**
    - The folder must not contain a file named `Dockerfile`.
- Run this command in your **root working directory**
    ```
    curl https://raw.githubusercontent.com/josefhammer/devdocker/main/build-devdocker.sh | bash
    ```

## Usage

- Run the newly created **launch script** in your **root working directory**

        ./run-devdocker.sh

    - This folder will be available within the container at `/home/devd/dev`.
    - Can be run multiple times if more than one shell in parallel is needed.
        - The first one to `exit` will stop the container.
    - _The script has been designed to make the container feel like a Vagrant virtual machine – this is not how one would typically use containers._


## License

This project is licensed under the [MIT License](LICENSE.md).

