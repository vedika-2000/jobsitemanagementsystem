# jobsitemanagementsystem

## Team members
* Neha Khairnar- nehak2209pc@gmail.com
* Prerna Shelke - prernashelke01@gmail.com
* Vedika mamidwar - vkmamidwar_b19@it.vjti.ac.in
* Shalini Gosavi - 
* Shivani Rashinkar - 


## Table of Contents
* [Getting Started](#Getting Started)
  * [Prerequisites](#Prerequisites)
  * [Setup](#Setup)
* [About the Project](#about-the-project)
  * [Description](#Description)
  * [Tech Stack](#tech-stack)
  * [File Structure](#file-structure)
* [Features](#Features)
* [Screenshots](#Screenshots)

## Getting Started
We made this project entirly in "Localhost" using Apache or HTTP Server. Kindly follow the below mentioned instructions to run it on your machine.

## Prerequisites
You need only XAMPP to run this project on your local machine. XAMPP is a completely free, easy to install Apache distribution containing MariaDB, PHP, and Perl.

## Setup
Git Clone the Repo or download the Project Zip file.

Extract the files in the htdocs directory where you installed XAMPP. Lets assume you installed XAMPP in C drive. Then your path to htdocs will be,

C:/xampp/htdocs/
Start the Apache & MySQL(or MariaDB) module in XAMPP Control Panel.

Go to phpmyadmin from your browser & import the database which is provided as a SQL file in the Project zip under Database folder.


## About The Project
Nowadays in our society, the issue of managing human resources in firms, companies or organizations is a great challenge to management. The job market is so extensive that a variety of
industries and companies are searching for right candidates and the candidates are searching for right companies for growth opportunities. Due to COVID-19 pandemic most people lost their jobs. So it is
important for the job seekers to be able to find jobs which have good recruitment policies and which are suitable for the job seeker.

## Description  
Purpose of this project aimed at developing a jobsite management system  that manages the recruitment processes of organizations and reduces the cost used in the recruitment of staff. This platform will enable the job seeker to get access to companies or firms with requirement policies
expected by the job seeker and will also help companies to find the suitable candidate for the job.


## Code Snippets
<hr>

##### Home.php

``` <section id="banner">
   
  <!-- Slider -->
        <div id="main-slider" class="flexslider">
            <ul class="slides">
              <li>
                <img src="<?php echo web_root; ?>plugins/home-plugins/img/slides/5.jpg" alt="" />
                <div class="flex-caption">
                    <h3>innovation</h3> 
          <p>We create the opportunities</p> 
           
                </div>
              </li>
              <li>
                <img src="<?php echo web_root; ?>plugins/home-plugins/img/slides/2.jpg" alt="" />
                <div class="flex-caption">
                    <h3>Specialize</h3> 
          <p>Success depends on work</p> 
           
                </div>
              </li>
            </ul>
        </div>
  <!-- end slider -->
```
##### Login.php 
```     <!-- Modal -->
          <div class="modal fade" id="myModal" tabindex="-1">
            <div class="modal-dialog">
              <div class="modal-content">
                <div class="modal-header">
                  <button class="close" data-dismiss="modal" type=
                  "button">×</button>

                  <h4 class="modal-title" id="myModalLabel">Login</h4>
                </div>

                <!-- <form action="process.php?action=login" enctype="multipart/form-data" method="post"> -->
                  <div class="modal-body hold-transition login-page">
                    <div id="loginerrormessage"></div>
                    <div class="login-box"> 
                        <div class="login-box-body" style="border: solid 1px #ddd;padding: 35px;min-height: 350px;"> 

                          <form action="" method="post">
                            <div class="form-group has-feedback">
                              <input type="text" class="form-control" placeholder="Username" name="user_email" id="user_email">
                              <span class="fa fa-user form-control-feedback" style="margin-top: -22px;"></span>
                            </div>
                            <div class="form-group has-feedback">
                              <input type="password" class="form-control" placeholder="Password" name="user_pass" id="user_pass">
                              <span class="fa fa-lock form-control-feedback" style="margin-top: -22px;"></span>
                            </div>
                            <div class="row">
                              <div class="col-xs-8">
                                <div class="checkbox icheck">
                                  <label>
                                    <input type="checkbox"> Remember Me
                                  </label>
                                </div>
                              </div>
                              <!-- /.col -->
                              <div class="col-xs-4">
                                
                              </div>
                              <!-- /.col -->
                            </div>
                          </form> 
                          
                          <a href="#">I forgot my password</a><br>
                          <a href="<?php echo web_root; ?>index.php?q=register" class="text-center">Register a new membership</a>

                        </div>
                        <!-- /.login-box-body -->
                      </div>
                  </div>

                  <div class="modal-footer">
                    <button class="btn btn-default" data-dismiss="modal">Close</button> <button class="btn btn-primary"
                    name="btnlogin" id="btnlogin"  >Login</button>
                  </div>
                <!-- </form> -->
              </div><!-- /.modal-content -->
            </div><!-- /.modal-dialog -->
          </div><!-- /.modal -->
```
##### Table structure for table `tblapplicants`
```CREATE TABLE `tblapplicants` (
  `APPLICANTID` int(11) NOT NULL,
  `FNAME` varchar(90) NOT NULL,
  `LNAME` varchar(90) NOT NULL,
  `MNAME` varchar(90) NOT NULL,
  `ADDRESS` varchar(255) NOT NULL,
  `SEX` varchar(11) NOT NULL,
  `CIVILSTATUS` varchar(30) NOT NULL,
  `BIRTHDATE` date NOT NULL,
  `BIRTHPLACE` varchar(255) NOT NULL,
  `AGE` int(2) NOT NULL,
  `USERNAME` varchar(90) NOT NULL,
  `PASS` varchar(90) NOT NULL,
  `EMAILADDRESS` varchar(90) NOT NULL,
  `CONTACTNO` varchar(90) NOT NULL,
  `DEGREE` text NOT NULL,
  `APPLICANTPHOTO` varchar(255) NOT NULL,
  `NATIONALID` varchar(255) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
```


* GitHub repo link: [Link to repository](https://github.com/vedika-2000/jobsitemanagementsystem)

### Tech Stack
* PHP
* HTML
* CSS
* JavaScript
* Bootstrap
* JQuery
* MySQL (DataBase)

### File Structure
```
.

```

## Features
<!-- >How can your project do its part in solving a real-life problem? What are its possible applications? Describe here.-->
The Project provides many standardized features of a Job Portal. Below are some of the Key features.
* Complete & seperate Register, Login & Working Panel for Jobseekers and Employers.
* Search Jobs without Registering.
* Detailed Profiles for both Jobseeker & Employer.
* One click Job Apply for Jobseekers.
* Track & View your Job Applications as a Jobseeker.
* Post multiple Jobs & Track them as Employer.
* View, Select or Reject Job Applications as Employer.
* Notification Mail to the registered Email ID for Job Application, Selection etc.
Many More... 



## Screenshots 
<!--
!<img src="https://github.com/vedika-2000/jobsitemanagementsystem/blob/master/Screenshot%20(580).png" height=450/> 

-->

<img src="https://github.com/vedika-2000/jobsitemanagementsystem/blob/master/Screenshot%20(582).png" height=450/>

<img src="https://github.com/vedika-2000/jobsitemanagementsystem/blob/master/Screenshot%20(583).png" height=450/>

<img src="https://github.com/vedika-2000/jobsitemanagementsystem/blob/master/Screenshot%20(584).png" height=450/>

<img src="https://github.com/vedika-2000/jobsitemanagementsystem/blob/master/Screenshot%20(585).png" height=450/>

<img src="https://github.com/vedika-2000/jobsitemanagementsystem/blob/master/Screenshot%20(586).png" height=450/>

<img src="https://github.com/vedika-2000/jobsitemanagementsystem/blob/master/Screenshot%20(587).png" height=450/>

<img src="https://github.com/vedika-2000/jobsitemanagementsystem/blob/master/Screenshot%20(588).png" height=450/>

<img src="https://github.com/vedika-2000/jobsitemanagementsystem/blob/master/Screenshot%20(589).png" height=450/>

<img src="https://github.com/vedika-2000/jobsitemanagementsystem/blob/master/Screenshot%20(590).png" height=450/>
