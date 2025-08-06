# Flask To Do tutorial web app

## Table of Contents

1. [Info](#info)
2. [Motivation](#motivation)
3. [What I Learned](#what-i-have-learned)
4. [How to Run](#how-to-run)

## Info

- Student: Barbu Alexandru Daniel
- [Source](https://www.youtube.com/watch?v=45P3xQPaYxc&t=55s)
- [Source Youtube channel](https://www.youtube.com/@codewithjoshoffical)

## Motivation

I have used `Flask` and `python` in the past but never actually spent the time to figure things out and learn to do something alone without someone or something helping me.

So it is time to change this.

## What I Have Learned

- Use **Flask** to communicate with `.html` files
- **Develop** and **use** a **database model**
- **Add, Update and delete entries** in said database
- **scss**: a much better version of css
- Correctly use **jinja templates**
- Understad **routes** and where they matter
- Different elements of `HTML` nature **(form, input, table, tr, th, td)**

## How to Run
```bash
# Step 1.1 - venv
python -m venv env              # this creates a virtual environment called `env`
```
```bash
# Step 1.2 - activate venv
source env/bin/activate         # activate the virtual environment named `env`
```
```bash
# Step 2 - dependencies
pip install -r requirements.txt # install the dependencies from the `requirements.txt` file
```
```bash
# Step 3 - run the web app
python3 app.py                  # this command runs the web app
```

> [!WARNING]
> I advise running the code on linux or linux like operating system. I developed this web app using `wsl` and tested therefore only on linux.


> [!CAUTION]
> This is a development version, meaning that debug info is somewhere present when running the app.
> To prepare it for production app.py must be change accordingly!