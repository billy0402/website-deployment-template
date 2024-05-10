# website-deployment-template

My website deployment template.

## Development environment

- [macOS 12.7.2](https://www.apple.com/tw/macos/monterey/)
- [Visual Studio Code 1.85.1](https://code.visualstudio.com/)
- [Docker 24.0.7](https://www.docker.com/)
- Frontend: [Next.js](https://nextjs.org/)
- Backend: [Django](https://www.djangoproject.com/) + [Django REST](https://www.django-rest-framework.org/)
- Database: [PostgreSQL](https://www.postgresql.org/)

## Getting Started

```shell
$ find . -name ".env.example" -type f -execdir cp -n {} .env \;

$ docker compose up -d
```

## Bugs and suggestions

If you have found a bug or have a request for additional functionality, please use the issue tracker on GitHub.

https://github.com/billy0402/website-deployment-template/issues

## License

Released under [MIT](/LICENSE) by [@billy0402](https://github.com/billy0402).
