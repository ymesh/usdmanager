# ymesh_dev branch
- version up to __0.16.0__
- added initial support for PySide6 using qustom Qt.py __1.3.9__
from forked repo https://github.com/ymesh/Qt.py.git@ymesh_dev<br>
```git clone --branch ymesh_dev https://github.com/ymesh/Qt.py.git```
- code formatted using __black__ formatter
- fix for __usdcat__ name for Windows Maya USD (__usdcat.cmd__)
- fix return values in __selectFont__ dialog (was opposite)
- fix __images_rc.py__ for Python 3
- __parsers/usd.py__:<br>use check ```if utils.isUsdCrate(path):``` instead of<br>
```if f.readline().startswith("PXR-USDC"):```
            