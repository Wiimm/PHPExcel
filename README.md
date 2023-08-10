# PHPExcel

PHPExcel last version, 1.8.1, was released in 2015. The project was officially deprecated in 2017 and permanently archived in 2019.

The project has not be maintained for years and should  not be used anymore. All users should must migrate to its direct successor [PhpSpreadsheet](https://github.com/PHPOffice/PhpSpreadsheet), or another alternative.

## Update in 2023 (PHP 8 support)

I was tasked with migrating 2 websites to a new server running PHP 8. Both projects worked after minimal adjustments, only the creation of Excel files with PHPExcel failed.

Now I had 2 alternatives. For one, I could rewrite the code on PhpSpreadsheet, which would mean a significant amount of work for me. On the other hand, I could look at the errors that PHPExcel throws and then correct them. I chose the second way and needed just 20 minutes for the corrections.

This fork contains exactly these corrections and makes PHPExcel and PHP 8 executable.

## License

PHPExcel is licensed under [LGPL (GNU LESSER GENERAL PUBLIC LICENSE)](https://github.com/PHPOffice/PHPExcel/blob/master/license.md)
