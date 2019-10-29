# Example Heroku-16 app

Example Heroku app using the [Heroku-16](https://devcenter.heroku.com/articles/heroku-16-stack) stack.

## App

```bash
$ heroku info
=== protected-headland-75700
Auto Cert Mgmt: false
Dynos:
Git URL:        https://git.heroku.com/protected-headland-75700.git
Owner:          danielmweibel@gmail.com
Region:         us
Repo Size:      3 KB
Slug Size:      9 MB
Stack:          heroku-16
Web URL:        https://protected-headland-75700.herokuapp.com/
```

## Restore

Clone the repository:

```bash
git clone https://github.com/weibeld/example-heroku-16
cd example-heroku-16
```

Add `heroku` remote:

```bash
git remote add heroku https://git.heroku.com/protected-headland-75700.git
```

Heroku app is now restored:

```bash
heroku info
```

## See also

[Example Heroku-18 app](https://github.com/weibeld/example-heroku-18)
