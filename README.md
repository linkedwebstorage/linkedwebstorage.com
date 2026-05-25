# linkedwebstorage.com

An unofficial, community-maintained information page about the W3C
[Linked Web Storage](https://www.w3.org/groups/wg/lws/) (LWS) initiative:
what it is, how it relates to Solid, the official documents, and the
implementations being built on it.

> **Note:** This is not an official W3C site. For authoritative information,
> see the [LWS Working Group](https://www.w3.org/groups/wg/lws/) and the
> [Working Group Charter](https://www.w3.org/2024/09/linked-web-storage-wg-charter.html).

## What's here

A single static page, [`index.html`](index.html). No build step and no
framework: styling is [Tailwind](https://tailwindcss.com/) via CDN, and the
social-card image is [`og.png`](og.png). The page is plain HTML so anyone
can read the source, copy a section, or open a pull request without tooling.

## Run locally

Open `index.html` directly in a browser, or serve the folder:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

The site is served by GitHub Pages from the `gh-pages` branch (the default
branch of this repository) at the domain in [`CNAME`](CNAME). Merging to
`gh-pages` publishes automatically; there is nothing to build.

## Contributing

Pull requests are welcome, especially:

- **Implementations.** Add a server, client, library, or auth implementation
  to the Implementations section. Include the project link, its role
  (server / client / library), and the LWS surface it implements.
- **Accuracy.** Fix or update links, document references, and descriptions as
  the specifications and Working Group progress.

Keep additions accurate and concise; the page aims to be a clear reference,
not a promotional surface. Open PRs against the `gh-pages` branch.

## Official W3C resources

- [LWS Working Group](https://www.w3.org/groups/wg/lws/)
- [LWS Protocol 1.0 (Editor's Draft)](https://w3c.github.io/lws-protocol/)
- [Controlled Identifiers (CID) 1.0](https://www.w3.org/TR/cid-1.0/)
- [LWS Use Cases](https://www.w3.org/TR/lws-ucs/)

## License

[MIT](LICENSE)
