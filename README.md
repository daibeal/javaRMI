# javaRMI
Basic Distributed Chat using Java RMI.

## Installation

gh repo clone https://github.com/daibeal/javaRMI

```bash
https://github.com/daibeal/javaRMI.git
```

## Usage

```bash
# At same directory as .class files fromm DistributedChat

rmiregistry 9000 # 9000 -> No of port (You may change it if its already in use)
			    	# Default value (port -> 1099)

java ChatServer nsport=9000 myport=9001

java ChatServer 

java ChatClient nsport=9000 myport=9002

java ChatClient nshost=192.168.1.1 nsport=9000 myport=9002

```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)