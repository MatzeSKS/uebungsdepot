# Übungsdepots (reine Simulation, keine Anlageberatung)

Letzter Lauf: 04.11.2026 (Mittwoch, Lauf ohne Kursdaten, keine Bewertung, keine Orders)

## Regeln

**Depot A (Aktien und Gold)**, Start 13.10.2026 mit 10.000 EUR, +500 EUR am 13. jedes Monats
- Einzelaktie max. 30 %, Krypto max. 25 %, Gold 10–20 %, Bargeld 5–15 %
- Verkauf bei mehr als 20 % Verlust ohne neue gute Nachricht
- Schließt Gold unter 3.900 USD: Goldposition halbieren. Gilt einmal pro Unterschreitung (vom Nutzer bestätigt am 31.10.2026). Erneut halbiert wird erst, wenn Gold zuvor wieder über 3.900 USD geschlossen hat und dann erneut darunter schließt.
  - Status: Halbierung am 31.10.2026 ausgeführt (Schluss 30.10.: 3.875,45 USD). Die Regel ist bis zu einem Schluss über 3.900 USD nicht mehr aktiv.
- Umschichten nur bei mehr als 5 Prozentpunkten Abweichung

**Depot B (Krypto)**, Start 17.10.2026 mit 10.000 EUR, +500 EUR am 17. jedes Monats
- BTC + ETH 40–60 %, einzelne Coin max. 35 %, Altcoins je max. 20 %
- LINK + AVAX zusammen max. 20 %, Bargeld 5–15 %
- Verkauf bei mehr als 30 % Verlust ohne neue gute Nachricht

## Aktueller Bestand Depot A (nach den Orders vom 31.10.2026)

| Position | Menge | Einstand | Kurs 31.10. | Wert EUR | Anteil | Ergebnis |
|---|---|---|---|---|---|---|
| Nvidia | 14,96 | 200,45 | 183,42 | 2.743,96 | 27,5 % | −8,5 % |
| Eli Lilly | 2,35 | 1.060,20 | 1.267,10 | 2.977,69 | 29,8 % | +19,5 % |
| Xetra-Gold | 6,225 g | 120,40 | 111,68 | 695,21 | 7,0 % | −7,2 % |
| Bitcoin | 0,0268 | 74.450 | 68.981 | 1.848,69 | 18,5 % | −7,3 % |
| Bargeld | | | | 1.710,77 | 17,1 % | |
| **Summe** | | | | **9.976,32** | | **−0,24 %** |

Eingezahlt: 10.000 EUR. Nächste Einzahlung: 13.11.2026.

## Aktueller Bestand Depot B (Stand 01.11.2026)

| Position | Menge | Einstand | Kurs 01.11. | Wert EUR | Anteil | Ergebnis |
|---|---|---|---|---|---|---|
| Bitcoin | 0,0413 | 72.530 | 69.756 | 2.880,92 | 30,5 % | −3,8 % |
| Ethereum | 1,017 | 2.163 | 2.026,84 | 2.061,30 | 21,8 % | −6,3 % |
| Solana | 16,09 | 93,20 | 84,46 | 1.358,96 | 14,4 % | −9,4 % |
| XRP | 858 | 1,165 | 1,12 | 960,96 | 10,2 % | −3,9 % |
| Chainlink | 64,2 | 10,90 | 10,22 | 656,12 | 6,9 % | −6,2 % |
| Avalanche | 67,5 | 8,88 | 7,78 | 525,15 | 5,6 % | −12,4 % |
| Bargeld | | | | 1.006,40 | 10,6 % | |
| **Summe** | | | | **9.449,81** | | **−5,50 %** |

Eingezahlt: 10.000 EUR. Nächste Einzahlung: 17.11.2026.

**Beide Depots zusammen: 19.426,13 EUR bei 20.000 EUR eingezahlt (−573,87 EUR, −2,87 %).** Depot A mit dem Stand vom 31.10. (9.976,32 EUR), am 01.11. nicht neu bewertet.

## Termine
- 13.11.2026: Einzahlung Depot A (+500 EUR)
- 17.11.2026: Einzahlung Depot B (+500 EUR)
- 18.11.2026: Nvidia-Quartalszahlen

## Offene Punkte
- Netzwerkfreigabe fehlt: Die Cloud-Umgebung blockiert api.coingecko.com, ls-tc.de u. a. (403 bzw. Namensauflösung fehlgeschlagen). Ohne Freigabe dieser Domains sind keine Kurse abrufbar. Läufe vom 02.11., 03.11. und 04.11. blieben deshalb ohne Bewertung. Zusätzlich blockiert: boerse.de (Namensauflösung fehlgeschlagen).
- Gold-Schlüsse vom 02.11., 03.11. und 04.11. (Regel 3.900 USD) nicht geprüft; Status der Halbierungsregel unverändert.
- Lilly liegt mit 29,8 % knapp unter der 30-%-Grenze. Bei weiterem Anstieg muss im nächsten Lauf die Grenze geprüft werden.

## Verlauf

### 28.10.2026: Anfangsstand (vom Nutzer vorgegeben)
Bestände wie vorgegeben übernommen. Kontrolle: Die Einstandswerte plus Bargeld ergeben bei beiden Depots genau 10.000,00 EUR.

### 31.10.2026: Lauf 1
**Kurse** (heute ist Samstag, kein Börsenhandel):
- Nvidia 183,42 EUR: Börse Stuttgart, 30.10. 21:56, nicht von heute. Die L&S-Seite war nicht erreichbar, Xetra-Schluss nicht gefunden.
- Eli Lilly 1.267,10 EUR: Lang & Schwarz, Stand 30.10. (geschlossen), nicht von heute
- Xetra-Gold 111,68 EUR/g: Börse Stuttgart, 30.10. 21:55, nicht von heute
- Gold-Schluss 30.10.: 3.875,45 USD/oz (L&S, 22:58, −3,6 %); gold.de 31.10. 09:58 unverändert 3.875,53 USD
- Krypto (CoinGecko, 31.10. 08:58 UTC, von heute): BTC 68.981, ETH 1.999,36, SOL 85,07, XRP 1,11, LINK 10,15, AVAX 7,53 EUR

**Nachrichten:**
- Eli Lilly (29.10.): Q3-Umsatz +39 % auf 24,4 Mrd. USD. Umsatzprognose 2026 auf 91–92 Mrd. USD angehoben, EPS-Prognose wegen IPR&D-Kosten leicht gesenkt. Aktie auf Rekordhoch.
- Nvidia (30.10.): −2,7 bis −4,4 %, unter die 100-Tage-Linie. Meldung über mögliche Kreditgarantien für ein Anthropic-Projekt. Keine neue negative Unternehmensnachricht.
- Gold (30.10.): −3,6 %, tiefster Stand seit fast einem Jahr, unter 3.900 USD
- Krypto: Markt weiter schwach, BTC unter 70.000 EUR

**Orders:**
- **Depot A: VERKAUF 6,225 g Xetra-Gold zu 111,68 EUR = 695,21 EUR.** Grund: Gold schloss am 30.10. bei 3.875,45 USD und damit unter 3.900 USD, also wird die Position halbiert. Gebucht zum letzten Kurs vom 30.10. (Wochenende). Realisierter Verlust: 6,225 × (111,68 − 120,40) = −54,28 EUR.
  - Danach liegt Gold bei 7,0 % (unter 10 %) und Bargeld bei 17,1 % (über 15 %). Beide Abweichungen sind kleiner als 5 Prozentpunkte, daher kein Rückkauf und kein Umschichten. Die Halbierungsregel geht hier der Bandregel vor.
- Depot A, sonst nichts: Kein Wert hat mehr als 20 % Verlust, Lilly mit 29,8 % unter 30 %, Krypto mit 18,5 % unter 25 %.
- Depot B: keine Order. BTC+ETH 52,1 % (Band 40–60), BTC 30,4 % (max. 35), größter Altcoin SOL 14,6 % (max. 20), LINK+AVAX 12,4 % (max. 20), Bargeld 10,7 %. Größter Verlust AVAX −15,2 % (Grenze −30 %).

**Einzahlungen:** keine fällig (nächste 13.11. und 17.11.)

**Korrekturen:** keine (erster Lauf)

### 01.11.2026: Lauf 2 (Sonntag, nur Depot B)
**Kurse:** CoinGecko-API, Stand 01.11.2026 20:55–20:56 UTC, von heute: BTC 69.756, ETH 2.026,84, SOL 84,46, XRP 1,12, LINK 10,22, AVAX 7,78 EUR (BTC 77.840 USD).

**Nachrichten:**
- Bitcoin schloss den Oktober mit etwa −7,3 % ab, das schwächste Oktoberergebnis seit mindestens 2016 (cryptoticker.io)
- US-Spot-Bitcoin-ETFs: Abfluss von 643 Mio. USD am 30.10. (cryptoticker.io; das Datum ist zwischen den Quellen nicht einheitlich)
- Fear & Greed Index 30, also „Angst“
- Meldung über einen Hack bei Binance (ca. 6,3 Mrd. USD, 29.10.) aus einer Quelle, die wenig verlässlich wirkt. Nicht bestätigt, daher nicht als Entscheidungsgrund verwendet.

**Orders:** keine. Prüfung der Regeln: BTC+ETH 52,3 % (Band 40–60), BTC 30,5 % (max. 35), größter Altcoin SOL 14,4 % (max. 20), LINK+AVAX 12,5 % (max. 20), Bargeld 10,6 % (Band 5–15). Größter Verlust AVAX −12,4 % (Grenze −30 %). Keine Regel verlangt eine Order.

**Einzahlungen:** keine fällig (nächste 17.11.)

**Korrekturen:** keine. Depot A wurde in diesem Lauf nicht geprüft, Bestand und Bewertung vom 31.10. bleiben stehen.

### 01.11.2026: Umzug in die Cloud
Die Datei wurde vom lokalen Rechner in das GitHub-Repository MatzeSKS/uebungsdepot übernommen. Bestände unverändert. Ab jetzt laufen die Aktualisierungen als Cloud-Aufgaben (werktags 22:30 beide Depots, sonntags 18:00 nur Depot B, Ortszeit Wien).

### 02.11.2026: Lauf 3 (Montag, Lauf ohne Kursdaten)
**Kurse:** Keine abrufbar. CoinGecko-API und ls-tc.de lieferten 403 (Proxy) bzw. Namensauflösung fehlgeschlagen. Die Websuche fand nur undatierte Bitcoin-Momentaufnahmen (ca. 55.000–57.000 EUR) ohne Datum und nicht mit den Vortageskursen (69.756 EUR) vereinbar. Sie wurden deshalb nicht verwendet.

**Orders:** keine. Ohne verlässliche Kurse und Nachrichten ist keine regelkonforme Entscheidung möglich. Bestände und Bewertungen vom 31.10. (Depot A) und 01.11. (Depot B) bleiben unverändert stehen.

**Einzahlungen:** keine fällig (nächste 13.11. und 17.11.)

**Korrekturen:** keine


### 03.11.2026: Lauf 4 (Dienstag, Lauf ohne Kursdaten)
**Kurse:** Keine abrufbar. api.coingecko.com und www.ls-tc.de: Proxy lehnt die Verbindung ab (403), www.boerse.de: Namensauflösung fehlgeschlagen. Die Websuche lieferte nur eine undatierte/modellierte Bitcoin-Angabe (ca. 71.750 EUR, Stand 01.11., sowie eine reine Prognose für den 03.11.) und widersprüchliche ältere Werte. Keine davon wurde verwendet. Keine Aktien-, Gold- oder Nachrichtendaten von heute gefunden.

**Orders:** keine. Ohne verlässliche Kurse ist keine regelkonforme Entscheidung möglich. Bestände und Bewertungen vom 31.10. (Depot A) und 01.11. (Depot B) bleiben stehen.

**Einzahlungen:** keine fällig (nächste 13.11. und 17.11.)

**Korrekturen:** keine

### 04.11.2026: Lauf 5 (Mittwoch, Lauf ohne Kursdaten)
**Kurse:** Keine abrufbar. api.coingecko.com und www.ls-tc.de: Proxy lehnt die Verbindung ab (403). Die Websuche lieferte für BTC nur Werte vom 25.10.2026 (71.632 EUR) und undatierte Angaben (ca. 55.500 EUR), für Gold nur Daten aus dem Frühjahr 2026. Nichts davon wurde verwendet. Keine Aktien- und Nachrichtendaten von heute gefunden.

**Orders:** keine. Ohne verlässliche Kurse ist keine regelkonforme Entscheidung möglich. Bestände und Bewertungen vom 31.10. (Depot A) und 01.11. (Depot B) bleiben stehen.

**Einzahlungen:** keine fällig (nächste 13.11. und 17.11.)

**Korrekturen:** keine
