2022.04.19 Частотный преобразователь Toshiba 37кВт, управляет электродвигателем подъема ж/д 
укладочного крана УК-25 (стоит два одинаковых электродвигателя и два одинаковых ЧП). Частотный преобразователь вышел из строя.
В процессе диагностики выявлено - произошел пробой одного IGBT-модуля, так же - 
вышел из строя драйвер управления данным плечом (одно плечо = 2 IGBT модуля).
Расчертил схему драйвера, стало понятно, что выход из строя произошел только из-за проблем с питанием драйвера.
Виной всему изменение в процессе эксплуатации параметров фильтрующих электролитических конденсаторов блока питания драйвера.
По отдельности на каждый драйвер запитан от отдельной обмотки одного импульсного источника питания.
Заменены фильтрующие, электролитические конденсаторы, элементы вышедшего из строя драйвера , один IGBT-модуль, 
произведена настройка частотного преобразователя.
