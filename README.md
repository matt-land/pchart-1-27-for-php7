# pChart
pChart 1.27d from http://pchart.sourceforge.net/ for PHP 7

## Update for PHP 7.1

``` 
// Parts like 
$Plots = "";
$Plots[] = $X1;
$Plots[] = $Y1;
// 1st line has to be changed into
$Plots = array();
$Plots[] = $X1;
$Plots[] = $Y1;
```

Ressources:

* *[Stackoverflow](https://stackoverflow.com/questions/5879675/problem-with-fatal-error-operator-not-supported-for-strings-in/5879729)*
* *[PHP.net](https://www.php.net/manual/de/migration71.incompatible.php)*
  see "The empty index operator is not supported for strings anymore

Also see (seems to be more mature then my quick and dirty fix)

*https://github.com/milkyway-git/pChart/commit/f330e9bbc1ec79234b646e42a916a4d4493ea90e*