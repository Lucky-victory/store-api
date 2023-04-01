# Store API
This API is built with Node.js, Express, MongoDB, and Mongoose to provide a simple store API that includes features such as pagination, search, sort, and numeric filters.

## Endpoints
### Get all static products
`GET /api/static/products`
This endpoint retrieves all products available in the store / database.

### Get all products
`Get /api/products`
This endpoint retrieves 10 products from the store / database by default, if limit is set then it returns the number set