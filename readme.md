# How to run?

I provided two ways to run it: Web and Python.

## Use Web

### Step1

Start:

```
python app.py
```

Then visit http://localhost:7860/

### Step2

First, enter your question. 

e.g.

①You scored 95 points in the test. Your classmates come to ask you about your score, how will you answer?

②You are late for work because party until very late last night, but you don't want to lose your job. What would you tell your boss instead?



Second, enter your Positive Personas.

e.g.

①"honest"

②"humorous and calm"



Third, enter your Negative Personas.

e.g.

①"untruthful"

②"angry and serious"



Forth, choose the Control Level.

The closer to the left (-2), the more negative; the closer to the right (+2), the more positive.

### Step3

Click "Submit".

## Use Python

Directly run pipeline.py

```python
python pipeline.py --question "You are late for work because you partied until very late last night, but you don't want to lose your job. What would you tell your boss instead?" --positive_personas humorous calm --negative_personas angry serious --level 2

```

Alternatively, modify the default parameters in the file directly and run it.

# Example

![img](D:/typora%E5%9B%BE%E7%89%87/41dfb6a9f6beb0d6b8d1ae4368ea484c.png)

![img](D:/typora%E5%9B%BE%E7%89%87/8e67e681554de886335752c086a57954.png)

![img](D:/typora%E5%9B%BE%E7%89%87/d2368c2c6881adb6c88cfbf53ed08e6b.png)