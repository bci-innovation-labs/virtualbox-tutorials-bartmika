# Lesson 3: Install React on CentOS 7

https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-a-centos-7-server

1. Install our dependicies.

    ```
    curl -sL https://rpm.nodesource.com/setup_10.x | sudo bash -
    sudo yum install nodejs
    node --version
    sudo npm install -g npm@next
    npm --version
    sudo npm install -g create-react-app
    ```


2. Confirm ``react`` version.

    ```
    create-react-app --version
    ```


3. Go to your developers directory

    ```
    mkdir ~/javascript
    cd ~/javascript
    ```

4. Now we will create our first ``react`` app using the installer.

    ```
    create-react-app helloworld
    ```

5. Open.

    ```
    cd ~/javascript/helloworld
    npm start
    ```
