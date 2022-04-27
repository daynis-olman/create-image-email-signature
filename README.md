# Create image email signatures
Simple PHP APP that generates downloadable JPEG email signatures (images) 
with personal data from HTML Webform submission

# How it works:

- Step 1: User completes HTML webform located (Name, Email, Department, Phone number)
- Step 2: User clicks "Download Email Signature"
- Step 3: Webform submits form data via POST to generate-signature.php
- Step 4: PHP file will write user submitted data onto a blank image with company logo
- Step 5: Email signature inside .ZIP file will be downloaded

Application does not require build or compile and will work 
on any server with PHP. Application has no dependencies and 
is written in procedural PHP