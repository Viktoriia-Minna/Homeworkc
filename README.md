<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="text-box">
        <h3>Пофарбуйте мене в рожевий колір (color:pink).</h3>
        <p>Даний елемент має залишитись неоформленим.</p>
        <p id="greycol">Пофарбуйте мене в сірий колір (color:grey).</p>
        <div>Даний елемент має залишитись неоформленим.</div>
        <div><p>Пофарбуйте мене в червоний колір (color:red).</p></div>
        <h3>Даний елемент має залишитись неоформленим.</h3>
        <p>Пофарбуйте мене в зелений колір (color:green).</p>
        <p class="yellow">Пофарбуйте мене в жовтий колір (color:yellow).</p>
      </div>

      <table>
        <thead>
                <td> Saturday </td>
                <td> Sunday </td>
        </thead>
                <tbody>
                    <tr>
            <td> Soft skills 19:00 </td>
            <td> Frontend 19:00 </td>
        </tr>
        <tr>
            <td> Frontend 20:00 </td>
        </tr>
        </tbody>
      </table>
</body>
</html>
div h3:nth-child(1) {
color: rgb(255, 0, 217);
}

#greycol  {
  color: rgb(194, 194, 194);
}
p:nth-child(1) {
  color: rgb(255, 0, 0);
}
p:nth-last-child(2) {
  color: rgb(30, 255, 0);
}
.yellow {
  color: rgb(255, 255, 0);
}




td:nth-child(1) {
  color: rgb(255, 255, 255);
  background-color: rgb(217, 184, 248);
  width: 100px;
  height: 100px;
  border: 1px solid rgb(0, 0, 0);
  text-align: center;
}
td:nth-child(2) {
  color: rgb(255, 255, 255);
  background-color: rgb(0, 0, 0);
  width: 100px;
  height: 100px;
  border: 1px solid rgb(233, 192, 231);
  text-align: center;
}
