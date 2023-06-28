# who is it
This is the write-up for the challenge "who is it" challenge in PicoCTF

# The challenge
Someone just sent you an email claiming to be Google's co-founder Larry Page but you suspect a scam.
Can you help us identify whose mail server the email actually originated from?

![](img/challenge.png)

## Hints
1. whois can be helpful on IP addresses also, not only domain names.

## Initial look
The challenge provided a .eml file
![](img/file_downloaded.png)

I opened the email and started looking at it's data, I searched for a domain / ip address 
![](img/email_with_ip.png)

I searched the web and found a website called whois<br/>
I copied the ip I found and pasted it in the search bar<br/>
![](img/whois_search.png)

I got inforamtion regarding the ip address
![](img/whois_result.png)

The challenge said to search for a name - first and last name, I found a name
![](img/whois_data.png)
I copied the the name and pasted it as flag.
<br/>
The flag is: 'picoCTF{WilhelmZwalina}'

