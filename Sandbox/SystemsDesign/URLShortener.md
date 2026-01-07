<!-- Use this one as example Example -->

# URL Shortener

## Requirements
- Shorten URL
- Redirect
- Analytics (optional)

## API
POST /shorten
GET /{id}

## Data Model
- id
- originalUrl
- createdAt

## Scale
- Cache
- DB sharding
- Load balancer

## Tradeoffs
- SQL vs NoSQL
- Consistency vs availability