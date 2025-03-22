# usingofifelseconditions

echo "Enter message: " <br>
read message <br>
echo "Enter 1 to send message to all: " <br>
echo "Enter 2 to send message to individual: " <br>
echo "Enter 3 to send message to group: " <br>
read num <br>
if [ $num -eq 1 ] <br>
then <br>
  echo "The message $message is sent to all." <br>
elif [ $num -eq 2 ] <br>
  then <br>
    echo "Enter name: " <br>
    read name <br>
    echo $message $name. <br>
elif [ $num -eq 3 ] <br>
then <br>
  for var in himakar murali jesus god <br>
  do <br>
   echo $message $var. <br>
  done <br>
fi <br>
# Use this 'fi' to end the if condition blocks.
