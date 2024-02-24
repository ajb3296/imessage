# imessage
Python tools for sending iMessage/SMS message from a Mac. Check out the blog post on medium related to this repository: [Medium](https://medium.com/@jameskabbes/sending-imessages-with-python-on-a-mac-b77b7dd6e371)

[Documentation](https://jameskabbes.github.io/imessage) <br>
[PyPI](https://pypi.org/project/pyimessage)

<br>

# Installation
`pip install git+https://github.com/ajb3296/imessage.git`

<br>

# Running main

```
python -m mac_imessage
```

<br>

# Usage

```python
import mac_imessage
```

## Basic Usage
Check out `utils.py` for the most basic functionality<br>
Images must be located in /Users/username/Pictures

```python
mac_imessage.send_image('/Users/username/Pictures/image', '123-555-5555', 'iMessage')
```
```python
mac_imessage.send('This is a test message', '123-555-5555', 'iMessage')
```
```python
mac_imessage.send_SMS('This is a test message', '123-555-5555')
```

```python
mac_imessage.send_iMessage('This is a test message', '123-555-5555')
```

<br>

# Author
James Kabbes
