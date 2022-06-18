# JSON Parse Training

1. After cloning the repository run `php -S localhost:3333`
2. Go to `http://localhost:3333/index.html`
3. The basic page has jQuery 3.6.0, Bootstrap 5, plus Axios to consume and parse the endPoint data.
4. Under the scripts folder there's a `main.js` where all the logic must be placed.
5. I have created an endpoint that retrieves a list of products. `https://my-json-server.typicode.com/rpswallace/test/products`
6. Please create a new branch before starting a task, that way it can review it in an isolated way before continuing with the next one.

For all tasks use the following endPoint `https://my-json-server.typicode.com/rpswallace/test/products` and wireframe `https://miro.com/app/board/uXjVOsZsYn0=/`. The main goal is not the styling, is the functionality, the way the endPoint is consumed and data parsed to reflect it in the browser. For styles, Bootstrap is available, please use it as needed, jQuery is also available.

**Task #1:**
- Determine how many products are coming, use it in the title "My Product List ([total products])"

**Task #2:** Build a product grid.
- Each product should be clickable for task #3.
- Do not include those where quantity is equals or less than zero. The title should also be updated (My Product List)
- Add a red border and a copy to those that are on sale.

**Task #3:**
- By clicking any product, should leads the user to the proper product page details. Please use `http://localhost:3333/product-details.html`, you can pass the params you want. The endPoint to retrieve a specific product data is the following: `https://my-json-server.typicode.com/rpswallace/test/products/[id]`
