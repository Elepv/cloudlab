### intro

Homepage is A modern, fully static, fast, secure fully proxied, highly customizable application dashboard with integrations for over 100 services and translations into multiple languages. Easily configured via YAML files or through docker label discovery.

### How to use it

Move the env.template to .env
Then fill it with your info.

```shell
mv env.template .env
vi .env
```

When it done, run:

```shell
docker compose up -d
```

test