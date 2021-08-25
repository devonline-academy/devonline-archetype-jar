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

## Build instructions:

#### 1. Install the `3.2.1-SNAPSHOT` version of the `maven-archetype-plugin`:

**For Windows:**

```bash
mvn install:install-file ^
  -Dfile=.plugins/maven-archetype-plugin-3.2.1-SNAPSHOT.jar ^
  -DpomFile=.plugins/maven-archetype-plugin-3.2.1-SNAPSHOT.pom
```

**For MacOS or Linux:**

```bash
mvn install:install-file \
  -Dfile=.plugins/maven-archetype-plugin-3.2.1-SNAPSHOT.jar \
  -DpomFile=.plugins/maven-archetype-plugin-3.2.1-SNAPSHOT.pom
```

#### 2. Build the latest version of the `devonline-archetype-jar` archetype and install to the local maven repository:

```bash
mvn clean install
```

-----------------------------------------------------------------------------------


## Readme tutorial

- https://guides.github.com/features/mastering-markdown/
- https://help.github.com/categories/writing-on-github/
