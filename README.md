# Laravel-JDF

[![Latest Stable Version](https://poser.pugx.org/hatamiarash7/jdf/v/stable)](https://packagist.org/packages/hatamiarash7/jdf) [![Total Downloads](https://poser.pugx.org/hatamiarash7/jdf/downloads)](https://packagist.org/packages/hatamiarash7/jdf) [![License](https://poser.pugx.org/hatamiarash7/jdf/license)](https://packagist.org/packages/hatamiarash7/jdf)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fhatamiarash7%2FLaravel-JDF.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fhatamiarash7%2FLaravel-JDF?ref=badge_shield)

It's a simple library to use Persian timestamps in Laravel ( 5.5+ / 6 / 7 )

### Install

`composer require majeed21/jdf`

Laravel 5.5+ has auto-discover ability and you don't need add anything to project's configuration

### How to use

```php
use Majeed21\JDF\JDF;

...

$jdf = new JDF();
$date = $jdf->getTimestamp(); // Output : ۱۳۹۷/۱۱/۰۲ - ۰۰:۳۸

$finalDate = $jdf->jdate_words(['ss'=>1390, 'mm'=>5, 'rr'=>20]);
// Output : [
		'ss' => 'هزار و سیصد و نود' ,
		'mm' => 'مرداد' ,
		'rr' => 'بیست'
	    ]
```

## Contributing

1. Fork it !
2. Create your feature branch : `git checkout -b my-new-feature`
3. Commit your changes : `git commit -am 'Add some feature'`
4. Push to the branch : `git push origin my-new-feature`
5. Submit a pull request :D

## Issues

Each project may have many problems. Contributing to the better development of this project by reporting them.
