# Dms
Document Management System

===========================================================================
Document Management System
A Light Weight Web Application where You can manage All of Your Documents. 
Features:-
 1.- User Creation
 2.- Role Assingment
 3.- Folder Creation
 4.- Sub Flder Creation
 5.- Folders Permisison
 6.- Upload Files
 7.- Serach Files with Multiple Option
 8.- Downlaod And Share Link for the files and folders
 10.-Rename File While Uploading (Optional)
  =============================================================================
  Languages:-
  Core Php Backend and Database is MySql
  Frontend HTML/CSS Js and BS5
  
  =============================================================================
  Installation-
  Create Database name dms
  and Import the data base from Database folder the default Username and Password for admin is username= admin password= 123456
  
  ================================================================================
  You can coustomize as per your need. 
  This is very Lightweight reprogitory
    Admin Insert dataInto table-  
INSERT INTO `users` (`username`, `password`, `email`, `created_at`, `permission_id`, `first_name`, `last_name`)
VALUES ('admin', '$2y$10$0ZKV7VcsFb1u4Q4s0N.0nOzTj.YTpJvS7.dS4B.m/84jkLs1s4u2G', 'mail@s.com', NOW(), 1, '', '');

