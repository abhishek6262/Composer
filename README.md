# Composer
The instance of Project-Level Composer.

This composer package allows you to install composer on your project level so you don't have to install composer on your system. Moreover you can consume the power of composer outside of the terminal as you do use any other PHP class.

## Examples
```
require_once 'Path\To\Composer.php';

$composer = new \Composer('pathToProjectRoot', 'pathToBinDirectory');

if (! $composer->exists()) {
  $composer->install();
}
```

## Credits

- [Abhishek Prakash](https://github.com/abhishek6262)

## Contributing
Please feel free to fork this package and contribute by submitting a pull request to enhance the functionalities. I will appreciate that a lot. Also please add your name to the credits.

Kindly [follow me on twitter](https://twitter.com/_the_shade)!

## License

The GNU General Public License v3.0. Please see [License File](LICENSE) for more information.
