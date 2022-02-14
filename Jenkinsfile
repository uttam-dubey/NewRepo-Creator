import requests
from bs4 import BeautifulSoup

headers = {
 'user-agent': 'Mozilla/5.0 (Macintosh; Intel Mac OS X 10_13_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.86 Safari/537.36'
}

login_data = {
'commit': 'Sign in',
'utf8': '%E2%9C%93',
'login': 'uttam-dubey',
'password': 'Shubh@m12345'
}
url = 'https://github.com/uttam-dubey'
session = requests.Session()
response = session.get(url, headers=headers)

soup = BeautifulSoup(response.text, 'html5lib')
login_data['authenticity_token'] = soup.find(
'input', attrs={'name': 'authenticity_token'})['value']
print(login_data.text)
