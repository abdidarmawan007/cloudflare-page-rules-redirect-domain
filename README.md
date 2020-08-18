## Redirect domain example.id to example.com with cloudflare page rules


- This page rule will redirect as per the following examples:
```
example.id > https://www.example.com
www.example.id > https://www.example.com
example.id/page > https://www.example.com/page
www.example.id/page > https://www.example.com/page
```
### create page rule for redirect from domain .id to .com
![alt text](https://i.imgur.com/x6kaTkG.png)
### you need create dummy A Record @ and www in cloudlfare example.id
![alt text](https://i.imgur.com/p9eLnU8.png)
