# technotrove

Endpoints

GET

http://localhost:8080/api <br>
http://localhost:8080/api/category/{Id} <br>
http://localhost:8080/api/product/{productId} <br>
http://localhost:8080/api/productVariant/find/{prodVarId} <br>

POST

http://localhost:8080/api/productVariant/add <br>

```
{
  "id": 122,
  "sku": "kkk111",
    "name": "kkk111",
    "price": 6783,
    "image_url1": "https://m.media-amazon.com/images/I/51JbsHSktkL._AC_UF1000,1000_QL80_.jpg",
    "image_url2": "https://m.media-amazon.com/images/I/51JbsHSktkL._AC_UF1000,1000_QL80_.jpg",
    "image_url3": null,
    "quantity": 35,
    "productId": 5
}
```
