## BUILD##

To edit the Handbook:
```
git clone https://github.com/davidbailey/Information_Security_Handbook.git
edit
git commit -a -m 'message'
git push
```

To release a new version of the PDF:
```
git tag "date -u "+%Y-%m-%d_%H.%M.%S""
git push --tags
```

Releases located at:
[https://github.com/davidbailey/Information_Security_Handbook/releases/latest/](https://github.com/davidbailey/Information_Security_Handbook/releases/latest/)
