# Lumen Sample Tutorial

Ref: [https://www.sitepoint.com/building-a-hacker-news-reader-with-lumen/](https://www.sitepoint.com/building-a-hacker-news-reader-with-lumen/)

## Development steps

1. Craft the application using lumen command line application.

```shell
lumen new hnreader
```

2. Do migration using the following command.

```shell
php artisan migrate
```

3. Get the news items feed and dump in the local database.

```shell
php artisan update:news_items
```