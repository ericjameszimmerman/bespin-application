# bespin-application
A tutorial project for using Git subtrees

Subtree Installation
--------------------
```
$ cd /path/to/bespin-application
$ git subtree add --prefix components/kamino-platform git@github.com:ericjameszimmerman/component-kamino-platform.git master --squash

$ git subtree add --prefix components/eadu-test-framework git@github.com:ericjameszimmerman/component-eadu-test-framework.git master --squash

```