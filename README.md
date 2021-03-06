# IMSserverV3

Implementation of local IMS server to be used with Enterprise Connector

![image](https://user-images.githubusercontent.com/22134155/115521993-fc2ea000-a28b-11eb-864d-72c551a144af.png)

There are 3 endpoints implemented

* /ping
* /protocol
* /v3/multipartMessage

## Preparations before starting the server

For using GitHub an account is needed, create an account via the [link](https://github.com/join)
Then proceed and clone the repository using the GIT program
If you don't have git visit the following [link](https://git-scm.com/downloads)

Additionally you need to have Node.js installed. If you don't have Node.js visit [Nodejs](https://nodejs.org/en/).

Clone the repository with below command in a local directory:

```
git clone https://github.com/gspagoni/IMSserverV3.git
```

After cloning you will have your directory filled like below:

![image](https://user-images.githubusercontent.com/22134155/115525009-00a88800-a28f-11eb-8a98-46b100027ea8.png)


Open a CMD command and navigate to the folder

Run the command

```
npm install
```
![image](https://user-images.githubusercontent.com/22134155/115535904-7c0f3700-a299-11eb-96a0-7e0c7b7d1691.png)


## Start the Server

From the same opened command window

Run the command

```
node index.js
```
Then the server starts

![image](https://user-images.githubusercontent.com/22134155/115536412-0e173f80-a29a-11eb-9624-fb69ddc1b662.png)

Open a browser and type http://localhost:3000

![image](https://user-images.githubusercontent.com/22134155/115536695-5fbfca00-a29a-11eb-9626-d26b223d4466.png)

The server is ready to receive messages from ION

## Create standalone web server

To create a standalone server (.EXE) go to a new command window in the same directory.

Run the command and enter 'y' to proceed.

```
npx pkg . --target node10-win-x64
```

A new nodejs-imsserver.exe file is generated that is the standalone server

![image](https://user-images.githubusercontent.com/22134155/115559012-96560e80-a2b3-11eb-9f57-bbe4dd245c04.png)

Double click and the server starts on the default PORT **3000**

![image](https://user-images.githubusercontent.com/22134155/115538749-7f57f200-a29c-11eb-8bde-9988e5aa6ebe.png)


If you want to run the server on different port you have to pass a parameter [-p|PORT]=portnumber

```
nodejs-imsserver.exe -p=4000
or
nodejs-imsserver.exe PORT=4000
```

![image](https://user-images.githubusercontent.com/22134155/115559479-09f81b80-a2b4-11eb-8e0e-f144a1fe7435.png)

In this case you can have more than one instance running on different Ports

<hr>

for any details write to [Giampaolo](mailto:giampaolo.spagoni@infor.com)

