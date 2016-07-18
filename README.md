# Portscanner

### Installation
Clone the project in a local folder

Run the program all required gems
```python
python3 main.py -H "ADDRESS" -p "PORTS SEPERATED BY COMMA"
```

Maybe you need to install nmap

Visit [https://nmap.org/book/install.html](https://nmap.org/book/install.html)

###Example
```python
python3 main.py -H 127.0.0.1 -p 21,80
```

Output:
```python
 [*] 127.0.0.1 tcp/21 closed
 [*] 127.0.0.1 tcp/80 open
```
