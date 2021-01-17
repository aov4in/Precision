# Отчёт о тестировании приложения Precision

## Краткое описание

Приложение выдает некорректный результат при подсчете суммы бонусов.

## Описание тестов

Было произведено функциональное тестирование приложения
1. Создать базовое приложение и разместить в нём  код:
```
public class Main {
    public static void main(String[] args) {
        double regularBonus = 0.3;
        double specialBonus = 0.6;
        double totalBonus = regularBonus + specialBonus;
        System.out.println(totalBonus);
    }
}
```
2. Проверить его работоспособность не меняя данные.

## Результаты

1. Итоговый результат totalBonus выводится некорректно.
2. <a href="https://github.com/aov4in/Precision/issues/1#issue-787702321">Баг-репорт 1</a>