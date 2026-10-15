# Fulfillment tým: skilly pro Claude

Šest „zaměstnanci" vytvoření z rolí v této složce, přeložení do češtiny a upravení pro fulfillment:

| Skill | Jak ho zavolat v chatu | Na co |
|---|---|---|
| `obchodnik` | „Obchodníku, …" | sehnat klienty, oslovovací e-maily, nabídka |
| `cenik` | „Ceník: …" | kolik si účtovat, kalkulace zakázky, marže |
| `provoz-skladu` | „Provoz: …" | postupy ve skladu, kapacita, chyby, brigádníci |
| `zakaznicka-pece` | „Podpora: …" | odpovědi klientům, reklamace, stížnosti |
| `emailing` | „Mailingu, …" | newslettery, automatické série e-mailů, kontakty, GDPR |
| `socialni-site` | „Sítě: …" | příspěvky na LinkedIn/FB/Instagram, kalendář, videa ze skladu |

Fungují stejně jako tvoji `/ceo` a Pepa a můžou spolupracovat. CEO může úkol delegovat, např. „ať to Ceník spočítá".

## Jak je nahrát do Claude (jednou, cca 5 minut)

1. Stáhni si soubory `.zip` ze složky `cz-fulfillment-skills/zip/`.
2. Na **claude.ai** otevři **Nastavení → Možnosti (Capabilities) → Skills**.
3. Klikni na **Nahrát skill (Upload skill)** a vyber první `.zip`. Totéž udělej pro zbylé.
4. Zkontroluj, že jsou všechny zapnuté.

## Jak je používat

Otevři normální chat a piš běžně, například:

- „Obchodníku, napiš mi e-mail pro e-shop s kosmetikou, který posílá asi 200 balíků měsíčně."
- „Ceník: klient má 2 palety a 300 objednávek měsíčně. Kolik mu mám účtovat?"
- „Provoz: napiš postup balení pro nového brigádníka."
- „Podpora: klient píše, že mu nedorazil balík, tady je jeho e-mail: …"

Tip: řekni jim jednou svoje čísla (mzdy, nájem, dopravci, ceny). Čím víc vědí, tím přesnější jsou.
