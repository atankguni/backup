## About

A simple example of zipping command on Python.

## Requirement

- Python v3 or greater.

## Usage

- Set your **source** and **target_dir** directory on the `backup.py`

- Run the command:
```
$ python3 backup.py
```

- Enter a comment. But you may ignore it.
```
Enter a comment: testing backup
```

- The process will be shown as like this:
```
Successfully created directory /Users/laluharyadiguni/Documents/20200810
Zip command is:
zip -r /Users/laluharyadiguni/Documents/20200810/113000_testing_backup.zip /Users/laluharyadiguni/Documents/notes
Running:
  adding: Users/laluharyadiguni/Documents/notes/ (stored 0%)
  adding: Users/laluharyadiguni/Documents/notes/b.txt (stored 0%)
  adding: Users/laluharyadiguni/Documents/notes/a.txt (stored 0%)
Successful backup to /Users/laluharyadiguni/Documents/20200810/113000_testing_backup.zip
```
