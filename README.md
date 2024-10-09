# Installation and usage
* clone the repo
  * git clone https://github.com/esix2/mailExport-RR.git
  * cd mailExport-RR
* Download the lva archive files from RR webpage
* Decript the file mail_list.csv.gpg, if it exists (you the need the passphrase)
  * gpg --decrypt mail_list.csv.gpg > mail_list.csv
* Run the following command
  * ./read-and-combine
* Encrypt the file mail_list.csv, before commiting to the
  * gpg --symmetric --cipher-algo AES256 mail_list.csv
