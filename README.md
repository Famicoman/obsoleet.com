```
cd /var/www
mkdir obsoleet.com
cd obsoleet.com
git clone https://github.com/Famicoman/obsoleet.com.git private
cd private
git submodule update --init --recursive
hugo
mv public ../
```
