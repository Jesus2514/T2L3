head -n10 user.txt

tail -n5 user.txt

tail -n +11 user.txt

tail -n+11 user.txt | head -n10

cut -b1 user.txt

cut -b1,3,5 user.txt

cat user.txt |sed 's/:/ /'|  awk '{print $1}' | grep -v ^#

cat user.txt |sed 's/:/ /'|  cut -d: -f1 | grep -v ^[#,_]

cat user.txt |sed 's/:/ /'| grep -v ^[#,_] | cut -d: -f3 

cat -n user.txt | sort -rn

cat user.txt | grep -v ^# | sort -t: -k3 -n 


cat user.txt |sed 's/:/ /'| grep -v ^#|  cut -d: -f4 | sort -n 

cat user.txt  | grep -v ^#| cut -d: -f2,3 | sed 's/:/-/'

cat user.txt  | grep -v ^#| cut -d: -f1,6 | sed 's/:/#/'





