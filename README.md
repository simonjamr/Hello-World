# Hello-World
<p>This is the first line of code in GIT HUB</p>
#this is some Python

import urllib2

response = urllib2.urlopen('http://www.gutenberg.org/files/2600/2600-h/2600-h.htm')
html = response.read()

love = 0

list_of_words = html.split(' ')

for word in list_of_words:
	if word == 'love':
		love += 1

print love
