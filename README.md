# Symfony1 Composer Package

This is a Symfony1.4 framework custamized to install using Composer.

My purpose is to use Symfony version 1.4 as composer packages.

## composer.json

The following code is a `composer.json` file to install symfony1.4 to your system.

```json
{
    "repositories": [
        {
            "type": "package",
            "package": {
                "name": "symfony/symfony1",
                "version": "1.4",
                "source": {
                  "url": "https://github.com/kohkimakimoto/symfony1.git",
                  "type": "git",
                  "reference": "1.4-composer-package"
                }
            }
        }
    ],
    "require": {
        "symfony/symfony1": "1.4"
    }
}
```


## Notice

It's under the development process.



