# IMSserverV3

Implementation of local IMS server to be used with Enterprise Connector

![image](https://user-images.githubusercontent.com/22134155/115521993-fc2ea000-a28b-11eb-864d-72c551a144af.png)

There are 3 endpoints implemented

* /ping
* /protocol
* /v3/multipartMessage

## Before starting the server

first of all you need to clone the repository using the GIT program
if you don't have git visit the following [link](https://git-scm.com/downloads)

clone the repository with...

```
git clone https://github.com/gspagoni/IMSserverV3.git
```

after that you can have this

![image](https://user-images.githubusercontent.com/22134155/115525009-00a88800-a28f-11eb-8a98-46b100027ea8.png)


open a CMD command and navigate to the folder

run the command

```
npm install
```
![image](https://user-images.githubusercontent.com/22134155/115535904-7c0f3700-a299-11eb-96a0-7e0c7b7d1691.png)


## Start the Server

From the same opened command window

run the command

```
node index.js
```
the server starts

![image](https://user-images.githubusercontent.com/22134155/115536412-0e173f80-a29a-11eb-9624-fb69ddc1b662.png)

open a browser and type http://localhost:3000

![image](https://user-images.githubusercontent.com/22134155/115536695-5fbfca00-a29a-11eb-9626-d26b223d4466.png)

the server is ready to receive messages from ION

<hr>

for any details write to [Giampaolo](mailto:giampaolo.spagoni@infor.com)
