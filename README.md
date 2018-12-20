# 5_BT_bangCuuChuong
Viết một ứng dụng để in ra trang web một bảng cửu chương
Cách 1:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>BCC</title>
</head>
<body>
    <script>
        document.write("<table border=1 width=30%>")
        for(i=1;i<=9;i++)
        {
            document.write("<tr>")
            for(n=2;n<=9;n++)
                document.write("<td>" +n + "x" + i +"="+ (n*i));
            document.write("</td>");
            document.write("</tr>")
        }
        document.write("</tr></table>")
    </script>
</body>
</html>

cách 2: 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>BCC</title>
</head>
<body>
    <script>
        for(i=1;i<=9;i++)
        {
            document.write("<br>")
            for(n=2;n<=9;n++)
                document.write("<td>" +n + "x" + i +"="+ (n*i)+' . ');
                document.write("<br>");
        }
    </script>
</body>
</html>
