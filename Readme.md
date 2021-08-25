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
git clone https://github.com/apache/maven-archetype ^
    && cd maven-archetype ^
    && git checkout 54b5fb4bf16d70fce0ab3493d2e178b317a2f5b7 ^
    && mvn install ^
    && cd ../ ^
    && rmdir /S /Q maven-archetype
```

**For MacOS or Linux:**

```bash
git clone https://github.com/apache/maven-archetype \
    && cd maven-archetype \
    && git checkout 54b5fb4bf16d70fce0ab3493d2e178b317a2f5b7 \
    && mvn install \
    && cd ../ \
    && rm -f -R maven-archetype
```

#### 2. Build the latest version of the `devonline-archetype-jar` archetype and install to the local maven repository:

```bash
mvn clean install
```

-----------------------------------------------------------------------------------


## Readme tutorial

- https://guides.github.com/features/mastering-markdown/
- https://help.github.com/categories/writing-on-github/
