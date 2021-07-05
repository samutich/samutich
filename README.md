```java

public class StepanSamutichev {
    private static final String NAME = "Stepan";
    private static final String SURNAME = "Samutichev";
    private static final String TELEGRAM = "@samutich";
    private static final String EMAIL = "stepan.samutichev@gmail.com";

    @Override
    public String toString() {
        return String.format("%s %s", NAME, SURNAME);
    }

    public static void main(String[] args) {
        StepanSamutichev stepan = new StepanSamutichev();
        System.out.println(stepan);
    }
}

```
