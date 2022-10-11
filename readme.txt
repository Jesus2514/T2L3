head -10 user.txt

tail -5 user.txt

awk ' ´{print $11 ":" print $121}'

awk ' ´{print $11 ":" print $20}'

cut -b=1

cut -c = 1,3,5

cat user.txt | awk'{print $1}'

sed '1 s/''/ /' user.txt
cut -c = 1,3,5

cat user.txt | grep -v ^[#,_]

sort -r user.txt 

sort -r user.txt