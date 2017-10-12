![Estonian Information System Authority](https://github.com/e-gov/RIHA-Frontend/raw/master/logo/gov-CVI/lions.png "Estonian Information System Authority") ![European Regional Development Fund](https://github.com/e-gov/RIHA-Frontend/raw/master/logo/EU/EU.png "European Regional Development Fund")

# RIHA-help

RIHA help files for UI and API end-users


## Contributing specifics

- Only pages under /docs are included in the final HTML page
- The page is genereated with jekyll to abi.riha.ee once a day
- New pages should be created right under /docs
- New images should be added to /docs/assets/images/data folder
- [Set up the page locally](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/) to test your changes before commiting them to the master branch

### Linking

- After adding a new page, a link has to be added to index.md
- If there are several sections on a page, you can create an internal link to the specific section by using the heading's id after hashtag element in the link
- Use URL-encoded counterpart when the internal link contains any special characters

```
[Kellel minu asutusest on kirjeldaja õigused?](RIHA-oigused-haldamine#kellel-minu-asutusest-on-kirjeldaja-%F5igused
```

### Design specifics

- All CSS files are under /docs/css
- /docs/css/bower_components includes general RIHA-specific CSS files
- RIHA-Help specific design elements should be overriden in resources.css file