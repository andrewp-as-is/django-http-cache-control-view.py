<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/django-http-cache-control-view.svg?maxAge=3600)](https://pypi.org/project/django-http-cache-control-view/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/django-http-cache-control-view.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/django-http-cache-control-view.py/actions)

### Installation
```bash
$ [sudo] pip install django-http-cache-control-view
```

##### `views.py`
```python
from django_http_cache_control_view.views import HttpCacheControlMixin

class MyView(HttpCacheControlMixin,...):
    http_cache_control_max_age = 60
```

```python
class MyView(HttpCacheControlMixin,...):
    def get_http_cache_control_max_age(self):
        return 60
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
