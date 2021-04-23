# node-blog
CRUD operations (sequelize integration soon to come)
session based authentication

API routes:

#####crud operations API routes
| API        | method        | description | auth required |
| ---------- |:-------------:| -----:|-------------------:|
|  /<username>  | GET | fetches the profile description of the username | false |
| <username>/posts   | GET      |   fetches all the posts by the username | false |
| /<username>/create | POST      |   creates a post | true |
| /<username>/<title> | GET     |   fetches the post with that particular title| false |
| /<username>/<title>/update | PUT      |   updates the post with the title name | true |
| /<username>/<title>/delete | DELETE      |   deletes a post with the title name | true |
