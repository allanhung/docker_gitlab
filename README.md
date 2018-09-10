# docker compose for gitlab

## How to use

Run gitlab with:

``` shell
git clone https://github.com/allanhung/docker_gitlab.git
cd docker_gitlab
docker-compose up -d gitlab
```

1. Get gitlab-ci token from admin/runners
2. modify token in config.toml.
3. copy config.toml to /opt/gitlab-runner/config/config.toml
4. Run gitlab runner with docker-compose up -d
