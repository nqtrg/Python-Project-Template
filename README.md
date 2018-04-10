# My Python project's template

### modd.conf
Execute automatically declared tasks whenever code change like running test or less css.

[About modd](https://github.com/cortesi/modd)

Sample *modd.conf* file content:
>*.py{
>    daemon +sigterm: PYTHONPATH=src python app.py
>}
>
>*.less{
>	daemon +sigterm: lessc src/pricetracker/static/style.less src/pricetracker/static/style.css
>}


### requirements.txt
List required python packages
Install:
```bash
pip install -r requirements.txt
```

### .sandbox
Contain #irl, ad-hoc code