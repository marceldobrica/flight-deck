# Dockstack

TEN7's dockstack is a library of containers for local Drupal development.
Instead of a single "stack to rule them all", dockstack provides a mix-and-match
approach to suit your development needs.

Many of the containers are based on Wodby's excellent [Docker4Drupal project](https://github.com/wodby/docker4drupal/).

## Library

| Container | Service name | Tags | Public Port | Supports Drupal |
| --------- | ------------ | ---- | ----------- | --------------- |
| [ten7/dockstack-php-apache](https://hub.docker.com/r/ten7/dockstack-php-apache/) | web | 5.6 | 80 | 6, 7 |
| [ten7/dockstack-php-apache](https://hub.docker.com/r/ten7/dockstack-php-apache/) | web | 7.0, latest | 80 | 8 |
| [ten7/dockstack-mysql](https://hub.docker.com/r/ten7/dockstack-mysql/) | db | latest | 3306 | all |
| [phpmyadmin/phpmyadmin](https://hub.docker.com/r/phpmyadmin/phpmyadmin/) | pma | latest | 8001 | all |
| [mailhog/mailhog](https://hub.docker.com/r/mailhog/mailhog/) | mailhog | latest | 8002 | all |
| [_/memcached](https://hub.docker.com/_/memcached/) | memcached | 1.4-alpine |   | all |
| [ten7/dockstack-varnish](https://hub.docker.com/r/ten7/dockstack-varnish/) | varnish | 4.0, latest | 8004, 8005 | all |
| [ten7/dockstack-solr](https://hub.docker.com/r/ten7/dockstack-solr/) | solr | 5.5, latest | 8003 | 7, 8 |

## Support

You can always [post an issue](https://github.com/ten7/dockstack/issues/new) on our Github page.

## License

See [LICENSE](https://raw.githubusercontent.com/ten7/dockstack/master/LICENSE).