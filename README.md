# backend_realproject

## How-to

### Option 1. Run server on host

- Just click **start button** on *vscode*

- or:

  - build using Gradle

    ```shell
    $ ./gradlew build
    ```

    - Takes about 1.5 minutes (tested on M1 Macbook Pro)

  - Run jar file

    ```
    $ java -jar build/libs/realproject-0.0.1-SNAPSHOT.jar
    ```

### Option 2. Run on Docker

This option is currently not available.

- Build the container

  ```shell
  $ docker compose build
  ```

- Run the container

  ```shell
  $ docker compose up
  ```
