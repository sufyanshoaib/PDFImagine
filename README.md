PDFImagine is a PDF to Image (any image) conversion tool written in NodeJS for speed, utilizing Ghostscript for conversion of PDF. This is a Lambda function, that works with S3 bucket public folders pdfs/ and images/ to extract and convert into images. Ghostscript is hosted in an AWS Layer as a compliment to the Lambda function.