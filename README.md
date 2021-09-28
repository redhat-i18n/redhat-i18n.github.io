# Red Hat i18n Team projects
This micro-site showcases some of the upstream projects
the Red Hat i18n Engineering team is involved in.

## Testing content
1. fork
2. enable github action
3. setup Pages to source gh-pages branch
4. edit data.json content and push
5. wait for github action to complete
6. open https://youruser.github.io/redhat-i18n.github.io to view


## Building manually
```
$ pip3 install -r requirements.txt
$ python3 app.py
```

### dir layout
- `/template/content.html`: main page
- `/template/static/`: consist of all css, js, images, font files used in website
- `/public/`: the published dir created by app.py with all the static html site files.
- `data.json`: data/content for your website
