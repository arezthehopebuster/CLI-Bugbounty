CLI Bug Bounty

#Directori & File Search IP

shodan domain semrush.com | grep -oE "\b([0-9]{1,3}\.){3}[0-9]{1,3}\b" | uniq -u | httpx --silent | dirdar -only-ok -err
