# German Language Pack for [Flarum](https://flarum.org/) third-party extensions

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

- 0.2.2
- Released on January 28, 2021

### Supported Extensions

We currently support following third-party extensions:

- [Flarum Categories](https://github.com/askvortsov1/flarum-categories) (v2.0.0)
- [Filter by FriendsOfFlarum](https://github.com/FriendsOfFlarum/filter) (v0.3.2)
- [Formatting by FriendsOfFlarum](https://github.com/FriendsOfFlarum/formatting) (v0.3.1)
- [Linguist by FriendsOfFlarum](https://github.com/FriendsOfFlarum/linguist) (v0.5.0)
- [Links by FriendsOfFlarum](https://github.com/FriendsOfFlarum/links) (v0.5.3)
- [Night Mode by FriendsOfFlarum](https://github.com/FriendsOfFlarum/nightmode) (v0.7.1)
- [OAuth by FriendsOfFlarum](https://github.com/FriendsOfFlarum/oauth) (v0.2.0)
- [Pages by FriendsOfFlarum](https://github.com/FriendsOfFlarum/pages) (v0.6.0)
- [Polls by FriendsOfFlarum](https://github.com/FriendsOfFlarum/polls) (v0.3.2)
- [ReCAPTCHA by FriendsOfFlarum](https://github.com/FriendsOfFlarum/recaptcha) (v0.3.1)
- [User Bio by FriendsOfFlarum](https://github.com/FriendsOfFlarum/user-bio) (v0.4.2)
- [User directory by FriendsOfFlarum](https://github.com/FriendsOfFlarum/user-directory) (v0.5.0)
- [Username Request by FriendsOfFlarum](https://github.com/FriendsOfFlarum/username-request) (v0.4.1)
- [flarum-imgur-upload](https://github.com/matteocontrini/flarum-imgur-upload) (v3.5.0)
- [Flarum discussion views](https://github.com/MichaelBelgium/flarum-discussion-views) (v5.0.0)
- [Flarum profile views](https://github.com/MichaelBelgium/flarum-profile-views/) (v4.0.0)
- [Minecraft Avatars](https://github.com/Nearata/flarum-ext-minecraft-avatars) (v1.2.0)
- [Flarum Blog](https://github.com/v17development/flarum-blog) (v0.2.1)

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
