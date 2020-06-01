printf "your IP is : " && ifconfig | grep "127" | cut -d" " -f10
printf "intr information : " && ifconfig | grep "flags=73" | cut -d" :" -f1
