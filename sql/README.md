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
















































