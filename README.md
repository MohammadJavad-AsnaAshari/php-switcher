# PHP Switcher

A simple bash script to switch between different PHP versions installed on your system.

## Requirements

- Bash
- sudo access
- Multiple PHP versions installed

## Usage

To switch to a specific PHP version, run the script followed by the desired PHP version number:

php-switcher <version>


Replace `<version>` with the desired PHP version (e.g., `7.4`, `8.0`, `8.1`). The script will create a symbolic link to the specified PHP version in `/usr/bin/php`.

## Example

Switch to PHP 7.4:
```
php-switcher 7.4
```

## Error Handling

If you don't provide a PHP version or the specified version is not found, the script will display an error message and exit with a non-zero status code.

## Clone and Install the Script

Follow these steps to clone the `php-switcher` script and make it available on your system:

1. Clone the repository to your local machine:
```
git clone https://github.com/MohammadJavad-AsnaAshari/php-switcher.git 
```

2. Change to the cloned repository directory:
```
cd php-switcher
```

3. Copy the `php-switcher` script to a directory that is in your system's `$PATH`, such as `/usr/local/bin`:
```
cp php-switcher /usr/local/bin/
```

4. Make the script executable:
```
chmod +x /usr/local/bin/php-switcher
```

Now, you can use the `php-switcher` script as described in the "Usage" section.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

