# ObjectMappers

![Lines of code](https://tokei.rs/b1/github/AlexRogalskiy/object-mappers-playground?category=lines) ![GitHub closed issues](https://img.shields.io/github/issues-closed/AlexRogalskiy/object-mappers-playground) ![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/AlexRogalskiy/object-mappers-playground) ![Github All Contributors](https://img.shields.io/github/all-contributors/AlexRogalskiy/object-mappers-playground) ![GitHub repo size](https://img.shields.io/github/repo-size/AlexRogalskiy/object-mappers-playground) ![GitHub last commit](https://img.shields.io/github/last-commit/AlexRogalskiy/object-mappers-playground) ![GitHub](https://img.shields.io/github/license/AlexRogalskiy/object-mappers-playground) ![GitHub language count](https://img.shields.io/github/languages/count/AlexRogalskiy/object-mappers-playground) ![GitHub search hit counter](https://img.shields.io/github/search/AlexRogalskiy/object-mappers-playground/goto) ![GitHub Repository branches](https://badgen.net/github/branches/AlexRogalskiy/object-mappers-playground) ![GitHub Repository dependents](https://badgen.net/github/dependents-repo/AlexRogalskiy/object-mappers-playground) [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=AlexRogalskiy_object-mappers-playground&metric=alert_status)](https://sonarcloud.io/dashboard?id=AlexRogalskiy_object-mappers-playground) [![Run Status](https://api.shippable.com/projects/5fb2d6f4a4e0a80007cb1606/badge?branch=master)](./) [![BCH compliance](https://bettercodehub.com/edge/badge/AlexRogalskiy/object-mappers-playground?branch=master)](https://bettercodehub.com/) [![Build status](https://ci.appveyor.com/api/projects/status/lqu3a77c8g81808r?svg=true)](https://ci.appveyor.com/project/AlexanderRogalskiy/object-mappers-playground)

## _Summary_

Object Mappers playground is intended to provide various mapping operations on DTO objects while converting from source to target objects.

## _Description_

Playground can be used for processing and testing mapping operations in order to evaluate major available options on objects conversion.

## _Compile_

### For JDK 8

\`\`\`shell script mvn clean install -Pdev,assembly,non\_module\_java -DskipTests

```text
### For JDK 11

```shell script
mvn clean install -Pdev,assembly,module_java -DskipTests
```

## _Up and Running_

Execute the following command to start Object Mappers application:

\`\`\`shell script run.bat 

```text
## Usage

Choose one of the modules and add to your `pom.xml`

```xml
<dependency>
    <groupId>io.nullables.api.playground</groupId>
    <artifactId>objectmappers-parent</artifactId>
    <version>{lib.version}</version>
</dependency>
```

Bundle with all Object Mappers dependencies:

* [**ObjectMappers All**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-all)  

  `objectmappers-all` - Library to work with Object Mappers API.

Object Mappers module dependencies:

* [**ObjectMappers Benchmarks**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-benchmarks) `objectmappers-benchmarks` - Library with utilities for benchmarks use cases.
* [**ObjectMappers Bull**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-bull) `objectmappers-bull` - Library to work with Bull API.
* [**ObjectMappers BeanMapper**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-beanmapper) `objectmappers-beanmapper` - Library to work with BeanCP API.
* [**ObjectMappers BeanCP**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-beancp) `objectmappers-beancp` - Library to work with BeanCP API.
* [**ObjectMappers BeanUtils**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-beanutils) `objectmappers-beanutils` - Library to work with BeanUtils API.
* [**ObjectMappers Commons**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-commons) `objectmappers-commons` - Library with utilities for common use cases.
* [**ObjectMappers Datus**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-datus) `objectmappers-datus` - Library to work with Datus API.
* [**ObjectMappers Dozer**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-dozer) `objectmappers-dozer` - Library to work with Dozer API.
* [**ObjectMappers JMapper**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-jmapper) `objectmappers-jmapper` - Library to work with JMapper API.
* [**ObjectMappers MapStruct**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-mapstruct) `objectmappers-mapstruct` - Library to work with MapStruct API.
* [**ObjectMappers ModelMapper**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-modelmapper) `objectmappers-modelmapper` - Library to work with ModelMapper API.
* [**ObjectMappers Moo**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-moo) `objectmappers-moo` - Library to work with Moo API.
* [**ObjectMappers Nomin**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-nomin) `objectmappers-nomin` - Library to work with Nomin API.
* [**ObjectMappers Orika**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-orika) `objectmappers-orika` - Library to work with Orika API.
* [**ObjectMappers ReMap**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-remap) `objectmappers-remap` - Library to work with ReMap API.
* [**ObjectMappers Selma**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-selma) `objectmappers-selma` - Library to work with Selma API.
* [**ObjectMappers Smooks**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-smooks) `objectmappers-smook` - Library to work with Smooks API.
* [**ObjectMappers TestFlow**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-testflow) `objectmappers-testflow` - Library to work with TestFlow API.
* [**ObjectMappers IntegrationTests**](https://github.com/AlexRogalskiy/object-mappers-playground/tree/master/modules/objectmappers-it) `objectmappers-it` - Library with utilities for integration test use cases.

## _Documentation_

The Website with documentation content is operated by [mkdocs](https://www.mkdocs.org/).

To enable documentation view serving at _localhost_ the following steps should be considered:

1\) To install/upgrade pip command-line utility:

```text
pip install --upgrade pip
```

or if you need to install pip for the first time:

```text
python get-pip.py
```

2\) To install the mkdocs package using pip:

```text
pip install mkdocs
```

or more conveniently for Windows subsystem:

```text
python -m pip install mkdocs
python -m mkdocs
```

3\) To install the material theme for the website:

```text
pip install mkdocs-material
```

4\) To start the server at localhost by running the following command:

```text
mkdocs serve
```

5\) Open up [localhost](http://127.0.0.1:8000/) in browser to get the default documentation homepage.

## _Version Store_

[./pom.xml](https://github.com/AlexRogalskiy/object-mappers-playground/blob/master/pom.xml)

## _Miscellaneous_

You can find more useful libs and examples on [wiki](https://github.com/AlexRogalskiy/object-mappers-playground/wiki)

## _Authors_

Object Mappers is maintained by:

* [Alexander Rogalskiy](https://github.com/AlexRogalskiy) 

with community support please contact with us if you have some question or proposition.

## _Team Tools_

[![alt tag](http://pylonsproject.org/img/logo-jetbrains.png)](https://www.jetbrains.com/)

Object Mappers Team would like inform that JetBrains is helping by provided IDE to develop the application. Thanks to its support program for an Open Source projects!

[![alt tag](https://sonarcloud.io/images/project_badges/sonarcloud-white.svg)](https://sonarcloud.io/dashboard?id=org.schemaspy%3Aschemaspy)

Object Mappers project is using SonarCloud for code quality. Thanks to SonarQube Team for free analysis solution for open source projects.

[![alt tag](https://app.shippable.com/app/assets/images/shippable-logo.png)](https://www.shippable.com/)

Object Mappers project is using Shippable DevOps and CI automation tool.

[![Edit with Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/AlexRogalskiy/object-mappers-playground)

Object Mappers has experimental support for Gitpod, a pre-configured development environment that runs in your browser. To use Gitpod, click the button below and sign in with GitHub. Gitpod also offers a browser add-on, though it is not required.

## _License_

Object Mappers is distributed under LGPL version 3 or later, see COPYING.LESSER\(LGPL\) and COPYING\(GPL\).  
LGPLv3 is additional permissions on top of GPLv3.

![image](https://user-images.githubusercontent.com/19885116/48661948-6cf97e80-ea7a-11e8-97e7-b45332a13e49.png)

## _Development Support_

Like _Object Mappers_ ? Consider buying me a coffee :\)

[![Buy Me A Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/AlexRogalskiy)

