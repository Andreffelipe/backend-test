# CHANGELOG

## [2025-08-04] version 1.0.0

### added

- Create Author
    * POST /create/author
    * Creates a new author in the system.

- Create Post

    * POST /create/post/:author_id
    * Creates a new post linked to a specific author.

- Search Posts by Author

    * GET /find/post/:author_id
    * Returns all posts related to a specific author.

- Search Post by ID

    * GET /find/post/:author_id/:post_id
    * Returns a specific post based on the author and post ID.

- Search All Posts

    * GET /find/posts
    * Returns the list of all posts registered in the system.

- Finish Competition

    * GET /finish
    * Endpoint responsible for ending the ongoing competition.