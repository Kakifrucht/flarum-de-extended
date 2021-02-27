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

- 0.3.0
- Released on February 27, 2021

### Supported Extensions

We currently support following third-party extensions:

- [Money](https://github.com/AntoineFr/flarum-ext-money) v0.11.0
- [Flarum Categories](https://github.com/askvortsov1/flarum-categories) v2.0.0
- [Flarum Progressive Web App](https://github.com/askvortsov1/flarum-pwa) v2.0.2
- [Trust Levels](https://github.com/askvortsov1/flarum-trust-levels) v0.1.4
- [Mailing](https://github.com/clarkwinkelmann/flarum-ext-mailing) v0.4.0
- [Best Answer by FriendsOfFlarum](https://github.com/FriendsOfFlarum/best-answer) v0.3.5
- [Byōbu by FriendsOfFlarum](https://github.com/FriendsOfFlarum/byobu) v0.6.1
- [Discussion Language by FriendsOfFlarum](https://github.com/FriendsOfFlarum/discussion-language) v0.3.2
- [Drafts by FriendsOfFlarum](https://github.com/FriendsOfFlarum/drafts) v0.3.2
- [Filter by FriendsOfFlarum](https://github.com/FriendsOfFlarum/filter) v0.3.2
- [Formatting by FriendsOfFlarum](https://github.com/FriendsOfFlarum/formatting) v0.3.1
- [Gamification by FriendsOfFlarum](https://github.com/FriendsOfFlarum/gamification) v0.4.2
- [Impersonate by FriendsOfFlarum](https://github.com/FriendsOfFlarum/impersonate) v0.7.0
- [Linguist by FriendsOfFlarum](https://github.com/FriendsOfFlarum/linguist) v0.5.0
- [Links by FriendsOfFlarum](https://github.com/FriendsOfFlarum/links) v0.5.3
- [Masquerade by FriendsOfFlarum](https://github.com/FriendsOfFlarum/masquerade) v0.3.7
- [Merge Discussions by FriendsOfFlarum](https://github.com/FriendsOfFlarum/merge-discussions) v0.5.1
- [Moderator Notes by FriendsOfFlarum](https://github.com/FriendsOfFlarum/moderator-notes) v0.4.1
- [Night Mode by FriendsOfFlarum](https://github.com/FriendsOfFlarum/nightmode) v0.7.1
- [OAuth by FriendsOfFlarum](https://github.com/FriendsOfFlarum/oauth) v0.2.0
- [Pages by FriendsOfFlarum](https://github.com/FriendsOfFlarum/pages) v0.6.0
- [Polls by FriendsOfFlarum](https://github.com/FriendsOfFlarum/polls) v0.3.2
- [Prevent Necrobumping by FriendsOfFlarum](https://github.com/FriendsOfFlarum/prevent-necrobumping) v0.4.0
- [Reactions by FriendsOfFlarum](https://github.com/FriendsOfFlarum/reactions) v0.5.0
- [ReCAPTCHA by FriendsOfFlarum](https://github.com/FriendsOfFlarum/recaptcha) v0.3.1
- [Secure HTTPS by FriendsOfFlarum](https://github.com/FriendsOfFlarum/secure-https) v0.3.0
- [Sitemap by FriendsOfFlarum](https://github.com/FriendsOfFlarum/sitemap) v0.6.0
- [Social Profile by FriendsOfFlarum](https://github.com/FriendsOfFlarum/socialprofile) v0.2.3
- [Split by FriendsOfFlarum](https://github.com/FriendsOfFlarum/split) v0.6.0
- [Upload by FriendsOfFlarum](https://github.com/FriendsOfFlarum/upload) v0.12.10
- [User Bio by FriendsOfFlarum](https://github.com/FriendsOfFlarum/user-bio) v0.4.2
- [User directory by FriendsOfFlarum](https://github.com/FriendsOfFlarum/user-directory) v0.5.0
- [Username Request by FriendsOfFlarum](https://github.com/FriendsOfFlarum/username-request) v0.4.2
- [Webhooks by FriendsOfFlarum](https://github.com/FriendsOfFlarum/webhooks) v0.5.0
- [HTML Head Items](https://github.com/imorland/html-head) v0.1.1
- [flarum-imgur-upload](https://github.com/matteocontrini/flarum-imgur-upload) v3.6.0
- [Flarum SSO](https://github.com/maicol07/flarum-ext-sso) v1.8.1
- [Flarum discussion views](https://github.com/MichaelBelgium/flarum-discussion-views) v5.0.0
- [Flarum profile views](https://github.com/MichaelBelgium/flarum-profile-views/) v4.0.0
- [Minecraft Avatars](https://github.com/Nearata/flarum-ext-minecraft-avatars) v1.2.0
- [Flarum Blog](https://github.com/v17development/flarum-blog) v0.2.1

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
