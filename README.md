# NeetCode Python practice — beginner solutions

Harsh Paun's Python learning log, with submissions synced from NeetCode. Start with a small, runnable example of variable assignment and printing.

## Browse the solutions

| Course | Exercise | Code | What it demonstrates |
| --- | --- | --- | --- |
| Python For Beginners | Variable declaration | [Python solution](Python%20For%20Beginners/python-variable-declaration/submission-0.py) | Assign a string to a variable and print it twice |

The repository currently contains one Python exercise. More entries can be added as new submissions are synced; this is not yet a complete interview-preparation collection.

## Run the example

With Python 3 installed:

```sh
git clone https://github.com/techgamewithharsh-dot/neetcode-submissions.git
cd neetcode-submissions
python3 "Python For Beginners/python-variable-declaration/submission-0.py"
```

Expected output:

```text
this string is stored in a variable
this string is stored in a variable
```

`message = ...` stores a string under a name. Both calls to `print(message)` read the same value, so the output repeats. Try changing the string locally to see how assignment affects both lines.

## Structure and sync

Submissions follow `<course>/<exercise>/submission-<number>.py`. The original exercise files are kept separate from these explanations so they can continue to be synced by the NeetCode integration.

Manage the integration through [NeetCode's GitHub settings](https://neetcode.io/profile/github).

## Feedback

Found a confusing explanation or a reproducible issue? [Open an issue](https://github.com/techgamewithharsh-dot/neetcode-submissions/issues) with the exercise path, your Python version, and the expected output.
