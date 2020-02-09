# Project organisation

```
--+ root
  |
  +-- src ...................... (source directory)
  |
  +-- include .................. (header directory)
  |
  +-- test ..................... (test suites directory)
  |
  +-- assets ................... (ressources directory)
  |
  +-- doc ...................... (documentation directory)
```

# CI pipeline

Pipeline:
 - **conan**     : gestion de dépendances
 - **github**    : hebergement du projet
 - **travis CI** : intégration continue
 - **catch2**    : framework de test
 - **cppcheck**  : analyse statique
 - **gprof**     : analyse de performance