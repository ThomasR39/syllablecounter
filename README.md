### Setup & Starting
- After installing python3, open up a terminal window
- Change directory to the folder you want this project to be enclosed within
- Then run `$ git clone https://github.com/thomasr39/syllablecount.git`
- Next run `$ cd syllablecount.git`
- The project is viewable and editable from this directory
- To run program enter `$ python3 syllable.py` into the terminal

---

### Testing
To test a list of files, you should use unix style piping,
```bash
$ cat words.txt | python3 Syllable.py
```
otherwise, running `$ python3 syllable.py` will open a prompt to read user input,
you should type each word seperated by a new line. Note that if you don't press
enter after the last word, the program won't know you finished the last word!

To run our doctests which are within syllable.py use,
```bash
$ python3 syllable.py -t -v 
```

Our test cases were chosen by using randomly generated words of different
syllable lengths.

---

### Authors
- Josh M
- Thomas H
- Thomas P
- Thomas R

10/01/2020
