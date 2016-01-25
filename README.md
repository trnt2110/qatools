# qatools
QA tool for checking coding standard, coding rule

Download nessesary tools:

# 1. php-cs-fixer
* wget http://get.sensiolabs.org/php-cs-fixer.phar -O php-cs-fixer
* sudo mv php-cs-fixer /usr/local/bin/php-cs-fixer

# 2. phpmd
* wget -c http://static.phpmd.org/php/latest/phpmd.phar
* sudo chmod +x phpmd.phar
* sudo mv phpmd.phar /usr/local/bin/phpmd

# 3. phpdcd
* wget https://phar.phpunit.de/phpdcd.phar
* chmod +x phpdcd.phar
* mv phpdcd.phar /usr/local/bin/phpdcd

# 4. phpcpd
* wget https://phar.phpunit.de/phpcpd.phar
* chmod +x phpcpd.phar
* sudo mv phpcpd.phar /usr/local/bin/phpcpd

# 5. phpcs
* curl -OL https://squizlabs.github.io/PHP_CodeSniffer/phpcs.phar
* chmod +x phpcs.phar
* sudo mv phpcs.phar /usr/local/bin/phpcs

# 6. phpcbf
* curl -OL https://squizlabs.github.io/PHP_CodeSniffer/phpcbf.phar
* chmod +x phpcbf.phar
* sudo mv phpcbf.phar /usr/local/bin/phpcbf

# 7. How to run
* git clone https://github.com/thangnvaltplus/qatools.git
* cd qatools
* cp pre-commit [your project]/.git/hooks/
* chmod +x [your project]/.git/hooks/pre-commit
* edit code & commit. The qatools automatic check with above tools

# 8. References
* php-cs-fixer
http://cs.sensiolabs.org/
* php-cs & phpcbf
https://github.com/squizlabs/PHP_CodeSniffer
* phpmd
http://phpmd.org/
* phpdcd
https://github.com/sebastianbergmann/phpdcd
* phpcpd
https://github.com/sebastianbergmann/phpcpd
