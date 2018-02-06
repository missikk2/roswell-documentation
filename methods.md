# Defining Styles in Digital and Print

We can use the same page to toggle styles that are used in digital and print.

{% method %}
## My first style

My first method exposes how to print a message in digital and print.

{% sample lang="dig" %}
Here is how to print a message to `stdout` in digital.

```js
console.log('My first method');
```

{% sample lang="print" %}
Here is how to print a message to `stdout` in print.

```go
fmt.Println("My first method")
```

{% common %}
We can also display content or styles that are common between the two.

```bash
$ My first method
```
{% endmethod %}
