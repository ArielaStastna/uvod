# uvod
 Vytvořte třídu s názvem Student, která bude obsahovat:
• String: surname, name
• Int: id, year
• Konstruktor v pořadí (surname, name, id, year) – pořadí důležité pro sdílený kód
• Z elerningu stáhnete předpřipravený seznam, který vložíte do listu students
• Vytvořte novou třídu s názvem StudentsController, ve které bude vaše práce
• Zde vytvořte metody, které obslouží tyto požadavky:
• /student vypíše Student: VašeJméno ID: VašeID, Jméno a ID bude tučně
• /student?name=Test&id=123456 vypíše místo vašich hodnot zadané hodnoty
• /students vypíše seznam všech studentů ze staženého listu
• /students?vutid=123456 vypíše pouze konkrétního studenta, pokud v listu nebude,
napíše se, že neexistuje. (Studenta zobrazíte z objektu třídy Student a bude tedy
obsahovat jméno, příjmení, id a rok narození)
• První 2 body můžete zpracovat pouze jako String (i jejich výchozí hodnoty)
