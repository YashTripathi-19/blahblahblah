# blahblahblah
echo -e "\e[32m"; while :; do printf "\v%$(($COLUMNS/4*3))s" "$(head -c$(($RANDOM%70)) /dev/urandom | tr -dc 'a-zA-Z0-9')"; sleep 0.05; done
