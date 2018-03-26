i18n
====

Help translating the Final.Vote website!

The locale files are in YAML format.
If you don't know how to edit these files,
you can read [this guide](http://guides.rubyonrails.org/i18n.html).

---

How to Contribute:

0. Fork this repository.

1. Copy the English locale file to new locale file in your language.

```
cp locales/main.en.yml locales/main.jp.yml
```

2. Put the locale code in the first line, and start translating!

```yaml
jp:
  hello: 'こんにちは'
```

3. Create a pull request.
