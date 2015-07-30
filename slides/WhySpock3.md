## Why Spock?

```groovy
class MathSpec extends Specification {
    @Unroll
    def "maximum of #a and #b should be #c" {
        expect:
        Math.max(a, b) == c

        where:
        a | b | c
        1 | 3 | 3
        7 | 4 | 4
        0 | 0 | 0
    }
}
```