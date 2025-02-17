# yanivlakhani.github.io

<!DOCTYPE html>
<html>

<head>
    <title>PDF in HTML</title>
</head>
<style>
    .pdf {
        width: 100%;
        aspect-ratio: 4 / 3;
    }

    .pdf,
    html,
    body {
        height: 100%;
        margin: 0;
        padding: 0;
    }

    h1,
    h3 {
        text-align: center;
    }

    h1 {
        color: green;
    }
</style>

<body>

    <h1>GeeksforGeeks</h1>
    <h3>Embedding the PDF file Using Object Tag</h3>
    <object class="pdf" 
            data=
"https://technolutions-us-east-1.s3.amazonaws.com/media/a/5/9/a5953834a10043179b23e8c16ffc9aa4.pdf?AWSAccessKeyId=AKIAQLKYRJEAOJ7ACURH&Expires=1739816825&response-content-type=application%2Fpdf&Signature=fufyq6JcwfWlXGZIaW3dKS9o2%2FE%3D"
            width="800"
            height="500">
    </object>
</body>

</html>
