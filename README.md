# Encryptable
This package adds the encryptable trait to your laravel model which automatically encrypts and decrypts them when communicating with the database.

## Installation

First, make sure you have the [Code Orange package registry](http://hub.nub.is/packages) set up correctly.

```
composer require code-orange/encryptable
```

## Usage

Add a protected $encrypted trait to your laravel model. I.E:

```
protected $encryptable = [
		'first_name', 'last_name', 'country', 'zipcode', 'housenumber', 'street', 'city', 'phone', 'email',
	];
```
