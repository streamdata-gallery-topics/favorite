swagger: "2.0"
x-collection-name: Plivo
x-complete: 1
info:
  title: Plivo
  version: 1.0.0
host: api.plivo.com
basePath: v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /photos/:id/favorite:
    post:
      summary: Post Photos Favorite
      description: Adds the photo to users list of favorites.
      operationId: adds-the-photo-to-users-list-of-favorites
      x-api-path-slug: photosidfavorite-post
      parameters:
      - in: query
        name: id (required)
        description: ID of the photo the favorite is cast upon
      responses:
        200:
          description: OK
      tags:
      - Photos
      - :id
      - Favorite