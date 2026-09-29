# Calotrak

A small calorie tracker that runs in the browser on your own machine. Nothing is sent anywhere. The log stays in this browser.

## What it does

- Record the name of the person the log is for.
- Add foods with a calorie count.
- Show how many calories are left today against a daily goal (2,000 by default).
- Turn the total red and say “over today” when the goal is passed.
- Remove an entry from today’s log.
- Start a fresh log each new day. Older days stay saved in the browser.

## Run it

Open `index.html` in a browser, or from this folder run:

```bash
python -m http.server 8765
```

Then visit [http://127.0.0.1:8765/](http://127.0.0.1:8765/).
