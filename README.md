# Microblog Application 

![ScreenShot](https://cloud.githubusercontent.com/assets/5566004/19917669/4181c2d8-a0eb-11e6-8c3e-84dabb7309fc.png)

### Usage

Download the zip and extract it. 

The database is initialised as follows: (within the python prompt)

```
>>> from flaskmb import init_db
>>> init_db()
```

Alternately, you could use: 
```
sqlite3 /tmp/flaskmb.db < schema.sql
```

Now, to get the application running, use:
```
python flaskmb.py
```

Open the link shown on the terminal (127.0.0.1:5000) to view. 

Use the username and password specified in the flaskmb.db file to login.
