# Puppeteer Netflix Categories

> Runs a puppeteer script to scrap and download all categories in a json file.


## Install

```
$ git clone 
```


## Usage

Download or clone this repo.
Enter your Netflix email and password in the config file.
You can also choose to enable headless mode in Chrome.
You can also set the error limit, if there is no category, how many more will it try.

This will create file called results.json

```bash
$ node index.js
```

results.json example
```bash
{
    "title": "African-American Crime Documentaries",
    "id": 1
}

```





## License

MIT © [Robert James Gabriel](https://robertgabriel.ninja)