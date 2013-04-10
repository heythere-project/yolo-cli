#yolo-cli
Command Line Utilities for yolo.

##Install
 ```sh 
$ npm install yolo-cli -g
```
###Scaffolding Yolo Models
Generate Models easily with the generator.js . This would generate a model named "post" with attributes title, content and author and title would be required field.

```sh
$ yolo-cli model post title:required content author
```
###Scaffolding Yolo Controllers
Generate Controllers easily with the generator.js . This would generate a controller namend "posts" with methods index, edit and delete. Method "edit" will be acessabble via 'POST' and "delete" via 'DELETE'. Routes to those methods will be added automatically.

```sh
$ yolo-cli controller posts index edit:post delete:delete
```