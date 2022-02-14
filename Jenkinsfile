from bs import BeautifulSoup
def response = httpRequest 'https://github.com/uttam-dubey'
        println("Status: "+response.status)
        println("Content: "+response.content)
        soup = BeautifulSoup(response.text, 'html5lib')
        token= soup.find('input', attrs={'name': 'authenticity_token'})['value']
        print(token)
                                       
