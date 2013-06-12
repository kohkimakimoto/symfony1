# Symfony1 Composer Package

This is a Symfony1.4 framework custamized to install using Composer.

My purpose is to use Symfony version 1.4 like composer packages.

# composer.json

    {
        "repositories": [
            {
                "type": "package",
                "package": {
                    "name": "symfony1",
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
            "symfony1": "1.4"
        }

    }

# Notice

It's under the development process.



