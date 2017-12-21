# interview-questions
# not categorized yet
* FP, main principles
* DTO
* VO
* How do u stay up to date with latest trends?
# JS
* async awaint
* promise
* callback
## React
* stateless components, functional components
* perf optimalization
* HOC
## Redux
## Webpack
## Typescript, Flow, Elm

# PHP
## PHP7
* `anonymous class`
* `??`
* `<=>`
* types!
* [extremely-defensive-php](https://ocramius.github.io/extremely-defensive-php/#/)
## Examples
```php
class Train
{
    public function __construct(array $wagons)
    {
        $this->wagons = (function (Wagon ...$wagons) {
            return $wagons;
        })(...$wagons);
    }
}
```

```php
$username = $_GET['user'] ?? 'nobody';

$gen = (function() {
    yield 1;
    yield 2;

    return 3;
})();
```
