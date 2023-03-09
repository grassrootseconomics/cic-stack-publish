# cic-deploy
 
## Usage

1. Create a `cic` overlay network with `docker network create cic`
2. Bring up the `services` containers with `docker-compose up -d`.
3. Bring up the `cic-stack` containers.
4. Optionally, bring up the `caddy` container if you want to expose the API to the internet.
5. Optionally, bring up the `observability` containers if you have an [Uptrace](https://uptrace.dev) deployment/account.


## License

[AGPL-3.0](LICENSE).