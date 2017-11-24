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

* yaml list, all list member with same indentation level starting with (a dash and a space) `'- '`, eg:

```
fruit:
    - apple
    - orange
    - strawberry
    - grape
```

* yaml dictionary, represent simple `key: value`, (a colon must follow by a space) `': '`, eg:
```
# an employee record
jack:
    name: jack huge
    job: se
    skill: running
```

* more compleate example, mix list and dictionary.
```
# epmloyee record
- jack:
    name: jack huge
    job: dev
    skill:
        - swim
        - cook
        - ski
- make:
    name: mike D
    job: dj
    skill:
        - sing
        - speak
        - laugh
```

* abbreviate format for map and list, eg
```
martin: {name: uncle martin, job: driver, skill: excellent}
fruit: ['apple', 'orange', 'grape']
```

