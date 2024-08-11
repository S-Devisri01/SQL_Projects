              -- Students Data Management System --
              
create database Students_Data_Management_System;

use Students_Data_Management_System;              

CREATE TABLE Student (
    Std_ID INT AUTO_INCREMENT PRIMARY KEY,
    Firstname varchar(100),
    Lastname varchar(100),
    Gender ENUM('Male', 'Female'),
    Age INT,
    Course VARCHAR(50),
    Current_year INT,
    Hostel_ID INT
    );

insert into Student (Std_ID, FirstName, LastName, Gender, Age, Course, Current_year, Hostel_ID) 
values (01,'Viji','Subramani', 'Female', 21, 'IT', 4, 101),
(02,'Sandip','Mondal', 'Male', 20, 'IT', 4, 201),
(03,'Thamayanthi','Jayaprakash', 'Female', 19, 'IT', 4, 101),
(04,'Devisri','Sadhasivam', 'Female', 19, 'IT', 4, 101),
(05,'Deepa','Selvakumar', 'Female', 20, 'AI&DS', 3, 101),
(06,'Jayasri','Seenu', 'Female', 20, 'CSE', 3, 102),
(07,'Dhanush','Ponnusamy', 'Male', 20, 'CSE',3, 202),
(08,'Ravi','Chandran', 'Male', 20, 'IT', 2, 202),
(09,'Dhinakaran','DK', 'Male', 19, 'AIDS', 2, 203),
(10,'Sangameshwaran','Prakash', 'Male', 19, 'AIDS', 4, 203),
(11,'Janarthini','srinivasan', 'Female', 20, 'AIDS', 3, 102),
(12,'Gomathi','Murugan', 'Female', 21, 'IT', 4, 102),
(13,'Aaliya','Hussain', 'Female', 20, 'IT', 3, 101),
(14,'Gogul','Priya', 'Female', 20, 'Agriculture', 3, 102),
(15,'Anitha','Palaniyappan', 'Female', 19, 'Agriculture', 2, 103),
(16,'Gopika','Ravi', 'Female', 19, 'MECH', 2, 103),
(17,'Dharanisri','Raman', 'Female', 19, 'Agriculture', 2, 103),
(18,'Sowmiya','Manikandan', 'Female', 21, 'BioMedical', 4, 104),
(19,'Srimathi','Nagarajan', 'Female', 20, 'BioMedical', 3, 104),
(20,'Rohini','Balan', 'Female', 19, 'BioMedical', 2, 104),
(21,'Sangeetha','Venkadesh', 'Female', 19, 'BioMedical', 2, 105),
(22,'Karthiga','Nagarajan', 'Female', 20, 'BioMedical', 3, 104),
(23,'Sajitha','Govindhasamy', 'Female', 20, 'ECE', 3, 105),
(24,'Udhay','Mariyappan', 'Male', 19, 'MECH', 2, 205),
(25,'Dinesh','Neelakandan', 'Male', 19, 'MECH', 2, 205),
(26,'Sadurdeva','Saravanan', 'Male', 19, 'MECH', 4, 205),
(27,'Sudharsan','Venkateswaran', 'Male', 19, 'MECH', 4, 205),
(28,'Kavinkumar','Duraisamy', 'Male', 19, 'MECH', 4, 205),
(29,'AswinRaj','Karthikeyan', 'Male', 20, 'CSE', 3, 202),
(30,'Moulidharan','Thirumoorthy', 'Male', 20, 'CSE', 3, 206),
(31,'MadhanRaj','Sekar', 'Male', 21, 'CSE', 4, 206),
(32,'Arun','Senthil', 'Male', 19, 'CSE', 2, 206),
(33,'Shalini','Madheshwaran', 'Female', 19, 'BioMedical', 4, 105),
(34,'Akila','Aki', 'Female', 19, 'BioMedical', 4, 105),
(35,'Remo','Jayapriyan', 'Male', 20, 'AIDS', 4, 201);

CREATE TABLE Books (
    Book_ID INT AUTO_INCREMENT PRIMARY KEY,
    Title VARCHAR(255),
    Author VARCHAR(255),
    Publisher VARCHAR(255),
    Year_of_Publish INT,
    Available_Copies INT
);
insert into  Books (Book_ID,Title, Author, Publisher, Year_of_Publish, Available_Copies)
 values(01, 'The Essence of Comedy', 'John Smith', 'Laugh House Press', 2020, 12),
(02, 'Exploring Love', 'Emma Johnson', 'Heartfelt Publications', 2018, 15),
(03, 'Crime Chronicles', 'David Miller', 'Mystery Press', 2017, 10),
(04, 'Thrills and Chills', 'Sophia Brown', 'Edge Publishing', 2021, 8),
(05, 'Life Quotes Collection', 'Michael Davis', 'Inspire Books', 2019, 20),
(06, 'Mind Stress Relief', 'Emily Wilson', 'Calm Press', 2022, 14),
(07, 'The Meaning of Life', 'Liam Taylor', 'Philosophy Press', 2016, 18),
(08, 'Reality Reflections', 'Olivia Martinez', 'Truth House', 2023, 16),
(09, 'Horror Stories', 'Ethan Anderson', 'Nightmare Books', 2015, 9),
(10, 'Adventures Unleashed', 'Ava Thomas', 'Explorer Press', 2020, 11),
(11, 'Fantasy Realms', 'Lucas White', 'Magic Books', 2019, 13),
(12, 'Sci-Fi Futures', 'Mia Harris', 'Tech Press', 2022, 10),
(13, 'Dramatic Turns', 'Noah Martin', 'Stage Press', 2018, 12),
(14, 'Action Packed', 'Isabella Thompson', 'Hero House', 2021, 9),
(15, 'Historical Narratives', 'James Garcia', 'History House', 2017, 8),
(16, 'Mysterious Paths', 'Amelia Robinson', 'Puzzle Press', 2016, 14),
(17, 'Romantic Expressions', 'Benjamin Clark', 'Love Letters Press', 2020, 18),
(18, 'Wisdom for Life', 'Charlotte Lewis', 'Wise Words Publishing', 2023, 22),
(19, 'Motivation for Success', 'Henry Walker', 'Inspire House', 2021, 17),
(20, 'Mindful Moments', 'Grace Allen', 'Awareness Press', 2019, 15),
(21, 'Psychological Thrills', 'Daniel Young', 'Mind Games Press', 2023, 7),
(22, 'Urban Realities', 'Victoria Hall', 'City Lights Press', 2018, 13),
(23, 'The Self-Help Guide', 'Alexander King', 'Better You Books', 2020, 19),
(24, 'Life Lessons Learned', 'Natalie Scott', 'Life Press', 2017, 21),
(25, 'Survival Tales', 'Elijah Green', 'Endurance Publishing', 2022, 9),
(26, 'True Stories of Life', 'Zoe Adams', 'Reality Press', 2016, 14),
(27, 'Dark Comedy Insights', 'William Baker', 'Shadow Laughs Press', 2018, 6),
(28, 'Epic Fantasy Worlds', 'Samantha Wright', 'Heroic Tales Publishing', 2021, 8),
(29, 'Inspirational Journeys', 'Matthew Carter', 'Uplift Books', 2019, 15),
(30, 'Quotes on Reality', 'Evelyn Reed', 'Truthful Press', 2023, 18);

CREATE TABLE Library (
    Issue_ID INT AUTO_INCREMENT PRIMARY KEY,
    Std_ID INT,
    Book_ID INT,
    Issue_Date Date,
    Return_Date DATE,
    FOREIGN KEY (Std_ID) REFERENCES Student(Std_ID),
    FOREIGN KEY (Book_ID) REFERENCES Books(Book_ID)
);
alter table Library modify Issue_ID varchar(100);

desc Library;
SELECT * FROM student WHERE Std_ID = Std_ID;

insert into Library (Issue_ID, Std_ID, Book_ID, Issue_date, Return_date)
values('1A2B',01, 1, '2024-08-01', '2024-08-15'),
('1B2C',02, 2, '2024-08-02', '2024-08-16'),
('1C2D',03, 3, '2024-08-03', '2024-08-17'),
('1D2E',04, 4, '2024-08-04', '2024-08-18'),
('1E2F',05, 5, '2024-08-05', '2024-08-19'),
('1F2G',06, 6, '2024-08-06', '2024-08-20'),
('1G2H',07, 7, '2024-08-07', '2024-08-21'),
('1H2I',08, 8, '2024-08-08', '2024-08-22'),
('1I2J',09, 9, '2024-08-09', '2024-08-23'),
('1J2K',10, 10, '2024-08-10', '2024-08-24'),
('1K2L',11, 11, '2024-08-11', '2024-08-25'),
('1L2M',12, 12, '2024-08-12', '2024-08-26'),
('1M2N',13, 13, '2024-08-13', '2024-08-27'),
('1N2O',14, 14, '2024-08-14', '2024-08-28'),
('1O2P',15, 15, '2024-08-15', '2024-08-29'),
('1P2Q',16, 16, '2024-08-16', '2024-08-30'),
('1Q2R',17, 17, '2024-08-17', '2024-08-31'),
('1R2S',18, 18, '2024-08-18', '2024-09-01'),
('1S2T',19, 19, '2024-08-19', '2024-09-02'),
('1T2U',20, 20, '2024-08-20', '2024-09-03'),
('1U2V',21, 21, '2024-08-21', '2024-09-04'),
('1V2W',22, 22, '2024-08-22', '2024-09-05'),
('1W2X',23, 23, '2024-08-23', '2024-09-06'),
('1X2Y',24, 24, '2024-08-24', '2024-09-07'),
('1Y2Z',25, 25, '2024-08-25', '2024-09-08'),
('1Z2A',26, 26, '2024-08-26', '2024-09-09'),
('2A3B',27, 27, '2024-08-27', '2024-09-10'),
('2B3C',28, 28, '2024-08-28', '2024-09-11'),
('2C3D',29, 29, '2024-08-29', '2024-09-12'),
('2DCE',30, 30, '2024-08-30', '2024-09-13');

CREATE TABLE Hostel (
    Hostel_ID INT AUTO_INCREMENT PRIMARY KEY,
    Hostel_name VARCHAR(100),
    Hostel_type ENUM('Boys', 'Girls')
);
insert into Hostel (Hostel_ID, Hostel_name, Hostel_type)
values(1, 'Boys Hostel 1', 'Boys'),
(2, 'Girls Hostel 1', 'Girls'),
(3, 'Boys Hostel 2', 'Boys'),
(4, 'Girls Hostel 2', 'Girls'),
(5, 'Boys Hostel 3', 'Boys'),
(6, 'Girls Hostel 3', 'Girls'),
(7, 'Boys Hostel 4', 'Boys'),
(8, 'Girls Hostel 4', 'Girls'),
(9, 'Boys Hostel 5', 'Boys'),
(10, 'Girls Hostel 5', 'Girls'),
(11, 'Boys Hostel 1', 'Boys'),
(12, 'Girls Hostel 1', 'Girls'),
(13, 'Boys Hostel 2', 'Boys'),
(14, 'Girls Hostel 2', 'Girls'),
(15, 'Boys Hostel 3', 'Boys'),
(16, 'Girls Hostel 3', 'Girls'),
(17, 'Boys Hostel 4', 'Boys'),
(18, 'Girls Hostel 4', 'Girls'),
(19, 'Boys Hostel 5', 'Boys'),
(20, 'Girls Hostel 5', 'Girls'),
(21, 'Boys Hostel 1', 'Boys'),
(22, 'Girls Hostel 1', 'Girls'),
(23, 'Boys Hostel 2', 'Boys'),
(24, 'Girls Hostel 2', 'Girls'),
(25, 'Boys Hostel 3', 'Boys'),
(26, 'Girls Hostel 3', 'Girls'),
(27, 'Boys Hostel 4', 'Boys'),
(28, 'Girls Hostel 4', 'Girls'),
(29, 'Boys Hostel 5', 'Boys'),
(30, 'Girls Hostel 5', 'Girls');

CREATE TABLE HostelRooms (
    Room_ID INT AUTO_INCREMENT PRIMARY KEY,
    Hostel_ID INT,
    Room_Number VARCHAR(10),
    Capacity INT,
    Current_Occupancy INT,
    FOREIGN KEY (Hostel_ID) REFERENCES Hostel(Hostel_ID)
);

INSERT INTO HostelRooms (Room_ID, Hostel_ID, Room_number, Capacity, Current_occupancy) 
values ('001', 1, '101', 3, 2),
('002', 1, '102', 3, 3),
('003', 2, '201', 4, 2),
('004', 2, '202', 4, 4),
('005', 3, '301', 2, 1),
('006', 3, '302', 2, 2),
('007', 4, '401', 3, 3),
('008', 4, '402', 3, 1),
('009', 5, '501', 4, 2),
('010', 5, '502', 4, 3),
('011', 6, '601', 2, 2),
('012', 6, '602', 2, 1),
('013', 7, '701', 3, 3),
('014', 7, '702', 3, 2),
('015', 8, '801', 4, 4),
('016', 8, '802', 4, 2),
('017', 9, '901', 2, 2),
('018', 9, '902', 2, 1),
('019', 10, '1001', 3, 3),
('020', 10, '1002', 3, 3),
('021', 11, '1101', 4, 2),
('022', 11, '1102', 4, 4),
('023', 12, '1201', 2, 1),
('024', 12, '1202', 2, 2),
('025', 13, '1301', 3, 3),
('026', 13, '1302', 3, 2),
('027', 14, '1401', 4, 4),
('028', 14, '1402', 4, 2),
('029', 15, '1501', 2, 2),
('030', 15, '1502', 2, 1);

create table  Mess (
    Mess_ID int not null,
    Hostel_ID int,
    Mess_name varchar(100),
    primary key(Mess_ID),
    foreign key(Hostel_ID) references Hostel(Hostel_ID)
);

insert into Mess (Mess_ID, Hostel_ID, Mess_name) 
values (1, 1, 'Main Mess'),
(2, 2, 'Secondary Mess'),
(3, 3, 'East Wing Mess'),
(4, 4, 'West Wing Mess'),
(5, 5, 'North Wing Mess'),
(6, 6, 'South Wing Mess'),
(7, 7, 'Central Mess'),
(8, 8, 'Junior Boys Mess'),
(9, 9, 'Senior Boys Mess'),
(10, 10, 'Junior Girls Mess'),
(11, 11, 'Senior Girls Mess'),
(12, 12, 'Boys Mess 1'),
(13, 13, 'Girls Mess 1'),
(14, 14, 'Boys Mess 2'),
(15, 15, 'Girls Mess 2'),
(16, 1, 'Additional Boys Mess 1'),
(17, 2, 'Additional Girls Mess 1'),
(18, 3, 'Additional Boys Mess 2'),
(19, 4, 'Additional Girls Mess 2'),
(20, 5, 'Boys Mess 3'),
(21, 6, 'Girls Mess 3'),
(22, 7, 'Boys Mess 4'),
(23, 8, 'Girls Mess 4'),
(24, 9, 'Boys Mess 5'),
(25, 10, 'Girls Mess 5'),
(26, 11, 'Boys Mess 6'),
(27, 12, 'Girls Mess 6'),
(28, 13, 'Boys Mess 7'),
(29, 14, 'Girls Mess 7'),
(30, 15, 'Boys Mess 8');

create table MessMenu (
    Menu_ID int not null,
    Mess_ID int,
    Day varchar(100),
    meal_type varchar(100),
    menu_details varchar(200),
    primary key(Menu_ID),
    foreign key (Mess_ID) references Mess(Mess_ID)
);

insert into MessMenu (Menu_ID, Mess_ID, Day, Meal_type, Menu_details)
values(1, 1, 'Monday', 'Lunch', 'Rice, Dal, Chicken Curry'),
(2, 1, 'Monday', 'Dinner', 'Chapati, Paneer Masala, Salad'),
(3, 2, 'Tuesday', 'Breakfast', 'Idli, Sambar, Coconut Chutney'),
(4, 2, 'Tuesday', 'Lunch', 'Fried Rice, Manchurian, Raita'),
(5, 3, 'Wednesday', 'Dinner', 'Rice, Sambar, Fish Fry'),
(6, 3, 'Wednesday', 'Breakfast', 'Poha, Jalebi, Curd'),
(7, 4, 'Thursday', 'Lunch', 'Pulao, Chicken Tikka, Raita'),
(8, 4, 'Thursday', 'Dinner', 'Chapati, Aloo Gobi, Dal Tadka'),
(9, 5, 'Friday', 'Breakfast', 'Dosa, Tomato Chutney, Filter Coffee'),
(10, 5, 'Friday', 'Lunch', 'Biriyani, Raita, Boiled Egg'),
(11, 6, 'Saturday', 'Dinner', 'Pasta, Garlic Bread, Soup'),
(12, 6, 'Saturday', 'Breakfast', 'Upma, Chutney, Tea'),
(13, 7, 'Sunday', 'Lunch', 'Mutton Curry, Rice, Salad'),
(14, 7, 'Sunday', 'Dinner', 'Chapati, Mixed Vegetable Curry, Curd'),
(15, 1, 'Monday', 'Breakfast', 'Paratha, Curd, Pickle'),
(16, 1, 'Monday', 'Lunch', 'Veg Pulao, Raita, Paneer Butter Masala'),
(17, 2, 'Tuesday', 'Dinner', 'Rice, Dal Makhani, Chicken Fry'),
(18, 2, 'Tuesday', 'Breakfast', 'Aloo Paratha, Curd, Pickle'),
(19, 3, 'Wednesday', 'Lunch', 'Jeera Rice, Rajma, Salad'),
(20, 3, 'Wednesday', 'Dinner', 'Roti, Baingan Bharta, Raita'),
(21, 4, 'Thursday', 'Breakfast', 'Puri, Chole, Lassi'),
(22, 4, 'Thursday', 'Lunch', 'Masala Rice, Curd, Chicken Gravy'),
(23, 5, 'Friday', 'Dinner', 'Roti, Mixed Dal, Paneer Sabzi'),
(24, 5, 'Friday', 'Breakfast', 'Vada, Sambar, Chutney'),
(25, 6, 'Saturday', 'Lunch', 'Biryani, Boiled Egg, Raita'),
(26, 6, 'Saturday', 'Dinner', 'Fried Rice, Chili Chicken, Raita'),
(27, 7, 'Sunday', 'Breakfast', 'Pancakes, Maple Syrup, Fresh Fruits'),
(28, 7, 'Sunday', 'Lunch', 'Mutton Biryani, Raita, Salad'),
(29, 1, 'Monday', 'Dinner', 'Pasta, White Sauce, Garlic Bread'),
(30, 1, 'Monday', 'Breakfast', 'Oats, Milk, Banana');

create table  MessAttendance (
    Attendance_ID int not null,
    Std_ID int,
    Mess_ID int,
    Date DATE,
    Meal_type varchar(100),
    Attendance_status boolean
);

INSERT INTO MessAttendance (Attendance_ID, Std_ID, Mess_ID, Date, Meal_type, Attendance_status) 
VALUES(1, 101, 1, '2024-08-01', 'Breakfast', TRUE),
(2, 102, 1, '2024-08-02', 'Breakfast', TRUE),
(3, 103, 1, '2024-08-03', 'Breakfast', FALSE),
(4, 104, 2, '2024-08-01', 'Lunch', TRUE),
(5, 105, 2, '2024-08-02', 'Lunch', TRUE),
(6, 106, 2, '2024-08-03', 'Lunch', FALSE),
(7, 107, 3, '2024-08-01', 'Dinner', TRUE),
(8, 108, 3, '2024-08-02', 'Dinner', TRUE),
(9, 109, 3, '2024-08-03', 'Dinner', FALSE),
(10, 110, 1, '2024-08-04', 'Breakfast', TRUE),
(11, 111, 1, '2024-08-05', 'Breakfast', TRUE),
(12, 112, 1, '2024-08-06', 'Breakfast', FALSE),
(13, 113, 2, '2024-08-04', 'Lunch', TRUE),
(14, 114, 2, '2024-08-05', 'Lunch', TRUE),
(15, 115, 2, '2024-08-06', 'Lunch', FALSE),
(16, 116, 3, '2024-08-04', 'Dinner', TRUE),
(17, 117, 3, '2024-08-05', 'Dinner', TRUE),
(18, 118, 3, '2024-08-06', 'Dinner', FALSE),
(19, 119, 1, '2024-08-07', 'Breakfast', TRUE),
(20, 120, 1, '2024-08-08', 'Breakfast', TRUE),
(21, 121, 1, '2024-08-09', 'Breakfast', FALSE),
(22, 122, 2, '2024-08-07', 'Lunch', TRUE),
(23, 123, 2, '2024-08-08', 'Lunch', TRUE),
(24, 124, 2, '2024-08-09', 'Lunch', FALSE),
(25, 125, 3, '2024-08-07', 'Dinner', TRUE),
(26, 126, 3, '2024-08-08', 'Dinner', TRUE),
(27, 127, 3, '2024-08-09', 'Dinner', FALSE),
(28, 128, 1, '2024-08-10', 'Breakfast', TRUE),
(29, 129, 1, '2024-08-10', 'Lunch', TRUE),
(30, 130, 1, '2024-08-10', 'Dinner', FALSE);

SELECT * FROM Student WHERE Hostel_ID = 1;

SELECT B.Title, l.Issue_date, l.Return_date
FROM Library l
JOIN Books B ON l.Book_ID = B.Book_ID
WHERE l.Std_ID = 1;

SELECT menu_details
FROM MessMenu
WHERE mess_id = 1 AND day = 'Monday' AND meal_type = 'Lunch';

SELECT date, meal_type, attendance_status
FROM MessAttendance
WHERE mess_id = 2 AND Meal_type = 'Dinner' AND Std_ID =2;
