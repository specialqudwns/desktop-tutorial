# API test 변경



## Create a new user

<mark style="color:green;">`GET`</mark>`/users`

\<Description of t 변경했he endp엉해oint>x xxxxxxx

**Headers**

| Name          | Value              |
| ------------- | ------------------ |
| Content-Type  | `application/json` |
| Authorization | `Bearer <token>`   |

**Body**

| Name   | Type   | Description      |
| ------ | ------ | ---------------- |
| `name` | string | Name of the user |
| `age`  | number | Age of the user  |

**Response**

{% tabs %}
{% tab title="200" %}
```json
{
  "id": 1,
  "name": "John",
  "age": 30
}
```
{% endtab %}

{% tab title="400" %}
```json
{
  "error": "Invalid request"
}
```
{% endtab %}

{% tab title="500" %}
```json
{
  "error": "Invalid request"
}
```
{% endtab %}
{% endtabs %}
