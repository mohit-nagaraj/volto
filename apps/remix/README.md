# Plone on Remix

This is a proof of concept of a [Remix](https://remix.run) app, using the `@plone/client` and `@plone/components` libraries.
This is intended to serve as both a playground for the development of both packages and as a demo of Plone using Remix.

> [!WARNING]
> This package or app is experimental.
> The community offers no support whatsoever for it.
> Breaking changes may occur without notice.

## Development

To start, from the root of the monorepo:

```shell
pnpm install
pnpm --filter plone-remix run dev
```

Then start the Plone backend:

% TODO MAKEFILE
```shell
make backend-docker-start
```


## About this app

- [Remix Docs](https://remix.run/docs/en/main)
