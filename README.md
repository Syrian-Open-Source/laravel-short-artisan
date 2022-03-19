# Laravel Short Artisan

This package is meant to be installed globally, and it's a set of aliases for php artisan commands. It doesn't require anything to be installed just add it with composer as a global dependency, and you're good to go.
```shell
composer global require syrian-open-source/laravel-short-artisan
```

#Usage

Once this package is installed go to any Laravel project folder and use it:
```shell
# basic usage
art make:model Post -crm # short for php artisan make:model Post -crm
# you can make it shorter like this
model Post -crm
```

## List of available aliases
| Alias          | Command                         |
|----------------|---------------------------------|
| `art`          | `php artisan`                   |
| `clear`        | `php artisan optimize:clear`    |
| `controller`   | `php artisan make:controller`   |
| `event`        | `php artisan make:event`        |
| `factory`      | `php artisan make:factory`      |
| `fresh`        | `php artisan migrate:fresh`     |
| `link`         | `php artisan storage:link`      |
| `listen`       | `php artisan queue:listen`      |
| `listener`     | `php artisan make:listener`     |
| `factory`      | `php artisan make:factory`      |
| `make`         | `php artisan make:`             |
| `migrate`      | `php artisan migrate`           |
| `migration`    | `php artisan make:migration`    |
| `model`        | `php artisan make:model`        |
| `mtest`        | `php artisan make:test`         |
| `notification` | `php artisan make:notification` |
| `pest`         | `php artisan make:test --pest`  |
| `policy`       | `php artisan make:policy`       |
| `publish`      | `php artisan vendor:publish`    |
| `request`      | `php artisan make:request`      |
| `resource`     | `php artisan make:resource`     |
| `seed`         | `php artisan seed`              |
| `seeder`       | `php artisan make:seeder`       |
| `serve`        | `php artisan serve`             |
| `test`         | `php artisan test`              |
| `tinker`       | `php artisan make:tinker`       |

Changelog
---------
Please see the [CHANGELOG](https://github.com/syrian-open-source/laravel-short-artisan/blob/master/CHANGELOG.md) for
more information about what has changed or updated or added recently.

Security
--------
If you discover any security related issues, please email them first to roduan98@gmail.com, if we do not fix it
within a short period of time please open a new issue describing your problem.

Credits
-------
[Roduan Kareem Aldeen](https://www.linkedin.com/in/roduankd)

About Syrian Open Source
-------
The Syrian Open Source platform is the first platform on GitHub dedicated to bringing Syrian developers from different
cultures and experiences together, to work on projects in different languages, tasks, and versions, and works to attract
Syrian developers to contribute more under one platform to open source software, work on it, and issue it with high
quality and advanced engineering features, which It stimulates the dissemination of the open-source concept in the
Syrian software community, and also contributes to raising the efficiency of developers by working on distributed
systems and teams.
