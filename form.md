# Les formulaires

Comment créer un formulaire en HTML
```html
<form action="" method=""></form>
```
| Property name         | type          | value          |
|-----------------------|---------------|----------------|
| action                | string uri    |                |
| method                | string        | "GET", "POST"  |



Example:
```html
<form action="#">
    <!-- Invisible input -->
    <input type="hidden" name="secretUserId">

    <!-- Firstname input -->
    <input type="text" name="firstname">

    <!-- Lastname input -->
    <input type="text" name="lastname">

    <input type="submit" value="Save">
</form>
```