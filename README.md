# Viperdock's PHP-FPM Base Image

---

## Docker 

### Configure Automated Builds

| Source Type | Source         | Docker Tag | Dockerfile Location | Build Context |
|-------------|----------------|------------|---------------------|---------------|
| Branch      | /^v([0-9.]+)$/ | {\1}-1.0   | Dockerfile-10       | /             |
| Branch      | master         | {\1}-2.0   | Dockerfile-20       | /             |

## Resources

- [PHP-FPM Docker Hub Repository](https://hub.docker.com/r/viperportside/php-fpm/)
- [Viperdock Git Repository](https://viper-lab.com/viper/docker).
