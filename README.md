# Flash RabbitMQ Message Testing (rpc)

This was written for situations where testing a story involves needing to manually publish a message.

## To use

- Clone the project
- `bundle install`
- Edit values in `config.yml` as needed. These include the RabbitMQ url and exchange, the routing key for the message, and the message payload.
- run `bin/test`

BunnyBurrow will log to stdout so the response can be verified.