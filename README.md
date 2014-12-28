# Roman Numeral Converter
Allows you to easily convert numbers to their roman numeral equivalent.

### Example Usage
```php
<?php

require 'vendor/autoload.php';

$converter = new RomanNumeralsConverter();

// Convert numbers and return the Roman Numeral Equivalent
echo $converter->convert(1); // Outputs I

echo $converter->convert(10); // Outputs X

echo $converter->convert(1000); // Outputs M

echo $converter->convert(4990); // Outputs MMMMCMXC

```