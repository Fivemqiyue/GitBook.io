# Interactive blocks

## Make your docs come alive

GitBook offers various interactive blocks to enhance user experience.

### Tabs

Organize content in tabs for different platforms or languages:

{% tabs %}
{% tab title="JavaScript" %}
```javascript
console.log("Hello");
```
{% endtab %}

{% tab title="Python" %}
```python
print("Hello")
```
{% endtab %}
{% endtabs %}

### Hints

Add colored hint boxes for important information:

{% hint style="info" %}
This is an info hint
{% endhint %}

{% hint style="warning" %}
This is a warning hint
{% endhint %}

{% hint style="danger" %}
This is a danger hint
{% endhint %}

### Expandable sections

Use expandable blocks for optional content:

<details>
<summary>Click to expand</summary>

Hidden content goes here.

</details>

### API method blocks

Document your API endpoints clearly:

{% swagger method="get" path="/users" baseUrl="https://api.example.com" summary="Get all users" %}
{% endswagger %}
