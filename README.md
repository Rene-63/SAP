# SAP

Deze scripts, alleen bruikbaar voor het team dat in de filename staat vermeld, maken het mogelijk om meldingen te delen waarbij in de chat wordt vermeld vanaf welke tijd de melding gesloten mag worden, wat het sluitvoertuig is en hoeveel credits de melding gemiddeld opbrengt

De volgende waarden kunnen aangepast worden. Let wel, bij een update zal dit opnieuw moeten gebeuren. Wilt u handmatig updaten, verwijder dan regel 9 (// @updateURL    https://github.com/Rene-63/SAP/blob/main/SAP_ALARMCENTRALE)

Minimum credits om te delen in het team, regel 99 (const alliance_credits = 5000;) en dan 5000 veranderen in de gewenste waarde
Minimum aantal uren dat de melding open moet staan, regel 101 (    const minOpenTime = 3;) en dan 3 veranderen in het gewenste aantal uren
Veranderen van de sneltoets om te gebruiken ipv de button, regel 237 (       const shortcutKeys = 126;) en verander de asci waarde in de waarde voor de gewenste sneltoets.

Er is bewust gekozen voor de sneltoets "~" omdat dit één van de minst gebruikte toetsen is. Gebruik van de letters a t/m z resulteert in het niet kunnen typen van die letter in een tekstvak.

Er kunnen nog meer waarden aangepast worden door iemand die er verstand van heeft, zoals de afsluittijd. In dit script wordt een na 22:00 uur gedeelde melding een afsluittijd vermeld van 10:00 uur ipv 3 uur later.
