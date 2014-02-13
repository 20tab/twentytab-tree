twentytab-tree
==============

A django app that allows to create a tree menu and breadcrumb. It provides to create also urls, views and template.


## Installation

Use the following command: <b><i>pip install twentytab-tree</i></b>

## Configuration

- settings.py

```py
INSTALLED_APPS = {
    ...,
    'mptt',
    'twentytab',
    'tree',
    ...
}
```

- urls.py

```py
urlpatterns = patterns('',
    ... ,
    (r'', include('tree.urls')),
    ...
)

```