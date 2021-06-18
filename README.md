# German Language Pack for [Flarum](https://flarum.org/) third-party extensions


## 🗄️ Repository has been archived
All contents have been merged into [flarum-lang/german](https://github.com/flarum-lang/german).

---

Extension to localize third party extensions into German. For support, please use the discussion thread on the [Flarum support forum](https://discuss.flarum.org/d/2648-german-language-pack), or use the issue tracker here on GitHub.

You can find the German language pack for **Flarum and it's bundled extensions** in [this repository](https://github.com/Kakifrucht/flarum-de).

- [Information](#information)
  - [Version](#version)
  - [Supported Extensions](#compatibility)
  - [License](#license)
- [Documentation](#documentation)
  - [How to install](#how-to-install)
  - [How to update](#how-to-update)

## Information

### Version

- 1.0.0
- Released on May 29, 2021

### Supported Extensions

We currently support following third-party extensions:



To add support for an extension or update an existing translation, please open a pull request.

### License

Released under the MIT License. Please see the [LICENSE](LICENSE) file.

## Documentation

### How to install

Use Composer in the root directory of your forum:

```text
composer require kakifrucht/flarum-de-extended
```

See also on [Packagist](https://packagist.org/packages/kakifrucht/flarum-de-extended).

### How to update

Execute these commands in the root directory of your forum:

```text
composer update kakifrucht/flarum-de-extended
php flarum cache:clear
```
