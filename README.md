<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AC</title>
</head>

<body>
    <ul id="myTodos"></ul>

    <input type="text" id="todoField">
    <button onclick="addTodo()">Todo hinzufügen</button>
    <script>
        function addTodo() {
            myTodos.innerHTML += `
    <li>${todoField.value}</li>
    `;

        }
    </script>
</body>

</html>
