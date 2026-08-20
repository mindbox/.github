![Mindbox GmbH is now zebra white GmbH](https://raw.githubusercontent.com/mindbox/.github/main/img/moved.png)

# Mindbox is now zebra white GmbH

Mindbox GmbH has become **zebra white GmbH** and is part of **zebra group**, together with
zebra black GmbH in Chemnitz. Our open source work has moved with us:

### → [github.com/zebra-group](https://github.com/zebra-group)

## If you use our code

Every repository that lived under `github.com/mindbox/…` has been transferred to
`github.com/zebra-group/…`. GitHub redirects the old paths, so existing clones and
`git fetch` / `git pull` keep working. Still, please update your remotes:

```bash
git remote set-url origin https://github.com/zebra-group/REPOSITORY.git
```

Using our Grav plugins through `user/.dependencies`? Point the `url:` entries at
`zebra-group` as well.

## Container images

Images under `ghcr.io/mindbox/…` stay pullable, but they are **no longer rebuilt** —
they will not receive further PHP or OS patches. New builds are published under
`ghcr.io/zebra-group/…`, for example:

```
ghcr.io/mindbox/php-fpm-apache   →   ghcr.io/zebra-group/php-fpm-apache
```

## npm packages

Unaffected. Packages such as `directus-extension-hash-generator` continue to be
published to the npm registry under the same names.

---

<sub>zebra white GmbH · Werner-Hartmann-Str. 5 · 01099 Dresden · <a href="https://zebra.de">zebra.de</a></sub>
