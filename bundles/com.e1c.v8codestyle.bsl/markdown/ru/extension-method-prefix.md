# У метода отсутствует префикс расширения

Все добавленные объекты (методы и объекты, отчеты, обработки и подсистемы, а также обработчики событий) расширения, 
а также имена собственных методов и переменных расширяющих модулей, должны иметь префикс, 
соответствующий префиксу самого расширения.

## Неправильно

```bsl
&Before("NonComplient")
Процедура Ext_НеправильныйМетод()
    //
КонецПроцедуры
```

## Правильно

```bsl
&After("Complient")
Процедура Ext1_ПравильныйМетод()
    //
КонецПроцедуры
```

## См.


- [Требования к программным продуктам](https://1c.ru/rus/products/1c/predpr/compat/soft/requirements.htm)