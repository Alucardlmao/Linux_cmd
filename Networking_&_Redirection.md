ifconfig - Display network interface information

ping - Send ICMP echo requests to a host

netstat - Display network connections and statistics {netstat -tuln = shows all listening TCP and UDP connections}

ss - Display network socket information {ss -tuln = shows all listening TCP and UDP connections}

ssh - Securely connect to a remote server

scp - Securely copy files between hosts

wget - Download files from the web

curl - Transfer data to or from a server

IO Redirection Commands

cmd < file - Input of cmd is taken from file

cmd > file - Standard output (stdout) of cmd is redirected to file

cmd 2> file - Error output (stderr) of cmd is redirected to file

cmd 2>&1 - stderr is redirected to the same place as stdout

cmd1 <(cmd2) - Output of cmd2 is used as the input file for cmd1

cmd > /dev/null - Discards the stdout of cmd by sending it to the null device

cmd &> file - Every output of cmd is redirected to file

cmd 1>&2 - stdout is redirected to the same place as stderr

cmd >> file - Appends the stdout of cmd to file
