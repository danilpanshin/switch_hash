# switch_hash
Меняем switch - case(if - else) на более интересный вариант:

<?php declare(strict_types=1);

 $switch = ['foo' => function():void {echo 'code:)';}, 'bar' => 'bar', 'baz' => 1][$val] ?? function():string {return 'default';};
