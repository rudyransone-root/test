###### ANSI Color

**Colors**
* BLACK
* WHITE
* GREEN
* RED
* YELLOW
* BLUE
* PURPLE
* CYAN

**Functions**
* `color.fg(Colors.TYPE);`
* `color.bg(Colors.TYPE);`

**Example**
```java
    class Main {
        public static void main(String[] args) {
            Color color = new Color();

            System.out.println(color.fg(Colors.GREEN) + "Hello, World!" + color.reset());
        }
    }
```
