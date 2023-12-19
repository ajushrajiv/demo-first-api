# Mein erstes API

## Allgemeine Infrastruktur
![](./images/Infrastructure.png)

## API Dokumentation
`GET /allitems`: Gibt Alle Elemente der Shopping Liste zurück

`GET /itembyid/{itemdId}`: Gibt ein einzelnes Elemnt zurück.
**Parameter**: `itemId` - Einzigartige Id des Elements

Erstellen von einem neuen Element
`POST /dbname/item`

Löschen von einem Element

`DELETE /dbname`
`DELETE /dbname/{itemid}`

Aktualisieren von einem Element

`GET /dbname/{itemid}`
`POST /dbname/{dbid}`
