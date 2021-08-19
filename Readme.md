# The `devonline-archetype-jar` Project

## Generate a new project using this archetype:

### For Windows:

Using default settings:

```bash
mvn archetype:generate ^
    -DarchetypeCatalog=local ^
    -DarchetypeGroupId=academy.devonline.maven.archetypes ^
    -DarchetypeArtifactId=devonline-archetype-jar ^
    -DinteractiveMode=false ^
    -DartifactId=simple
```

Using custom settings:

```bash
mvn archetype:generate ^
    -DarchetypeCatalog=local ^
    -DarchetypeGroupId=academy.devonline.maven.archetypes ^
    -DarchetypeArtifactId=devonline-archetype-jar ^
    -DinteractiveMode=false ^
    -DgroupId=org.example ^
    -DartifactId=simple ^
    -Dversion=2.0-SNAPSHOT ^
    -Dpackage=org.example.simple.root
```

Using interactive mode:

```bash
mvn archetype:generate ^
    -DarchetypeCatalog=local ^
    -DarchetypeGroupId=academy.devonline.maven.archetypes ^
    -DarchetypeArtifactId=devonline-archetype-jar ^
    -DinteractiveMode=true
```

### For MacOS or Linux:

Using default settings:

```bash
mvn archetype:generate \
    -DarchetypeCatalog=local \
    -DarchetypeGroupId=academy.devonline.maven.archetypes \
    -DarchetypeArtifactId=devonline-archetype-jar \
    -DinteractiveMode=false \
    -DartifactId=simple
```

Using custom settings:

```bash
mvn archetype:generate \
    -DarchetypeCatalog=local \
    -DarchetypeGroupId=academy.devonline.maven.archetypes \
    -DarchetypeArtifactId=devonline-archetype-jar \
    -DinteractiveMode=false \
    -DgroupId=org.example \
    -DartifactId=simple \
    -Dversion=2.0-SNAPSHOT \
    -Dpackage=org.example.simple.root
```

Using interactive mode:

```bash
mvn archetype:generate \
    -DarchetypeCatalog=local \
    -DarchetypeGroupId=academy.devonline.maven.archetypes \
    -DarchetypeArtifactId=devonline-archetype-jar \
    -DinteractiveMode=true
```

-----------------------------------------------------------------------------------


## Readme tutorial

- https://guides.github.com/features/mastering-markdown/
- https://help.github.com/categories/writing-on-github/
