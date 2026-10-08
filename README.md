CREATE TABLE hospital_patients (
    patient_id INTEGER PRIMARY KEY,
    patient_name TEXT NOT NULL,
    department TEXT NOT NULL,
    admission_date TEXT NOT NULL,
    discharge_date TEXT,
    bill_amount REAL NOT NULL,
    payment_status TEXT NOT NULL
);

INSERT INTO hospital_patients VALUES (101, 'Arun', 'Cardiology', '2026-01-02', '2026-01-07', 45000.00, 'Paid');
INSERT INTO hospital_patients VALUES (102, 'Meena', 'Neurology', '2026-01-03', '2026-01-10', 62000.00, 'Pending');
INSERT INTO hospital_patients VALUES (103, 'Karthik', 'Orthopedics', '2026-01-05', '2026-01-09', 38000.00, 'Paid');
INSERT INTO hospital_patients VALUES (104, 'Divya', 'Pediatrics', '2026-01-08', '2026-01-12', 28000.00, 'Paid');
INSERT INTO hospital_patients VALUES (105, 'Suresh', 'General Medicine', '2026-01-10', '2026-01-15', 22000.00, 'Pending');
INSERT INTO hospital_patients VALUES (106, 'Priya', 'Cardiology', '2026-01-12', '2026-01-18', 55000.00, 'Paid');
INSERT INTO hospital_patients VALUES (107, 'Rahul', 'Neurology', '2026-01-15', '2026-01-22', 70000.00, 'Pending');
INSERT INTO hospital_patients VALUES (108, 'Anitha', 'Orthopedics', '2026-01-18', '2026-01-23', 42000.00, 'Paid');
INSERT INTO hospital_patients VALUES (109, 'Vijay', 'Pediatrics', '2026-01-20', '2026-01-24', 30000.00, 'Paid');
INSERT INTO hospital_patients VALUES (110, 'Nisha', 'General Medicine', '2026-01-22', '2026-01-28', 26000.00, 'Pending');
INSERT INTO hospital_patients VALUES (111, 'Ramesh', 'Cardiology', '2026-01-25', '2026-01-31', 60000.00, 'Paid');
INSERT INTO hospital_patients VALUES (112, 'Lakshmi', 'Neurology', '2026-01-27', '2026-02-02', 58000.00, 'Pending');
INSERT INTO hospital_patients VALUES (113, 'Deepak', 'Orthopedics', '2026-01-30', '2026-02-05', 47000.00, 'Paid');
INSERT INTO hospital_patients VALUES (114, 'Swetha', 'Pediatrics', '2026-02-02', '2026-02-06', 32000.00, 'Pending');
INSERT INTO hospital_patients VALUES (115, 'Manoj', 'General Medicine', '2026-02-04', '2026-02-09', 24000.00, 'Paid');
INSERT INTO hospital_patients VALUES (116, 'Harini', 'Cardiology', '2026-02-07', '2026-02-15', 68000.00, 'Pending');
INSERT INTO hospital_patients VALUES (117, 'Gokul', 'Neurology', '2026-02-10', '2026-02-17', 72000.00, 'Paid');
INSERT INTO hospital_patients VALUES (118, 'Keerthi', 'Orthopedics', '2026-02-12', '2026-02-18', 44000.00, 'Pending');
INSERT INTO hospital_patients VALUES (119, 'Santhosh', 'Pediatrics', '2026-02-15', '2026-02-19', 29000.00, 'Paid');
INSERT INTO hospital_patients VALUES (120, 'Pavithra', 'General Medicine', '2026-02-18', '2026-02-25', 27000.00, 'Pending');
INSERT INTO hospital_patients VALUES (121, 'Mohan', 'Cardiology', '2026-02-20', '2026-02-27', 63000.00, 'Paid');
INSERT INTO hospital_patients VALUES (122, 'Aishwarya', 'Neurology', '2026-02-22', '2026-03-01', 75000.00, 'Pending');
INSERT INTO hospital_patients VALUES (123, 'Surya', 'Orthopedics', '2026-02-25', '2026-03-03', 49000.00, 'Paid');
INSERT INTO hospital_patients VALUES (124, 'Janani', 'Pediatrics', '2026-02-27', '2026-03-02', 31000.00, 'Pending');
INSERT INTO hospital_patients VALUES (125, 'Ashok', 'General Medicine', '2026-03-01', '2026-03-08', 25000.00, 'Paid');

SELECT * FROM hospital_patients;
