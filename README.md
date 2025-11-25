https://github.com/SimeAnte/appa-ag.git
SELECT k.naslov
FROM knjiga AS k
JOIN autor AS a ON a.id = k.autor
WHERE a.prezime_ime = 'Andrić Ivo'
ORDER BY k.naslov ASC;
