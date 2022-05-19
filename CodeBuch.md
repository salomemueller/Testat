## Inhalt

-   VfbEdgelist.csv (Edgelist)

-   VfbNodelist.csv (Nodelist)

-   Codebuch.md (Codierung der Datensätze)

## 

## Ursprung und Datenerhebung

Wir wurden beauftragt die Transfers zum VFB ür das jetzige Kader zu visualisieren. Hierzu hatten wir folgenden Link <https://www.transfermarkt.de/vfb-stuttgart/startseite/verein/79> und sollten damit Edge- und Nodelist erstellen.

# **Edgelist**

Die Edgelist erhält pro Spalte einen Wert.

**from:** gibt an, von welchem Verein der Spieler kommt oder Rückennummer

**to:** Rückennummer (ID) des Spielers oder Nationalität des Spielers

**weight:** Transfersumme in 100.000 Euro Schritten (auch gerundete Zahlen)

**season:** Das Zeitfenster des Transfers. Es wurde immer das erste Datum im Format JJJJ gewählt.

*zweite Form:*

**from:** Rückennummer des Spielers

**to:** Nationalität des Spielers

# **Nodelist**

**id:** Rückennummer, Vereinsname des abgenenden Vereins oder Nationalitäten, die in der Edgelist auftauchen

**name:** Spielername oder Vereinsname

**country:** Nationalität des Spielers oder Land des Vereins

**type:** 1 bedeuted Spieler/Person und 2 Verein
