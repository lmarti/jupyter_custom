# jupyter_custom
Jupyter notebooks customization shared by -most of- my notebooks.

# Notebook header with UFF and IC logos
```html
<div align='left' style="width:400px;height:120px;overflow:hidden;">
<a href='http://www.uff.br'>
<img align='left' style='display: block;height: 92%' src='https://github.com/lmarti/jupyter_custom/raw/master/imgs/uff.png' alt='UFF logo' title='UFF logo'/>
</a>
<a href='http://www.ic.uff.br'>
<img align='left' style='display: block;height: 100%' src='https://github.com/lmarti/jupyter_custom/raw/master/imgs/logo-ic.png' alt='IC logo' title='IC logo'/>
</a>
</div>
```

# Including modifications to change fonts
```python
# this code is here for cosmetic reasons
from IPython.core.display import HTML
from urllib.request import urlopen
HTML(urlopen('https://raw.githubusercontent.com/lmarti/jupyter_custom/master/custom.include').read().decode('utf-8'))
```
