1. index.html


<!DOCTYPE html>
<html>
<head>
    <title>CSS Box Model</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Box Model Practice</h1>

    <div class="box1">
        <h2>Box 1</h2>
        <p>Content Box</p>
    </div>

    <div class="box2">
        <h2>Box 2</h2>
        <p>Border Box</p>
    </div>

    <div class="box3">
        <h2>Box 3</h2>
        <p>Different Spacing</p>
    </div>
</body>
</html>

2. style.css


div {
    background: lightblue;
    width: 200px;
}
.box1 {
    padding: 20px;
    border: 5px solid blue;
    margin: 20px;
    box-sizing: content-box;
}
.box2 {
    padding: 30px;
    border: 3px solid green;
    margin: 30px;
    box-sizing: border-box;
}
.box3 {
    padding: 10px;
    border: 8px solid red;
    margin: 40px;
}

Box Model Parts:

Content: Text or information inside the box.

Padding: Space between content and border.

Border: Line surrounding the padding and content.

Margin: Space outside the border.

Difference: content-box adds padding and border outside the specified width, while border-box includes them within the specified width.