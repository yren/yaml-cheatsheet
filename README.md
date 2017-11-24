# yaml cheatsheet

* from http://docs.ansible.com/ansible/latest/YAMLSyntax.html

## yaml basics
* a small quirk to yaml, a yaml file start with `---` , end with `...`, eg:
```
---
# an example yaml file
fruit:
    - apple
    - orange
    - peral
    - mango
...
```

* yaml comments use `#`