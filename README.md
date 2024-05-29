# fast_api_demo

### install the dependencies using:
    pip install -r requirements.txt

### to run the api use command:
    uvicorn main:app --reload

### the output should be something like this:
    INFO:     Will watch for changes in these directories: ['/Users/trav/Documents/projects/codesense/api']
    INFO:     Uvicorn running on http://127.0.0.1:8000 (Press CTRL+C to quit)
    INFO:     Started reloader process [38349] using WatchFiles
    INFO:     Started server process [38351]
    INFO:     Waiting for application startup.
    INFO:     Application startup complete.

### based on the output we can make a curl get request though the following command:
    curl 127.0.0.1:8000 

### we can also make a curl post request as follows:
    curl 127.0.0.1:8000 -X POST

### with fastapi you get autodocumentation which you checkout by going to the local_address/docs:
    http://127.0.0.1:8000/docs