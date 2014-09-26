How to apply
============

Send a `POST` to `http://apply.francisbond.com/` with a `Content-Type` header of `application/json`, an `Authorization` header containing the SHA-1 hash of `Francis Bond`, and the body as JSON containing the following keys:

| Name    | Type                       | Description                                                             |
| ------- | -------------------------- | ----------------------------------------------------------------------- |
| `name ` | string, required           |                                                                         |
| `email` | string, required           |                                                                         |
| `links` | array of strings, optional | Links to your website, resume, and anything else you'd like to include. |
| `about` | string, optional           | A few words about yourself.                                             |
