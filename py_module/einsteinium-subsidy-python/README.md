install: python setup.py install --record files.txt
uninstall: cat files.txt | xargs rm -rf
