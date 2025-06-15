---
title: How to install package
description: How to install package
github: https://github.com/zaimea/heroicons-docs/edit/main/
---

# Heroicons

[[TOC]]

## Instalation

```json
"repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/zaimealabs/heroicons"
        }
    ]
```

```bash
composer require zaimealabs/heroicons
```

#### Publish (Optional)

```bash
php artisan vendor:publish --tag="heroicons.config"
```
```bash
php artisan vendor:publish --tag="heroicons.views"
```
