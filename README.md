```pyhton
from bot import TemplateBot

class SiteParser(TemplateBot):
    def get_data(url: str) -> None:
        ...

if __name__ == "__main__":
    with SiteParser(show = True) as parser:
        parser.get_data("https://site.com")
```
