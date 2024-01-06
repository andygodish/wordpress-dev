# Wordpress Development Environment

- [Repository](https://github.com/andygodish/wordpress-dev)
- [Documentation](https://github.com/andygodish/wikijs-storage/blob/main/wordpress/local-development.md)

---

docker exec -it wordpress-dev2-web-1 /bin/bash

find . -maxdepth 1 -not -name 'wordpress' -not -name '.' -exec mv {} wordpress/ \;
find . -maxdepth 1 -not -name 'wordpress' -not -name 'wp-content' -not -name '.' -exec mv {} wordpress/ \;
