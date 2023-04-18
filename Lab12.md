## Lab 12

- Name: Isabella Livingston
- Email: livingston.70@wright.edu

## Part 1 Answers:

1. `tar` options:
   - `-c`: Creates a new archive
   - `-v`: Verbosely list files processed
   - `-f`: Tells tar that the next argument is the file name of the archive
   - `-z`: Decompresses the Files
   - `-x`: Extracts the files from the zipped file
2. Command(s): tar -czvf .tar.gz text.txt

## Part 2 Answers:

1. Command: sudo sftp -i labsuser.pem ubuntu@34.228.33.69
2. `sftp` options:
   - `ls`: Display remote directory listing
   - `lls`: Display local directory listing
   - `put`: Upload file
   - `get`: Download file
3. Command(s): get .tar.gz
4. Command(s): !, cd Space, tar -czvf .tar.gz text.txt

## Part 3 Answers:

1. sudo adduser NewUser
2. ssh-keygen -t rsa
3. cd .ssh, put id_rsa authorized_keys
4. sudo sftp -i authorized_keys NewUser@34.228.33.69

## Part 4 Answers

1. Translate to network prefixes + CIDR notation:
   - Sample: `10.0.0.0 - 10.0.1.255` = `10.0.0.0/23` OR `10.0.1.0/23`
   - `130.108.0.0 - 130.108.255.255` = '130.108.0.0/23' OR '10.0.0.255/23'
   - `10.0.0.0 - 10.0.0.255` = '10.0.0.0/23' OR '10.0.1.255/23'
   - `your_public_ip - your_public_ip` = '127.0.0.1/23' OR '127.0.0.1/23'
2. How you confirmed current rules are bad, and why are they bad. Anyone can connect to the AWS Server 
3. Your implementation details: EC2 Dashboard > Instances (running) > *Checked Name of Instance* > Security > Security Groups (link) > Edit inbound rules > Source Type: My IP
4. Something invalid: An invalid IP is anything but my IP

## Extra Credit Answers:

### Solve the conflict

1.
2.
3.
4.
5.
