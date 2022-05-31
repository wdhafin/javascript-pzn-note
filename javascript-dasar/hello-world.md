# Hello World

## Membuat Kode JavaScript

Ada beberapa cara untuk membuat kode JavaScript

* Bisa langsung di file HTML.
* Bisa menggunakan file .js ( ekstensi untuk JavaScript ), lalu di include di dalam file HTML.

## Program Hello World

### Inline HTML

{% tabs %}
{% tab title="hello-world.html" %}
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <script>
      document.writeln('Hello World');
    </script>
  </body>
</html>
```
{% endtab %}
{% endtabs %}

### Import JS File

{% tabs %}
{% tab title="hello-world-include.html" %}
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <script src="scripts/hello-world.js"></script>
  </body>
</html>

```
{% endtab %}

{% tab title="scripts/hello-world.js" %}
```javascript
document.writeln('Hello World');
```
{% endtab %}
{% endtabs %}

## Titik Koma

* JavaScript mirip seperti bahasa pemrograman C/C++, dimana di akhir setiap statement kode program, kita perlu menambahkan ; ( titik koma ).
* Namun, di JavaScript tanda ; ( titik koma ) tidak wajib, jadi kita bisa menambahkan ataupun tidak.
* Sangat disarankan konsisten, jika ingin menggunakan titik koma, gunakan disemua tempat, jika tidak, jangan gunakan di semua tempat.
