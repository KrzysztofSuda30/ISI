Punkt drugi z tutoriala:

Połączenie z bazą:
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/c91d550b-bb81-4bcc-a69e-41912da26546)



![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/0acad671-09e1-4e62-94d2-23b9cd5df399)


![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/623917b5-f0f4-4323-9ef4-032d14d8aa92)


![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/12788909-9642-4bc2-ada6-ed55ee3ae998)


![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/581fb818-8ed1-4aaa-8bd8-6aba4c70b7c3)


![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/95b153ea-56b2-4ae8-83a2-2d38c25228f4)

Exercise
Write a SQL query to select the sex and body mass columns from the little_penguins in that order, sorted such that the largest body mass appears first.
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/05a3d057-ff27-4096-a6a6-dab3605820e2)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/af3555d4-3746-4531-b70a-26ac95a45340)


![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/eb1ea19c-1222-4ca1-8d3e-8b14081cf16f)


![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/a72c73e2-03e0-47c1-a3df-c2b153533468)

Write a SQL query to select the islands and species from rows 50 to 60 inclusive of the penguins table. Your result should have 11 rows.
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/50c0521b-28b3-46d7-ae22-e5bc0349b6a4)


Modify your query to select distinct combinations of island and species from the same rows and compare the result to what you got in part 1.
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/d0941940-d5f0-4e36-a89f-7edf87ea0943)


![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/7af5a861-2433-4782-abdb-8c25a0786c92)

Write a query to select the body masses from penguins that are less than 3000.0 grams.
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/7b367011-0e1f-4041-9dc6-3b24924ae3b2)

Write another query to select the species and sex of penguins that weight less than 3000.0 grams. This shows that the columns displayed and those used in filtering are independent of each other.
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/d5148f1b-3de9-4c5d-92bc-aeca77ab5fc7)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/febf336d-3cd8-4fc0-85d7-9d4f62c1d30a)

Use the not operator to select penguins that are not Gentoos.
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/f8e39d42-7bbc-4398-b32d-51ae3ee48cf8)
bardzo dużo wierszy zostało zwruconych

SQL’s or is an inclusive or: it succeeds if either or both conditions are true. SQL does not provide a specific operator for exclusive or, which is true if either but not both conditions are true, but the same effect can be achieved using and, or, and not. Write a query to select penguins that are female or on Torgersen Island but not both.
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/32fe3d76-8749-46da-b021-d40f72ded005)
mniej ale nadal dużo

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/9e99d6d9-8d53-4f09-8adb-4f8b76e61869)


![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/67b7c4d5-cc20-48be-be5f-b0ef038836d5)

Write a single query that calculates and returns:
-A column called what_where that has the species and island of each penguin separated by a single space.
-A column called bill_ratio that has the ratio of bill length to bill depth.
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/9425977c-b727-43e7-9aaf-0e847d54256b)


![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/ea142381-4388-40cd-80fa-5c612a425430)

Use SQLite’s .nullvalue command to change the printed representation of null to the string null and then re-run the previous query. When will displaying null as null be easier to understand? When might it be misleading?
.nullvalue null

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/e83a5b87-6b7f-4ced-bf53-f254cb552cfc)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/78a6bc02-b76c-4cca-a897-e11b467b636c)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/53f0b9fc-5a8f-411a-9b7f-6840ec0ae8cc)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/197e3bd1-d3fe-4716-b696-d76477522436)

Write a query to find penguins whose body mass is known but whose sex is not.
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/273b05ae-0df7-468d-992e-c609c3b5b4a5)


Write another query to find penguins whose sex is known but whose body mass is not.
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/50fc6b4a-c76e-44de-b8f4-da301eb3d61c)
nie istnieje takie w bazie danych

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/ff3d767d-a416-47e2-8b7d-c46cfceffe9e)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/766db9b4-2b95-4e06-971e-39f5e31634a2)

What is the average body mass of penguins that weight more than 3000.0 grams?
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/fd47f3ad-c4ac-4543-89c8-b76f135cbb02)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/e8c694c5-180b-4e2b-9fcd-3a4eaa5f692b)

How many different body masses are in the penguins dataset?
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/63b40996-d2cd-4fed-a774-cb8cd2f63a85)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/5876b5d7-240f-48e9-ba50-676869b48489)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/abc4480d-8c73-4139-89b9-64884d6a8791)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/a5dc4912-e338-4b7b-b605-6dc41d56e89c)

Explain why the output of the previous query has a blank line before the rows for female and male penguins.
Jest tam pusta linia, ponieważ w niej znajdowałaby się zawartość null czyli pingwinów bez płci(tęczowych?)


Write a query that shows each distinct body mass in the penguin dataset and the number of penguins that weigh that much.
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/a8ec9938-61c3-41c1-8e3c-c1ff6294adc6)
działa, ale jest znacznie więcej linijek

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/1e3433f8-05f6-4f4f-bb16-9930aa1185b4)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/0a53855d-7e62-4802-8a19-c84683c00642)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/f557a091-171d-4c71-8543-1c48c70e1f1f)

Write a query that uses filter to calculate the average body masses of heavy penguins (those over 4500 grams) and light penguins (those under 3500 grams) simultaneously. Is it possible to do this using where instead of filter?
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/50345860-2434-40a8-8a5a-81f10ceb7479)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/ecab3ce5-25f8-451f-83be-c718c807da5b)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/f754cb19-01ca-42ef-8974-ded749bd713e)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/b4f68db4-0892-4de9-8f81-11baaeaca0c6)

Using an in-memory database, define a table called notes with two text columns author and note and then add three or four rows. Use a query to check that the notes have been stored and that you can (for example) select by author name.
What happens if you try to insert too many or too few values into notes? What happens if you insert a number instead of a string into the note field?
Jeśli doda się trzy wartości do tabeli z dwoma wartościami wyskoczy błąd

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/3ce30413-c8d6-4b2b-88e9-8196ff5fde1c)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/abebe7db-70aa-42f0-abd5-79e59d633cfb)

What happens if you try to delete rows that don’t exist (e.g., all entries in work that refer to juna)?
Polecenie się wykona, lecz napisze że dotyczyło ono 0 wierszy

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/668def43-12d1-4417-bf23-a5be0a885b6a)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/5112ad41-952a-4b7c-9e0d-fa2acd589dd3)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/0ae36606-16ba-42a4-b425-9b7d3118bf60)

Re-run the query shown above using where job = name instead of the full table.name notation. Is the shortened form easier or harder to read and more or less likely to cause errors?
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/b23c1952-e602-4cea-9412-859fbbf646ec)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/4024c1c2-0029-4d43-aa99-aae72bd7fd05)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/cc883825-7a38-4e3c-b9ef-29cf0a9e2aee)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/a917fd4b-beeb-427b-a36b-63fa82adc295)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/a743b808-b055-490d-80e3-8b0bf5e7227b)


Punkt trzeci z poradnika-TOOLS:

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/47b44356-dd23-40e0-a846-1b13f865d561)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/c2237501-fe55-4dbd-950a-bd120dc52ae2)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/f4e9c51e-9440-49a0-ba57-6513da4195d9)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/b5492bdc-4a7a-4fe1-bb3b-77631fddf7af)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/9e3936ed-4f8b-4103-9513-4d6046c8442b)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/ae2b0d9c-3880-4afa-a5d7-b2ad1c9754b2)

Are you able to modify the values stored in sqlite_sequence? In particular, are you able to reset the values so that the same sequence numbers are generated again?
Można modyfikować jedynie dodając nowe wartości do tabeli

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/ea724775-27c6-41ba-85ff-ba006946f8bd)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/f01aac36-a9e6-460f-a50a-143da2246cec)

Powrót do pinguin.db

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/26702d26-db6c-4bb7-b089-da6fbd22d591)

Use a subquery to find the number of penguins that weigh the same as the lightest penguin.
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/ff06060e-4d81-4bf2-8266-36a3548fd660)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/02cd3b3a-6bab-4427-9c8e-f449feecfe61)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/da470fe4-662d-4080-ac00-4ec86a451741)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/9c2f3fb1-17f6-4327-b9e2-2e40162be824)

Use a CTE to find the number of penguins that weigh the same as the lightest penguin of the same sex and species.
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/7fd17f9a-031b-45b1-910a-cd8d7274bd73)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/49ce6a4d-2c34-4481-8c57-f07c92bb30b2)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/75034146-a378-4db0-9313-379f67fdeeae)

What does each of the expressions shown below produce? Which ones do you think actually attempt to divide by zero?
iif(0, 123, 1/0)
iif(1, 123, 1/0)
iif(0, 1/0, 123)
iif(1, 1/0, 123)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/5c52764e-fff4-4dae-9d81-20e81f9623b8)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/6953fa5d-7989-4f28-9e53-23c7c7d75ad8)

Modify the query above so that the outputs are "penguin is small" and "penguin is large" by concatenating the string "penguin is " to the entire case rather than to the individual when branches. (This exercise shows that case/when is an expression rather than a statement.)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/5d15f1ff-2709-44e5-b91f-5d04aa5f76b7)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/d9ae605e-08f6-4199-bd52-c16a142c7558)

Przełączenie się na assays.db :
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/a2f73e61-2688-45c0-9ae4-f69d3786039a)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/c4f3ed57-2b18-4eb1-a79a-d833f7f5f744)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/bc363311-d3a6-4a66-a0a1-101de60e12ff)

Rewrite the pattern-matching query shown above using glob.
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/20a54af5-8a51-49cd-a8d8-9a181276d3c6)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/689959ac-e505-40b8-ae91-0b9794267435)

Write a query whose result includes two rows for each Adelie penguin in the penguins database. How can you check that your query is working correctly?
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/bd0b012d-ffeb-43e4-ae2a-021129af7e11)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/5aa951bd-829f-4dbe-a2fe-ac76e1bb8fcc)

Use intersect to find all Adelie penguins that weigh more than 4000 grams. How can you check that your query is working correctly?
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/a2391a6f-a6c9-441a-8e24-04f983473da1)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/83c48915-d69b-4c5e-96f7-2529747efe24)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/6906bc48-8991-4a83-af5e-587dbfd522dc)

Write a query that:
uses a CTE to create 1000 random numbers between 0 and 10 inclusive;
uses a second CTE to calculate their mean; and
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/1c9bafd3-c7ae-4585-b2a2-73f70e8c6b94)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/163f6e06-cb84-429c-9bf5-5b9038a9fd9e)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/9913837f-7115-4b71-a64d-baee64ce5cf5)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/835fbe22-b286-4649-8155-246dd5b713cf)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/d646c479-d116-42a6-9fc8-bb0c4e2e7ebf)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/763a25a8-b27a-479c-af16-55d80474142e)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/02bf075b-63e7-4c75-946e-7d2974cae2c9)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/4dee1751-de35-445d-ab1e-383dce7a0926)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/098fa935-2fa0-4e2d-a4b8-f1ee46d15c34)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/b841d6b0-9af0-4717-9b64-d4c15a16885b)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/0684ad90-09ad-4c33-8f9c-3c616dce200b)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/a7adebc0-d639-40b9-aa8f-558fab9bed1b)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/8e282313-4c10-4f01-b447-188e473a8e58)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/aeca43a4-34f5-4bd3-97dd-ece4fcd07e07)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/047ae6fc-6011-4b0b-9f28-6f149d0f3ce7)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/f6d1c987-ba48-4e81-8677-7f5f6191331b)

Create a query that:
finds the unique weights of the penguins in the penguins database;
sorts them;
finds the difference between each successive distinct weight; and
counts how many times each unique difference appears.
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/0a293c64-a13c-45d7-b245-a69f159d5de3)

Część czwarta-Advanced Features:

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/b55315fc-b4b2-4237-addb-aafc83c5b57f)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/fabcca47-1e78-48f4-bae3-b6393d5438ab)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/e313b96e-9ba0-4292-be89-fcb289cf34b6)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/5e863f61-e7aa-47e6-8688-fc3b69432e9e)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/a643fa05-5e72-42c2-9b55-9a95c73dd6de)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/42860c40-476f-4b64-a639-212e00dd5e9b)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/1873cfde-7b89-43c9-9170-6c15c0c1ab7f)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/ca23eeeb-fb65-46af-8237-b572b3db9032)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/f755f8a8-2190-46ad-93cb-05d1ae49fd1a)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/d580b542-a19c-43d5-beb4-96cac367bb75)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/9b804bae-ea79-49b8-8632-0ed22fe46789)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/263551bf-9e20-48f8-b57d-87105b22816c)

Część5-Skrypty Python

1Quering from python


import sqlite3
import sys

db_path = "db/penguins.db"
connection = sqlite3.connect(db_path)
cursor = connection.execute("select count(*) from penguins;")
rows = cursor.fetchall()
print(rows)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/f25ba891-e6be-4ea0-8ffa-5291e07b4391)

2Incremental Fetch

import sqlite3
import sys

db_path = "db/penguins.db"
connection = sqlite3.connect(db_path)
cursor = connection.cursor()
cursor = cursor.execute("select species, island from penguins limit 5;")
while row := cursor.fetchone():
    print(row)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/edb54cbc-07dd-414b-856e-8d512077e247)

3Insert, Delete, and All That

import sqlite3

connection = sqlite3.connect(":memory:")
cursor = connection.cursor()
cursor.execute("create table example(num integer);")

cursor.execute("insert into example values (10), (20);")
print("after insertion", cursor.execute("select * from example;").fetchall())

cursor.execute("delete from example where num < 15;")
print("after deletion", cursor.execute("select * from example;").fetchall())

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/06944d8f-658f-44cf-9356-760c1a993d7b)

4Interpolating Values

import sqlite3

connection = sqlite3.connect(":memory:")
cursor = connection.cursor()
cursor.execute("create table example(num integer);")

cursor.executemany("insert into example values (?);", [(10,), (20,)])
print("after insertion", cursor.execute("select * from example;").fetchall()

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/28b2fbb8-077d-45f5-aff4-bd0e13a8bdfe)

5Script Execution

import sqlite3

SETUP = """\
drop table if exists example;
create table example(num integer);
insert into example values (10), (10);
"""

connection = sqlite3.connect(":memory:")
cursor = connection.cursor()
cursor.executescript(SETUP)
print("after insertion", cursor.execute("select * from example;").fetchall())

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/04ad20c3-2740-4e93-aaa5-6bb61a7aa6a0)

6SQLite Exceptions in Python

import sqlite3

SETUP = """\
create table example(num integer check(num > 0));
insert into example values (10);
insert into example values (-1);
insert into example values (20);
"""

connection = sqlite3.connect(":memory:")
cursor = connection.cursor()
try:
    cursor.executescript(SETUP)
except sqlite3.Error as exc:
    print(f"SQLite exception: {exc}")
print("after execution", cursor.execute("select * from example;").fetchall())
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/0828129d-dfa9-4084-b7e8-6c4d793398c5)

7Python in SQLite

import sqlite3

SETUP = """\
create table example(num integer);
insert into example values (-10), (10), (20), (30);
"""


def clip(value):
    if value < 0:
        return 0
    if value > 20:
        return 20
    return value


connection = sqlite3.connect(":memory:")
connection.create_function("clip", 1, clip)
cursor = connection.cursor()
cursor.executescript(SETUP)
for row in cursor.execute("select num, clip(num) from example;").fetchall():
    print(row)

![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/612e224f-5990-4729-9f67-69aff0c1651f)

8Handling Dates and Times

from datetime import date
import sqlite3


# Convert date to ISO-formatted string when writing to database
def _adapt_date_iso(val):
    return val.isoformat()


sqlite3.register_adapter(date, _adapt_date_iso)


# Convert ISO-formatted string to date when reading from database
def _convert_date(val):
    return date.fromisoformat(val.decode())


sqlite3.register_converter("date", _convert_date)

SETUP = """\
create table events(
    happened date not null,
    description text not null
);
"""

connection = sqlite3.connect(":memory:", detect_types=sqlite3.PARSE_DECLTYPES)
cursor = connection.cursor()
cursor.execute(SETUP)

cursor.executemany(
    "insert into events values (?, ?);",
    [(date(2024, 1, 10), "started tutorial"), (date(2024, 1, 29), "finished tutorial")],
)

for row in cursor.execute("select * from events;").fetchall():
    print(row)
![image](https://github.com/KrzysztofSuda30/ISI/assets/172184955/2856bd57-64f7-4b57-92a8-3e72599031a0)
