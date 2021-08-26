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
## Setup instructions:

### For Windows:

1. Install `wget` tool for Windows:

*For example from here: https://eternallybored.org/misc/wget/*

2. Setup `devonline-archetype-jar` archetype using `wget` tool:

```cmd
wget -O %TMP%\archetype.jar ^
  -q https://github.com/devonline-academy/devonline-archetype-jar/releases/latest/download/devonline-archetype-jar-1.0.jar ^
     && mvn org.apache.maven.plugins:maven-install-plugin:3.0.0-M1:install-file -Dfile=%TMP%\archetype.jar ^
     && del /f /q %TMP%\archetype.jar
```

### For MacOS

Setup `devonline-archetype-jar` archetype using `curl` tool

*(FYI: If `curl` tool is not available on your computer, please install this tool manually before using the following setup instructions)*

```bash
curl -o /tmp/archetype.jar \
    -L -s https://github.com/devonline-academy/devonline-archetype-jar/releases/latest/download/devonline-archetype-jar-1.0.jar \
    && mvn org.apache.maven.plugins:maven-install-plugin:3.0.0-M1:install-file -Dfile=/tmp/archetype.jar \
    && rm -rf /tmp/archetype.jar
```

### For Linux

Setup `devonline-archetype-jar` archetype using `wget` tool

*(FYI: If `wget` tool is not available on your computer, please install this tool manually before using the following setup instructions)*

```bash
wget -O /tmp/archetype.jar \
    -q https://github.com/devonline-academy/devonline-archetype-jar/releases/latest/download/devonline-archetype-jar-1.0.jar \
    && mvn org.apache.maven.plugins:maven-install-plugin:3.0.0-M1:install-file -Dfile=/tmp/archetype.jar \
    && rm -rf /tmp/archetype.jar
```
-----------------------------------------------------------------------------------

## Build instructions:

#### 1. Install the `3.2.1-SNAPSHOT` version of the `maven-archetype-plugin`:

```bash
mvn install:install-file -Dfile=.plugins/maven-archetype-plugin-3.2.1-SNAPSHOT.jar
```

#### 2. Build the latest version of the `devonline-archetype-jar` archetype and install to the local maven repository:

```bash
mvn clean install
```

-----------------------------------------------------------------------------------


## Readme tutorial

- https://guides.github.com/features/mastering-markdown/
- https://help.github.com/categories/writing-on-github/
