## Урок 3. Задача №1

[Ссылка на код Main.java](https://github.com/npetyaeva/javaLesson_3_1/blob/master/src/Main.java)

```java
public class Main {
    public static void main(String[] args) {

        BonusMilesService service = new BonusMilesService();

        int price = 10_000;

        int miles = service.calculate(price);
        System.out.println(miles + " miles");
    }
}
```

[Ссылка на код BonusMilesService.java](https://github.com/npetyaeva/javaLesson_3_1/blob/master/src/BonusMilesService.java)

```java
public class BonusMilesService {

    public int calculate (int cost) {

        int pricePerMile = 20;
        return cost / pricePerMile;
    }
}
```
