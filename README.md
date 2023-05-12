# usingofifelseconditions

echo "Enter message: "
read message
echo "Enter 1 to send message to all: "
echo "Enter 2 to send message to individual: "
echo "Enter 3 to send message to group: "
read num
if [ $num -eq 1 ]
then
  echo "The message $message is sent to all."
elif [ $num -eq 2 ]
  then
    echo "Enter name: "
    read name
    echo $message $name.
elif [ $num -eq 3 ]
then
  for var in himakar murali jesus god
  do
   echo $message $var.
  done
fi
# Use this 'fi' to end the if condition blocks.
