<div align="center">
    <img src="https://iili.io/XSA0gt.md.png" width='290px' alt="Angel code style"/>
</div>

<br>
<br>

<div align="center">
<h1>AngelDB</h1>

<p align="center">
  <img src="https://dcbadge.vercel.app/api/shield/509271102653202433" alt="img"/> 
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="img"/>
  <img src='https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white' alt="img"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-ff0000" alt="img"/>
  <img src="https://img.shields.io/badge/code_style-Angel-ff0000.svg" alt="angel code style"/>
</p><hr />

</div>

<br>

AngelDB is a fast json database that allows you to insert data, delete and edit

<br>

### **Getting started**

```bash
npm i angeldb
```

After the installation you can create a json file and start immediately.

<br>

### **Usage**



import AngelDB to your project

```javascript
const angel = require('angeldb');
```

add your json file

```javascript
const angel = require('angeldb');

const angels = table("./angels.json");
```

<br>

add an object to the json file

```javascript
await angels.set({ id: 0, username: "StarBoy", email: "StarBoy@test.com" });
```

<br>

find your objects in the json file

```javascript
const data = await angels.find(x => x.username === "StarBoy");
```

<br>

update objects in the json file

```javascript
await angels.update(x => x.username === "StarBoy", { city: "london" });
```
<br>

remove objects in the json file

```javascript
await angels.remove(x => x.city === "london");
```

<br>

Delete all objects in the json file

```javascript
await angels.xo();
```

<br>

<p>
love you all 😘

..Angel Code Style..
</p>
