# piston_bot

A Python bot that will run code for you.

## Example

- Input:

```python
/run py
print('bruh')
for i in range(10):
    print(i)
```

- Response:

**Code:**

```console
print('bruh')
for i in range(10):
    print(i)
```

**Output:**

```console
bruh
0
1
2
3
4
5
6
7
8
9
```

## Deploy your own

You'll need [go](https://golang.org) installed.

- Create a telegram bot, and copy its token.
- Run the following in your terminal:

  ```bash
  go build ./cmd/bot

  export TOKEN=<the bot token>
  ./bot # this runs the bot
  ```