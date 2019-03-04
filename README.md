# tiny-blog
Deployments for tiny-blog

## Parts

tiny-blog consists of many smaller parts. It has a shared data model between ui and backend, 
the [tiny-blog-model](https://github.com/strangedev/tiny-blog-model).
The [tiny-blog-api](https://github.com/strangedev/tiny-blog-api) is used to communicate with
[tiny-blog-backend](https://github.com/strangedev/tiny-blog-backend). Data is persisted using
a the [tiny-blog-db](https://github.com/strangedev/tiny-blog-db) connector and a MongoDB.
It comes with a official Vue user interface, the [tiny-blog-ui](https://github.com/strangedev/tiny-blog-ui).

![Image of dependencies](https://raw.githubusercontent.com/strangedev/tiny-blog/master/tiny-blog.png)
