# Installation and usage

* clone the repo
    * git clone https://github.com/esix2/mailExport-RR.git
    * cd mailExport-RR
* Download the lva archive files from RR webpage (from 2019 and 2023 are already included in the mail_list.gpg)
    * The name of the archive files is not important. Only the file extion, i.e., **.lva**

* Run the following command (you the need the passphrase. The passphrase can be acquired from the SharePoint)
    * ./read-and-combine
* The list gets updated and again encypted. 
    * For data privacy reasons, files with **.lva** and **.csv** extensions cannot be sommited to git (they are in **.gitignore**)
    * Do not publish them. Delete after usage.
