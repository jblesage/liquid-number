Liquid-Number
=============

A Jekyll/Liquid plugin that formats numbers

## Installation and Usage

To use this plugin with [Jekyll](http://jekyllrb.com/), copy `pluralize.rb` to your `_plugins` folder.

The only function available is `number`. It can be used in two ways: 

* to use a standard number separator:
  raw_number = 2345

    {{ raw_number | number }}

  will output 2,345

* to use a custom number separator:
  raw_number = 2345

    {{ raw_number | number: " " }}

  will output 2 345

## Bugs

This was written quickly and for a very specific purpose. Therefore, it currently does not support numbers with decimals, only whole numbers.

## Contact

E-mail [Jean-Benoit Lesage](mailto:jblesage@alphalist.ca) with questions or comments.

This project is [hosted on GitHub](https://github.com/jblesage/liquid-number). Please feel free to submit issues and pull requests.

## License

This script is hereby released into the public domain. To the extent possible, the author places no restrictions upon its use, modification, or redistribution.