# tobin
hello world

AIM
Shell scripting:For,while
For
echo "sum of n numbers"
read n
sum=0
for i in $(seq 1 $n)
do
sum=$(( $sum + $i))
done


,////////////////////////
"sum of $n number is $sum" While
echo "sum of n numbers using while loop"
read n
i=1
sum=0
while [ $i -le $n ]
do
sum=$(( $sum + $i))
i=$(( $i + 1))
done
echo "sum of $n number is $sum"


////////
if [ $num1 -gt $num2 ] && [ $num1 -gt $num3 ]
then
echo "greatest number is:" $num1
elif [ $num2 -gt $num1 ] && [ $num2 -gt $num3 ]
then
echo "greatest number is:" $num2
else
echo "greatest number is:" $num3
fi

8.WRITE A SHELL PROGRAM TO FIND GREATEST OF THREE 
NUMBERS
echo “ Enter the first number”
read a
echo “ Enter the second number”
read b
echo “ Enter the third number”
read c
if [ $a -gt $b -a $a -gt $c ];then
echo “$a is largest”
elif [ $b -gt $a -a $b -gt $c ];then
echo “$b is largest”
else
echo “$c is largest”
fi

7.WRITE A SHELL PROGRAM TO FIND ALL EVEN NUMBERS 
BETWEEN 1 AND 10
echo Enter the limit number
read a
echo even numbers 
for((i=1;i<=a;i++))
do
r=$(( $i % 2 ))
if [ $r == 0 ];then
echo $i 
fi
done

6. WRITE A SHELL PROGRAM TO PRINT NAME
#!/bin/bash
echo "Enter name "
read name
echo "name is: $name"

5. WRITE A SHELL PROGRAM TO FIND SUM OF N NUMBERS USING 
FOR LOOP
echo "Enter Size(N)"
read N
sum=0
echo "Enter Numbers"
for((i=1;i<=N;i++))
do
 read num 
 sum=$((sum + num)) 
done
echo "sum="$sum

#!/bin/bash
echo "Enter the first number : "
read num1
echo "Enter the second number : "
read num2
sum=$((num1 + num2))
echo "sum of two value is $sum"

3.WRITE A SHELL PROGRAM TO CHECK WHETHER A GIVEN 
NUMBER IS EVEN OR ODD
echo "Enter a Number:"
read n
 rem=$(( $n % 2 ))
 if [ $rem -eq 0 ]
then
 echo "Number is even"
else
 echo "Number is odd"
fi

2. WRITE A SHELL PROGRAM TO FIND AREA OF A CIRCLE
echo "Enter the radious of the circle"
read r
area=$(echo "3.14*$r*$r" | bc )
echo "area of the circle is " $area

1. WRITE A SHELL PROGRAM TO FIND THE SUM OF N NUMBERS 
USING WHILE LOOP
echo "Enter Size(N)"
read N
i=1
sum=0
echo "Enter Numbers"
while [ $i -le $N ]
do
 read num #get number
 sum=$((sum + num)) #sum+=num
 i=$((i + 1))
done
echo "sum is" $sum

scp /home/cev/Desktop/ab.txt cev@ip:/home/cev/Desktop
scp -r /home/cev/Desktop/ab cev@ip:/home/cev/Desktop

su
ssh cev@ip
ys
pswd
mkdir
cat


crontab -e
30 13 11 04 04 tar -zvcf /home/cev/Desktop/ex.tar.gz /home/cev/Desktop

commands
tar -czvf tst.tar.gz a.txt
tar -xzvf tst.tar.gz

cut -b 1,2 a.txt
paste a.txt b.txt

chmod 777 a.txt

su
passwrd
chmod student a.txt

git

apt-get-install git

git config --global user.name tobinthankachan1
git config --global user.email tobinthankachan1@gmail.com
git config --list

git clone url


create repositry in github
ls command in cmd
cd repstryname
mkdir abc
cat >file

git status
red colr file

git add file
git status
green color file

git init

git commit -m "des" filename

git push -u origin master
usrname
paswd



