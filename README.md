Badges for Maven projects
=========================
[![Dependency Status](https://gemnasium.com/jirutka/maven-badges.svg)](https://gemnasium.com/jirutka/maven-badges)

## Outdated

We have migrated this project to NodeJS and you can find a new version [here](https://github.com/softwaremill/maven-badges). Please report any issues there, PRs are welcome as well :)

## Description

Badges! These tiny pictures with label and some numbers, you see them in many GitHub readmes. We all love them, yeah? Travis, Coveralls, Code Climate, Gemnasium, Gem, PyPi, npm… 
However, most of them are not usable for Java/Groovy guys and that’s quite sad, isn’t it?

Well, I put together [shields.io](http://shields.io/), [Heroku](https://heroku.com) and some Ruby code to generate a shiny badge that shows an artifact’s version available in Maven Central.


Usage
-----

    https://maven-badges.herokuapp.com/maven-central/{group_id}/{artifact_id}/badge.(svg|png)?style={style}

For example:

	[![Maven Central](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser)

[![Maven Central](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser/badge.svg)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser)

	[![Maven Central](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser)

[![Maven Central](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser/badge.svg?style=plastic)](https://maven-badges.herokuapp.com/maven-central/cz.jirutka.rsql/rsql-parser)

License
-------
This project is licensed under [MIT license](http://opensource.org/licenses/MIT).
