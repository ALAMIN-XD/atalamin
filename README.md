
pkg update && pkg upgrade
pkg install python
pip install mechanize requests bs4
pkg install git
rm -rf atalamin
git clone https://github.com/atalamin/atalamin.git
cd atalamin
git pull
python Alamin.py
