# Seed - Fastest OSINT Username Searcher

## Disclaimer
```
This or previous program is for Educational purpose ONLY. Do not use it without permission. 
The usual disclaimer applies, especially the fact that me (Object02X) is not liable for any 
damages caused by direct or indirect use of the information or functionality provided by these 
programs. The author or any Internet provider bears NO responsibility for content or misuse 
of these programs or any derivatives thereof. By using these programs you accept the fact 
that any damage (dataloss, system crash, system compromise, etc.) caused by the use of these 
programs is not Object02X's responsibility.
```

## Setup

#### Clone the repository
```shell
git clone https://github.com/Object02X/seed
cd seed
```

#### Install requirements
```shell
pip install -r requirements.txt
```

## Usage

#### Search by username
```python
python seed.py -u username
```
#### Read results file
```python
python seed.py -f username.json
```
#### List supported sites
```python
python seed.py --list-sites
```
#### Use proxy
```python
python seed.py -u crash --proxy http://127.0.0.1:8080
```
#### Show all results
By default only found accounts will be shown, however you can use the argument below to see all of them.
```python
python seed.py -u crash --show-all
```
