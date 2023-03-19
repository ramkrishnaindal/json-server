GET    /posts
GET    /posts/1
POST   /posts
PUT    /posts/1
PATCH  /posts/1
DELETE /posts/1


GET    /profile
POST   /profile
PUT    /profile
PATCH  /profile

GET /posts?title=json-server&author=typicode
GET /posts?id=1&id=2
GET /comments?author.name=typicode

GET /posts?_page=7
GET /posts?_page=7&_limit=20

GET /posts?_sort=views&_order=asc
GET /posts/1/comments?_sort=votes&_order=asc
GET /posts?_sort=user,views&_order=desc,asc

GET /posts?_start=20&_end=30
GET /posts/1/comments?_start=20&_end=30
GET /posts/1/comments?_start=20&_limit=10

GET /posts?views_gte=10&views_lte=20

GET /posts?id_ne=1

GET /posts?title_like=server

GET /posts?q=internet

GET /posts?_embed=comments
GET /posts/1?_embed=comments

GET /comments?_expand=post
GET /comments/1?_expand=post

GET  /posts/1/comments
POST /posts/1/comments