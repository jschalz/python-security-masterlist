# python-security-masterlist
A list of infosec resources, tools/libraries, docs, etc. for the Python programming language.

This list is ever-changing, and the author appreciates PR additions/updates to it!

## Contents
- [Tools](#tools)
  - [Best Practices](#best-practices)
  - [Scanners/Linters](#scannerslinters)
- [Libraries](#libraries)
  - [Best Practices](#best-practices)
  - [Cryptography](#cryptography)
  - [Deserialization](#deserialization)
- [Docs](#docs)
- [Resources](#resources)
- [Vulnerabilities](#vulnerabilities)
- [Miscellaneous](#miscellaneous)

## Tools

### Best Practices
- Use `pipenv` over `virtualenv`
  - `pipenv`: https://pipenv.pypa.io/en/latest/
  - Why? https://towardsdatascience.com/python-environment-101-1d68bda3094d

### Scanners/Linters
- Bandit
  - "A security linter from PyCQA"
  - Docs: https://bandit.readthedocs.io/en/latest/
  - https://pypi.org/project/bandit/

## Libraries

### Best Practices
TODO

### Cryptography
- `cryptography`
  - `cryptography` https://pypi.org/project/cryptography/
  - Preferred over `cryptodomex`
  - Difference between `cryptodome` and `cryptodomex`: https://stackoverflow.com/questions/48155294/what-is-pycryptodomex-and-how-does-it-differ-from-pycryptodome

### Deserialization
TODO

## Docs

- Python Security: https://python-security.readthedocs.io/security.html
  - Specific information on vulns and patches by branch: https://devguide.python.org/#status-of-python-branches

## Resources
- Common appsec pitfalls and fixes: https://deepsource.io/blog/python-security-pitfalls/
- OWASP Python security project: https://github.com/ebranca/owasp-pysec
  - "Python Security is a free, open source, OWASP project that aims at creating a hardened version of python that makes it easier for security professionals and developers to write applications more resilient to attacks and manipulations."

## Vulnerabilities
- Python Security: https://python-security.readthedocs.io/vulnerabilities.html

## Disclosure Info
> There is not any hard and fast rule to determine if a bug is worth reporting. The general rule is any attack worth reporting via the security address must allow an attacker to affect the confidentiality, integrity and availability of the Python application or its system for which the attacker does not already have the capability.

Guidance on how to disclose vulns is provided here: https://www.python.org/dev/security/
- This link also provides examples of previous disclosure decisions.

**PyPI-specific** disclosure info: https://pypi.org/security/

## Miscellaneous
TODO
