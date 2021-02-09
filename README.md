# idacapa_plugins
mod capa ida plugin

add support to export json from https://github.com/Dump-GUY/CAPA_JsonConver

Support Python3 only, tested with ida 7.5

Install:
clone capa repository (because the pip is not install the newest)
``` git clone --recursive https://github.com/fireeye/capa.git ```
cd to capa folder and run command 
```
python3 setup.py install
```
clone the plugins repo
```
git clone --recursive https://github.com/computerline1z/idacapa_plugins.git
```
copy capa_explorer.py and idacapa folder to IDADIR/plugins
rules data is in folder idacapa\capa-rules, just clone rules repository https://github.com/fireeye/capa-rules.git (or from capa folder) and copy contents to capa-rules folder
