# Parcel HMR Example

This is a small example about how to get Hot Module Replacement (HMR) working with Parcel while we're serving the index with another server (`python3 http.server`).

The purpose is to be able to use Parcel while we're developing with a web framework like Django or Flask, avoiding to lose the HMR feature.

## Install & Run

```bash
npm install

# run the python webserver in a terminal
npm run web

# watch the changes in the `index.html` and `index.js` files
npm run watch
```

After that, you'll be able to open http://localhost:8000/ in a browser, and once you add some changes in the `index.html` or `index.js`, the hot reloading should work.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
