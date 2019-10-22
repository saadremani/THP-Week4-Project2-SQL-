# THP-Week4-Project2-SQL-




2.2. Concepts de sites et base de donnée 2.2.1. MOOCcademy

- Table Course : 				id integer (primary key)
								title text
								description text
- Table Lesson : 				id integer (primary key)
								title text
								body text
								id_course (foreign key from Course) - relation One Course for Many Lessons

2.2.2. The Hacking Pinterest

- Table User					id integer (primary key)
								name text
- Table Pins					id integer (primary key)
								url text
								id_user (foreign key from User) - relation One User for Many Pins
- Table Comment					id integer (primary key)
								content text
								id_user (foreign key from User) - relation One User for Many Comment
								id_pins (foreign key from Pins) - relation One Pins for Many Comment
