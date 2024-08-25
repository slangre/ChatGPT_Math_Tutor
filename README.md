# ChatGPT_Math_Tutor
Datenerhebung zu Antworten von ChatGPT 3.5, 4.0 und 4.0 mit Wolfram auf mathematische Fragen, ergänzt durch Umfrageergebnisse von Studierenden und Nachhilfenehmenden.

**Über dieses Repository**
Dieses Repository enthält die im Rahmen einer Forschungsarbeit zur Analyse der Antwortenqualität verschiedener ChatGPT-Versionen auf mathematische Fragen gesammelten Datensätze. Die Datensammlung beinhaltet Antworten von *ChatGPT 3.5, ChatGPT 4.0* und *ChatGPT 4.0* mit der Integration von *Wolfram Alpha*. Die zu beantwortenden mathematischen Fragen entstammen fünf unterschiedlichen Themengebieten *Gleichungen, Integralrechnung, Stochastik, analytische Geometrie und Logikrätsel* jedes dieser Themengebiete beinhaltet fünf verschiedene Fragen, die an jede der untersuchten KIs dreimal wiederholt gestellt wurde.

**Datensatz: ChatGPT Antworten**
Der Datensatz besteht aus 225 von den oben genannt ChatGPT-Versionen generierte Antworten in Form von Screenshots der Chatverläufe als .png Dateien. Zur Verbesserung der Bildqualität wurden die Chatverläufe nachträglich erneut in verbesserter Qualität aufgenommen. Dabei wurden längere Chatverläufe auf mehrere Bilder aufgeteilt, wobei die Reihenfolge im Namen der Datei kenntlich gemacht wurde. Bei dem erneuten Aufrufen der archivierten Chats sind im Vergleich zu den Ursprünglichen für die Datenauswertung verwendeten Chats fielen folgende Veränderungen auf:
1. Die in der Antwort integrierten Grafiken, wie Funktionsgrafen, etc. wurden meist nicht mehr angezeigt. In diesen Fällen wurde entweder über den in der Aufgaben hinterlegten Link die Grafik über Wolfram|Alpha erneut abgerufen und als separate Bilddatei beigelegt. Oder für den Fall, dass kein Link angegeben wurde, die Bilddatei aus den ursprünglichen Datensätzen entnommen.
2. In seltenen Fällen fehlten nach dem erneuten Aufrufen der Chats Satzteile/ Teile der Erklärung. Dies trat auch mitten in den Erklärungen in Satzmitte auf. Auch in diesem Fall wurde der betroffene Teil aus den alten Datensätzen entnommen und separat den Antworten beigefügt.
3. Mehrheitlich ist die Formatierung der Rechnungen anders als in der ursprünglichen Anzeige. So wurden Rechnungen, welche früher untereinander aufgeführt wurden, nach dem erneuten Aufrufen nebeneinander angezeigt.
   Bsp.:
   
| vorher   | nachher                 |
|----------|-------------------------|
| 2x + 2 = 6 | 2x + 2 = 6   2x = 4    |
| 2x = 4    | ...                     |

Zusätzlich liegt für jede mathematische Aufgabe die bei der Auswertung verwendete Musterlösung mit einem exemplarischen Rechenweg bei. Dieser Rechenweg ist in der Form exemplarisch, dass der aufgeführte Rechenweg nicht die einzige Möglichkeit zur Lösung dieser Aufgabe darstellt und somit selbstverständlich auch andere Lösungswege akzeptiert wurden.

**Struktur des Repositories:**
*chatgpt_datensammlung/*: Enthält die strukturierte Sammlung der gestellten Fragen und ihrer generierten Antworten.
*umfrage/*: Enthält die Ergebnisse der Umfrage untergliedert in die beiden Gruppen, der Befragten.

**Lizenz**
Dieses Projekt steht unter der [MIT License](LICENSE).
