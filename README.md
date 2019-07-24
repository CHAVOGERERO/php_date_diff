# php_date_diff


```
function timestampdiff($qw,$saw)
{
    $datetime1 = new DateTime("@$qw");
    $datetime2 = new DateTime("@$saw");
    $interval = $datetime1->diff($datetime2);
    return $interval->format('%H:%I:%S');
}
```
