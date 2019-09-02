## Parcel bug

### Reproduceable https://github.com/parcel-bundler/parcel/issues/3485

    >rustup --version
    rustup 1.18.3 (435397f48 2019-05-22)
    >cargo --version
    cargo 1.39.0-nightly (22f7dd049 2019-08-27)
    >parcel --version
    1.12.3

running

    >parcel index.html

I get a successfull build however on importing in javascript, I get an error printed to the console and the import fails.