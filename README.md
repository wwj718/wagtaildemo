#Wagtail demo

fork from [wagtaildemo](https://github.com/torchbox/wagtaildemo)

##安装
*  git clone https://github.com/wwj718/wagtaildemo.git
*  virtualenv django1.6
*  source django1.6/bin/activate
*  cd wagtaildemo
*  sudo apt-get install libpq-dev python-dev
*  sudo apt-get install libxml2-dev libxslt-dev zlib1g-dev
*  pip install -r requirements/dev.txt -i http://pypi.douban.com/simple
*  python manage.py run_gunicorn --workers=2 -b 0.0.0.0:8000
*  64位系统:sudo apt-get install python-dev libjpeg-dev libfreetype6-dev zlib1g-dev

##与原版本的不同之处
*  数据库默认为sqlite3，开箱可用
*  设置语言环境，默认中文
*  使用gunicorn,便于部署

