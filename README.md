# Monitoring-System-Resources-for-a-Proxy-Server
Instructions for Usage

1.	Add Execute Permissions (if needed):
If the script does not have execute permissions (e.g., -rw-r--r--), you need to add execute permissions:
chmod +x monitor.sh
2.	Run the script with no options to display the full dashboard:
sudo ./monitor.sh
3.	Use specific options to view individual sections:
./monitor.sh -cpu
./monitor.sh -memory
./monitor.sh -network
./monitor.sh -disk
./monitor.sh -process
./monitor.sh -service
4.	View help message:
./monitor.sh -help
