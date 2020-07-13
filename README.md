Receives image uploaded by user, then uses celery task queue backed by redis
to create a thumbnail, zips together with the original image and provide a 
download of the result zip file.