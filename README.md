<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>White Wolf Image</title>
    <style>
        #wolf-image {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <div id="image-container"></div>

    <script>
        function showWhiteWolf() {
            const imageContainer = document.getElementById('image-container');
            const img = document.createElement('img');
            img.src = 'https://www.google.com/search?q=white+wolf&rlz=1CDGOYI_enUS1096US1096&oq=white+wolf&gs_lcrp=EgZjaHJvbWUyBggAEEUYOdIBCDI0MTZqMGo0qAICsAIB4gMEGAEgXw&hl=en-US&sourceid=chrome-mobile&ie=UTF-8#vhid=Ebch1GUbs_LniM&vssid=_Alw1Z_HTDKOY0PEPuY3LmA0_19'; 
            // Replace with a URL or path to the image
            img.alt = 'White Wolf';
            img.id = 'wolf-image';
            
            imageContainer.appendChild(img);
        }

        // Call the function to show the image
        showWhiteWolf();
    </script>
</body>
</html>

<!---
yason969/yason969 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
