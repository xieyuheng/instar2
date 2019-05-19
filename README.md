# A simple relay chat app

IRC-like architecture:
- relay only -- not central database for chat history
- chat history can be achieved by third part channel-log bots

Prepare:
- `npm install; npm run build`

Server:
- code at `/src` (nodejs, expressjs, typescript)
- `npm run server`

Web client:
- code at `/web` (react, jsx, parcel-bundler)
- `npm run web`

## Contributing

- We enforce C4 as collaboration protocol -- [The C4 RFC](https://rfc.zeromq.org/spec:42/C4)
- [Style Guide](STYLE-GUIDE.md) -- observe the style of existing code and respect it
- [Code of Conduct](CODE-OF-CONDUCT.md)

## License

- [GPLv3](LICENSE)
