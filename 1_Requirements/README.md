# Requirements
## Introduction
In most universities, there are well-equipped libraries with excellent infrastructure facilities having a large collection of books. Compared to public libraries, university libraries have a large collection on science and engineering where readers get scope for gathering vast knowledge on respective fields. Because of the dispersion of knowledge, this collection increases rapidly day by day. Although there are many existing software tools, most of those are not proper user interactive and have some limitations for accessing the books. Besides, most universities in mid-level countries like Bangladesh still are using traditional way to manage their library, which prevents faster searching for a book, and faster report generation. This leads to develop an online digital library management system. A good interactive interface was available and users could obtain a fresh and different feeling. Proper security has been maintained in the proposed system because only authorized users could access this application.

## Research
From ancient times the knowledge is spread by people across the world in written form. First, the information is stored by carving words on copper using the sharp tool; by the time the papers are invented and using the ink and feather of bird the information is started to store on paper, which helped a lot for storing purpose. It's very difficult to store the data stored in books secured and safe; as we know the paper can be torn apart or they got stolen by someone or in worst scenario pages get eaten by bugs. So as we know from old times the libraries are managed manually by a group of people. The methods are really difficult as compare to today’s digitized world, nowadays we can find anything on just one click, but we see at past methods they kept written records for each thing and that record goes on increasing as time pass. If the records got lost then there is no other for retrieving them back, so the loss is permanent. 

## Benefits
Digitization of library helps to keep all the records secured and retrievable which saves the paperwork and made library records easy to store.



## Defining Our System

### Explanation
* Library Management System have few inbuilt features like:
    * Add book
    * Delete book
    * Search a book
    * View Book
    * Update Password


## SWOT ANALYSIS
![SWOT Analysis](https://github.com/Diptiman1999/LTTS_MiniProject_C/blob/master/1_Requirements/swot.png)

# 4W&#39;s and 1&#39;H

## Who:
Schools, Colleges and Universities have started using this library management system.
## What:
Able to manage books efficiently and effectively.
## When:
Earlier library managers used to store books informations in registers. But with new technology it will save time aswell as efforts.
## Where:
This system is used all over the world.
## How:
This system will help to store books information effectively search,delete them efficiently.


# Detail requirements
## High Level Requirements: 
User here refers to Librarian.

| ID | Description | Category | Status | 
| ----- | ----- | ------- | ---------|
| HR01 | User shall be able to login to system | Techincal | Implemented |
| HR02 | User shall be able to add new book | Techincal | Implemented | 
| HR03 | User shall be able to display books | Techincal | Implemented |
| HR04 | User shall be able to delete book | Techincal | Implemented |
| HR05 | User shall be able to search book | Techincal | Implemented |
| HR06 | User shall be able to update credentials | Techincal | Implemented |
| HR07 | Data should not be lost in case of failure | Scenario | FUTURE |
| HR08 | Data should always be stored when closing the system | Technical | Implemented |


##  Low level Requirements:
| ID | Description | HLR ID | Status (Implemented/Future) |
| ------ | --------- | ------ | ----- |
| LR01 | User shall only be able to login to system by providing username and password | HR01 | Implemented |
| LR02 | If login is successfull then the file where data will be stored should be checked for existence, if YES then it will append to file otherwise it will create a new file | HR01 | Implemented |
| LR03 | User shall be able to add book by providing details like id,name of the book, author's name and date when added | HR02 | Implemented |
| LR04 | User shall be able display all book details like id,name,author and date added | HR03 | Implemented |
| LR05 | User need to search by id for the book to be deleted, if no such book name is available then "Book doen't exist" Message should be displayed | HR04 | Implemented |
| LR06 | User need to search by name for book details, if no such book is available then "Book doen't exist" Message should be displayed | HR05 | Implemented |
| LR07 | User need to provide new username and password to update the credentials  | HR06 | Implemented |
| LR08 | User shall be able to save book details to the files, if file already exists then it should append to file and should not overwrite it and if file does not exists then it should create a new file | HR02, HR03, HR04, HR05,HR06 | Implemented |
| LR09 | If opening the file fails, then the system shloud prompt the message "File not exist" and should not end the program execution | HR02, HR03, HR04, HR05,HR06 | Implemented |
| LR010 | When user exit the system, file should be automatically saved and "Thank You" message should be displayed | HR08 | Implemented |


