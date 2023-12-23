# mini blog special thanks

https://www.youtube.com/watch?v=Z1RJmh_OqeA&t=27s

VSCODE
CTRL+ò to open terminal

$ python --version

This repo has been updated to work with `Python v3.8` and  Python 3.11.4.

## How To Run
1. Install `virtualenv`:
```
$ python -m venv venv
```

2. Open a terminal in the project root directory and run:
```
$ venv\Scripts\activate
```

3. Then run the command:
```
$ (venv) python -m pip install --upgrade pip
```

4. Then install the dependencies:
```
$ (venv) pip install -r requirements.txt
```

5. Finally start the web server:
```
$ (env) flask run
```

This server will start on port 5000 by default. You can change this in `app.py` by changing the following line to this:

```python
if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
```

## Contributing

Since this is a repository for a tutorial, the code should remain the same as the code that was shown in the tutorial. Any pull requests that don't address security flaws or fixes for language updates will be automatically closed. Style changes, adding libraries, etc are not valid changes for submitting a pull request.