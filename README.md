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
