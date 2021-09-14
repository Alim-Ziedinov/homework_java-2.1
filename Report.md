# Отчёт о тестировании homework_java-2.1
## Тестирование части JAVA кода

14.09.2021 20:00 - 14.09.2021 20:40 было проведено в приложении IntelliJ IDEA.

На тестирование затрачено: 40 минуты

В результате тестирования выявлены следующие дефекты:
* [Некорректное отображение значения переменной баланса  в java коде #1](https://github.com/Alim-Ziedinov/homework_java-2.1/issues/1#issue-996292688)


В качестве тестовых данных использовался следующая часть JAVA кода:
```
public class Balans {
    public static void main(String[] args) {
        int price = 2_000_000_000;
        int count = 500_000_000;
        int total = price + count;
        System.out.println(total);
    }
}
```


Тестирование производилось в следующем окружении:
* PC, Windows 8Pro 64-bit
* Java v.11
* IntelliJ IDEA v2021.2.1