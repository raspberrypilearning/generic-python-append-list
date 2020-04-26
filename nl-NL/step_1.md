Python-lijsten zijn veranderbaar. Dit betekent dat gegevens kunnen worden toegevoegd of verwijderd. Laten we dit proberen!

- Begin met het maken van een lege lijst.

```python
mijn_lijst = []
```

- Met het trefwoord `append` kun je alle gewenste gegevens aan de lijst toevoegen.

```python
mijn_lijst.append('Een string')
```
- Dit levert een lijst op die er als volgt uitziet:
```python
['Een string']
```

- Lijsten kunnen gegevens van elk type bevatten:
```python
mijn_lijst.append(1)
mijn_lijst.append(['andere', 'lijst'])
mijn_lijst.append(('een', 'tuple'))
```

- Het eindresultaat van al deze operaties zou zijn:
```python
['Een string', 1, ['andere', 'lijst'], ('een', 'tuple')]
```
