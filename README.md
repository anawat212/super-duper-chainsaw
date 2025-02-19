<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Upload .PBO File</title>
</head>
<body>
    <h1>Upload .PBO File</h1>
    <form action="upload.php" method="POST" enctype="multipart/form-data">
        <label for="fileToUpload">Choose .PBO File:</label>
        <input type="file" name="fileToUpload" id="fileToUpload" accept=".pbo">
        <input type="submit" value="Upload File" name="submit">
    </form>
</body>
</html>
