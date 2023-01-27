# Postman + Newman + Github actions 

## Task steps 
1. Clone and checkout the github project:

        git clone https://github.com/Karyna0505/PostMan.git

2. Run (install node.js dependencies)

        npm i 
3. Run (to run testing server locally )

        npm run tern-on-api

### Overview of local server testing
Routes `/products`, `/orders` and `/users`. Below is a table of supported operations with `products` as example resource. The same operations are also supports for `orders/` and `users/`.

| VERB     |Route          | Input      | Output             |
|----------|---------------|------------|--------------------|
| GET      | /products     | *None*     | **Array**          |
| GET      | /products/:id |  **e.g 3** | **Object**         |
| POST     | /products     | **object** | **Created object** |
| PUT      | /products     | **object** | **Updated object** |
| DELETE   | /products/:id | **e.g 3**  | **Deleted object** |


4. Upload `store.postman_collection.json` and `petstore.collection.json` in Postman app. 
5. Make some request tests in Postman, could be status code/JSON check and so on. 



###  GH actions 
6. Open Actions of repository https://github.com/Karyna0505/PostMan.git .
7. Check github actions for result https://karyna0505.github.io/PostMan/.




