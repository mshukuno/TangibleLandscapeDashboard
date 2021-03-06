# Tangible Landscape Dashboard

## Node.js and npm Installation

Skip this if you have Node.js and npm installed or already know how to install. 

The code below is tested on Ubuntu 14.04 (trusty).

1. Update apt-get:
    ```
    sudo apt-get update
    sudo apt-get dist-upgrade
    ```
2. Install NVM
  see https://github.com/creationix/nvm

3. Close terminal and re-open the terminal.

4. Verify NVM installation - if below command returns "nvm", then installation was successful:
    ```
    command -v nvm
    ```

5. Install latest Node.js:
    ```
    nvm install 4.4.3
    ```

6. Install npm:
    ```
    sudo apt-get install npm
    ```

7. Download TangibleLandscapeDashboard project.

8. Open command and change directory.
    ```
    cd "path to TangibleLandscapeDashboard"
    ```

9. Install Node modules:
    ```
    //Install "express.js", "body-parser.js", "underscore", "sequilize", and "sqlite3"
    npm install
    ```

10. Run Node.js server:
    ```
    node server.js
    ```

11. Open web browser and type URL:
    ```
    localhost:3000
    ```
    
## Snapshots
Top page
![top page](https://github.com/mshukuno/TangibleLandscapeDashboard/blob/master/public/img/snapshot/top_page.png)

Play page
![play page](https://github.com/mshukuno/TangibleLandscapeDashboard/blob/master/public/img/snapshot/play_page.png)

Data page
![data page](https://github.com/mshukuno/TangibleLandscapeDashboard/blob/master/public/img/snapshot/data_page.png)
