Проверка принадлежности пользователя к указанным веб-группам. Если пользователь принадлежит хотя бы к одной из групп, то возвращается true, иначе false

Замечание: если $groupNames не является массивом, то метод вернет false

Замечание: для проверки членства пользователя в той или иной группе лучше использовать метод getUserDocGroups.

bool isMemberOfWebGroup(array $groupNames);

$groupNames - массив пользовательских групп
Пример

$test = $modx->isMemberOfWebGroup( array('Editors')); // true