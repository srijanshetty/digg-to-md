# What?

Extract subscription information from Digg Reader.

# Why?

Markdown is more human-friendly; and I needed it for my [site](http://srijanshetty.in/almanac.html#rss)

# How?

1. Install from source (Haven't published it to npm yet, and might not in the future).

```shell
git clone https://github.com/srijanshetty/digg-to-md.git
cd digg-to-md
npm install
npm link
```

2. Run on a *digg_reader_subscriptions.xml* file.

```shell
digg-to-md digg_reader_subscriptions.xml
```

# LICENSE

This project is licensed under the terms of the [MIT LICENSE](./LICENSE)
