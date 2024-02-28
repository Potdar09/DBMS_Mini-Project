# DBMS_Mini-Project
Database Management System Mini Projects using MySQL.The project uses a relational database design approach with an ER diagram and a relational schema diagram.

## Title - Pharmacy Management System

This project is a Pharmacy Management System developed using MySQL for the Back-end. It can be used in any pharmaceutical shops having a database to maintain. The software used can generate reports, as per the user’s requirements, print invoices, bills, receipts, and maintain the record of supplies sent in by the supplier. The admin who are handling the organization will be responsible to manage the record of the employee.

### Purpose
1. To make it Easy for the Pharmacy to Manage and keep a record of Medicines
2. To automate the work of Pharmacy Employees and Save their Efforts and Time
3. To gain practical experience by modeling a software based on real world problem.
4. To develop an application that deals with the day to day requirement of any pharmacy.
5. To develop the easy management of the medicines.
6. To provide details information about the stock on details necessary and help locate it in shop easily.


### Installing MySQL-
On Ubuntu 20.04, you can install MySQL using the APT package repository. At the time of this writing, the version of MySQL available in the default Ubuntu repository is version 8.0.27.

To install it, update the package index on your server if you’ve not done so recently:
```
$ sudo apt update
```
Then install the mysql-server package:
```
$ sudo apt install mysql-server
```
Ensure that the server is running using the systemctl start command:
```
$ sudo systemctl start mysql.service
```
These commands will install and start MySQL, but will not prompt you to set a password or make any other configuration changes. Because this leaves your installation of MySQL insecure, we will address this next.

## ENTITY RELATIONS DIAGRAM
![Network Diagrams](https://github.com/Potdar09/DBMS_Mini-Project/assets/149302716/2858f43b-0c69-4d72-b163-6a8cb8181fb9)


## SCHEMA DIAGRAM
![drawSQL-pharmacy-export-2024-02-14](https://github.com/Potdar09/DBMS_Mini-Project/assets/149302716/329395ad-638c-40c0-8feb-629aa9022ab9)



## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```


## HARDWARE USED

1. HARDWARE MODEL- Dell Inc. OptiPlex 5070
2. PROCESSOR- Intel® Core™ i7-9700 CPU @ 3.00GHz × 8
3. GRAPHICS- NV106 / Mesa Intel® UHD Graphics 630 (CFL GT2)
4. OS MODEL- Ubuntu 22.04.3 LTS


## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.



## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
