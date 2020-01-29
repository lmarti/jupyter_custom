# jupyter_custom

Jupyter notebooks customization shared by -most of- my notebooks.

## Notebook header with Inria logo

```html
<div align='left' style="width:38%;overflow:hidden;">
<a href='http://inria.fr'>
<img src='https://github.com/lmarti/jupyter_custom/raw/master/imgs/inr_logo_rouge.png' alt='Inria logo' title='Inria'/>
</a>
</div>
```

**Note:** Inria logo taken from https://www.inria.fr/en/charter-use-visual-identity-inria

## Including modifications to change fonts

```python
# this code is here for cosmetic reasons
from IPython.core.display import HTML
from urllib.request import urlopen
HTML(urlopen('https://raw.githubusercontent.com/lmarti/jupyter_custom/master/custom.include').read().decode('utf-8'))
```
