<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/6wj0hh6.jpg" alt="Project logo"></a>
</p>

<h3 align="center">Project Title</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> Few lines describing your project.
    <br> 
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using
## Mongo DB setup <a name = "getting_started"></a>

From browser create a account on MongoDB Atlas,
than while creating Cluster add the IP as Access from anywhere i.e 0.0.0.0/0

Create the user
* NOTE : while creating password for the user if using special char like ": / ? # [ ] @"
use the URL encoded format in the connection string 

For example, if your password in plain-text is p@ssw0rd'9'!, 

you need to encode your password as:

p%40ssw0rd%279%27%21

Than click on Database under Deployment from left side nav bar

click on connect --> select drivers --> run npm install mongdodb if u not having it in the package.json

![Alt text](/images/image.png)

Copy the connection string into .ENV file in your connection string remove double quotes
and replace the <password> with your password with url encoding of special char.



run
```
npm  i

npm  start
```
Also to have a view of browser in vscode you can install the MongdoDb extension in vscode

![Alt text](/images/image2.png)

![Alt text](/images/image3.png)

* Note in URL if you just mention
c1ggocx.mongodb.net/dbname

instead of this it will create automatically a db 
c1ggocx.mongodb.net/?retryWrites=true&w=majority


### Now Change the dir to Frontend


RUN commands to install packages and start the application
```
npm i
npm start
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo.

## 🔧 Running the tests <a name = "tests"></a>

Explain how to run the automated tests for this system.

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## 🎈 Usage <a name="usage"></a>

Add notes about how to use the system.

## 🚀 Deployment <a name = "deployment"></a>

Add additional notes about how to deploy this on a live system.

## ⛏️ Built Using <a name = "built_using"></a>

- [MongoDB](https://www.mongodb.com/) - Database
- [Express](https://expressjs.com/) - Server Framework
- [VueJs](https://vuejs.org/) - Web Framework
- [NodeJs](https://nodejs.org/en/) - Server Environment

## ✍️ Authors <a name = "authors"></a>

- [@kylelobo](https://github.com/kylelobo) - Idea & Initial work

See also the list of [contributors](https://github.com/kylelobo/The-Documentation-Compendium/contributors) who participated in this project.

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Hat tip to anyone whose code was used
- Inspiration
- References
