# Asociace

## Cvičení na práci s nástrojem Git od Nauč mě IT

**Asociace** je mentální propojení myšlenek, pocitů, vzpomínek, představ, vjemů atd. Když se řekne webová stránka, co si představíte? Člověk od člověka se to liší, nás napadl třeba prohlížeč, aplikace, email, Seznam.

V rámci cvičení si zahrajeme hru na asociace. Smyslem hry je napsat slovo nebo slovní spojení, které tě napadne po přečtení posledního slova či slovního spojení v souboru asociace.txt. My vykopáváme spojením **webová stránka**.

Jak hrát:

Prerekvizity:
- Účet na GitHubu

1. Udělej si kopii repozitáře k sobě. Použij v pravo nahoře tlačítko **Fork**.
2. Stáhni si repozitář k sobě. Pod zeleným tlačítkem **Code** najdeš adresu, kterou potřebuješ. Použij příkaz `git clone https://adresa.git`
3. Vytvoř si vlastní větev a přepni se do ní: `git checkout -b vetevXY`
4. Napiš svou asociaci na posledí slovo v souboru [asociace.txt](https://github.com/Nauc-me-IT/asociace/blob/main/asociace.txt)
5. Podívej se kdo commitoval před tebou: `git log -1`
6. Napiš číslo předchozího commitu do souboru [preLog.txt](https://github.com/Nauc-me-IT/asociace/blob/main/preLog.txt)
7. Podívej se jaké soubory jsou upravé nebo vytvořené: `git status`
8. Přidej soubory do stage: `git add .`, nebo vypiš soubory např. `git add preLog.txt`
9. Commitni svou práci: `git commit -m "nejaky text"`, kde *nejaky text* je tvoje zpráva
10. Pošli svoji práci na server: `git push --set-upstream origin test`
11. Spoj svou větev s **main** větví. Vytvoř pull request. Jdi na [GitHub](http://github.com/) do svého projektu a hned nahoře nad soubory je zelené tlačítko **Compare & pull request**. (jedná se o začátek merge procesu).
13. Projdi si změny a potvď vytvoření pull requestu. Zelené tlačítko **Create**
14. Teď to vše musíš ještě spojit. Počkej až doběhne žluté kolečko a objeví se ti tlačítko Merge pull request. V tento moment se dělá codereview kolegům.
15. Potvrď Merge.

Gratulujeme teď jsi provedl první merge.

Pokud chceš můžeš svou asociaci spojit s naším repozitářem.

1. Merge k nám doplním.
