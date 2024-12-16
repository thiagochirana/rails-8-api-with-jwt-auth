# Rails 8 API with JWT Auth and JWT Blacklist

This is a API example made in Rails 8, with JWT authentication

## Routes avaliable

All routes starts with `/backend/v1`

_Obs: all stared with "\*" needs authentication
(Authorization Bearer token in header request)_

```
[GET] /hello* -> say hello to you
```

```
[POST] /auth -> returns a JWT access token and a JWT refresh token
```
