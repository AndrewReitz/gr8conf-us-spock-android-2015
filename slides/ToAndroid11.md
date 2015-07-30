## Get Spock to Android!

IT WORKS!

```groovy
class AndroidTestSpec extends Specification {
  def "this should run on Android!"() {
    given:
    def a = 2
    def b = 3

    when:
    def result = a + b

    then:
    result == 5
  }
}
```