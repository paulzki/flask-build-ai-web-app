## Install

```bash
pip install -r requirements.txt
```

Add your Azure Translator KEY, ENDPOINT and LOCATION to the [.env](.env).

Run the following command to set the Flask runtime to development, which means that the server will automatically reload with every change

```powershell
# Windows
set FLASK_ENV=development
```

```bash
# Linux/macOS
export FLASK_ENV=development
```

## Run the application!

```
flask run
```

Then you should see something like:

```
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
 * Running on http://127.0.0.1:5000 (Press CTRL+C to quit)
```

Press on the [http://127.0.0.1:5000](http://127.0.0.1:5000) to see the web page.
