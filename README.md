# Static analysis tools for PHP

A curated list of static analysis tools for PHP.

## Contributing

See [CONTRIBUTING](https://github.com/exakat/php-static-analysis-tools/blob/master/CONTRIBUTING.md).

## Table of Contents

* [Bugs finders](#bugs-finders)
* [Coding standards](#coding-standards)
* [DIY](#diy)
* [Fixers](#fixers)
* [Metrics](#metrics)
* [SaaS](#saas)
* [Misc](#misc)

### Bugs finders

Tools to report issues in code that are or lead to bugs.

* [Churn-PHP](https://github.com/bmitch/churn-php.git) - Discover files in need of refactoring.
* [jscpd](https://github.com/kucherenko/jscpd) - Copy/paste detector for programming source code. 
* [noverify](https://github.com/VKCOM/noverify) - Pretty fast linter (code static analysis utility) for PHP.
* [Pfff](https://github.com/facebook/pfff) - Tools for code analysis, visualizations, or style-preserving source transformation.
* [PHP Architecture Tester](https://github.com/carlosas/phpat) - Easy to use architecture testing tool for PHP
* [PHParch](https://github.com/j6s/phparch.git) - PHPArch is a work in progress architectural testing library for PHP projects. 
* [PHPCodeFixer](https://github.com/wapmorgan/PhpCodeFixer) -  Finds usage of deprecated functions, variables and ini directives.
* [php-compat-info](https://github.com/llaville/php-compat-info) - Find out the minimum version and the extensions required for a piece of code to run.
* [PHPCPD](https://github.com/sebastianbergmann/phpcpd) - Spots copy/pasted code, and help enforcing DRY rule.
* [Phan](https://github.com/etsy/phan) - The static analyzer by Rasmus, PHP Creator.
* [PHP Inspection](https://plugins.jetbrains.com/plugin/7622?pr=idea) - Static analysis plugin for PHPStorm.
* [PHPlint](http://www.icosaedro.it/phplint/) - A validator and documentator for PHP 5 programs.
* [PHP-Parallel-Lint](https://github.com/php-parallel-lint/PHP-Parallel-Lint) - A parallel php linting tool for PHP 5.4 or newer
* [PHP Magic Number Detector](https://github.com/povils/phpmnd) - PHP Magic Number Detector
* [PHP-malware-finder](https://github.com/nbs-system/php-malware-finder) - Detect potentially malicious PHP files
* [PHP Mess Detector](http://phpmd.org/) - Look for several potential problems within source code.
* [PHP SA](https://github.com/ovr/phpsa) - A development tool aimed at bringing complex analysis for PHP applications and libraries.
* [PHP Stan](https://github.com/phpstan/phpstan) - Focuses on finding errors in code without actually running it.
* [Progpilot](https://github.com/designsecurity/progpilot) - A static analysis tool for security purposes.
* [Psalm](https://getpsalm.org/) - A static analysis tool for finding errors in PHP applications.
* [psecio:parse](https://github.com/psecio/parse.git) - Parse : A PHP Security Scanner.
* [Serenta](https://gitlab.com/Serenata/Serenata) - Indexes PHP code and performs static analysis for Atom editor.
* [SonarQube](http://www.sonarqube.org/) - An open platform to manage code quality. It covers PHP code.
* [Unused-scanner](https://github.com/Insolita/unused-scanner.git) - Detect unused composer dependencies
* [PHP VarDump Check](https://github.com/JakubOnderka/PHP-Var-Dump-Check) - PHP console application for finding forgotten variable dump.

### Coding standards

Tools to review the way PHP code was written and more.

* [PHP Code Sniffer](https://github.com/squizlabs/PHP_CodeSniffer) - PHPCS checks the code for a large range of coding standard.
* [EasyCodingStandard](https://github.com/Symplify/EasyCodingStandard) - An easy to use tool, that allows to use CodeSniffer and PHP-CS-Fixer in simple way.
* [PHPCheckstyle](https://github.com/PHPCheckstyle/phpcheckstyle) - A tool to help adhere to certain coding conventions.
* [Pahout](https://github.com/wata727/pahout) - A pair programming partner for writing better PHP.

### Fixers

Tools to automatically fix the code they are provided with.

* [Rector](https://github.com/rectorphp/rector) - AST-based Instant Upgrades of PHP Applications
* [PHP CS Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) - Analyzes and tries to fix coding standards issues (PSR-1 and PSR-2 compatible).
* [php-scoper](https://github.com/humbug/php-scoper) -  Prefixes all PHP namespaces in a file/directory to isolate the code bundled in PHARs.
* [PHP Weaver](https://github.com/troelskn/phpweaver) - Analysing parameter types at runtime and generate the appropriate phpdocs.

### Metrics

Tools to measure the code complexity, line of codes, etc.

* [churn-php](https://github.com/bmitch/churn-php) - Helps discover good candidates for refactoring.
* [dePHPend](https://github.com/mihaeu/dephpend) - dePHPend helps analyze dependencies & architecture and allows you to define constraints for both.
* [PHPLOC](https://github.com/sebastianbergmann/phploc) - Utility to measures PHP application size and count various structures.
* [PHP Metrics](https://github.com/Halleck45/PhpMetrics) - Calculates all sorts of metrics, and display them in a gorgeous interface.

### SaaS

Online services for PHP code, provide dashboards. They may use the previous tools or offer their own.

* [Checkmarx](http://lp.checkmarx.com/php-code-analysis/) - Get a full PHP  static security code analysis and prevent security vulnerabilities.
* [Codacy](https://www.codacy.com/) - Codacy: Automated Code Review.
* [Code Climate](https://codeclimate.com) - Hosted static analysis for Ruby, PHP and JavaScript source code.
* [CodeScene](https://codescene.io/) - Prioritize technical debt in PHP, JavaScript, etc.
* [RIPS](https://www.ripstech.com/) - The superior security software for PHP applications. Source code static analyser for vulnerabilities.
* [Scrutinizer](https://scrutinizer-ci.com/) - Improve code quality and find bugs before they hit production with our continuous inspection platform.
* [SideCI](https://sideci.com/) - CI for automated code review by code analysis.
* [Laravelshift](https://laravelshift.com/) - the automated way to upgrade Laravel applications. Upgrade Laravel applications all the way from Laravel 4.2 to the latest version of Laravel.

## Misc

* [HHVM](http://hhvm.com/) - Hack Language from Facebook. Add a SCA until version 3.3.8, newer version doesn't have anymore.
* [PHPQA](https://edgedesigncz.github.io/phpqa/) - A Wrapper to a lot of PHP tools reported into a single HTML file.
* [Fixtro](https://github.com/karlosagudo/fixtro) - A wrapper that allow to run in each precommit. It install itself all the dependencies for the runners with a lot of them (phpunit, phpmd, php-cs-fixer, etc..)
* [Coverage Checker](https://github.com/exussum12/coverageChecker) - A tool which allows some of the tools here to be enforced on changed code only. Good for moving towards new standards
* [Composer Require Checker](https://github.com/maglnet/ComposerRequireChecker) - A CLI tool to check whether a specific composer package uses imported symbols that aren't part of its direct composer dependencies
* [Static Analysis Results Baseliner](https://github.com/DaveLiddament/sarb) - A tool for generating a baseline from static analysis tools. 
