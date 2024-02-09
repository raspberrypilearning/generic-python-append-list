Les listes Python sont mutables. Cela signifie que des données peuvent y être ajoutées ou supprimées. Essayons ça !

- Commence par créer une liste vide.

```python
ma_liste = []
```

- En utilisant le mot clé `append`, tu peux ajouter toutes les données que tu veux à la liste.

```python
ma_liste.append('Une chaîne')
```
- Tu obtiendras ainsi une liste qui ressemblera à celle-ci :
```python
['Une chaîne']
```

- Les listes peuvent contenir des données de n'importe quel type :
```python
ma_liste.append(1)
ma_liste.append(['une autre', 'liste'])
ma_liste.append(('un', 'tuple'))
```

- Le résultat final de toutes ces opérations est :
```python
['Une chaîne', 1, ['une autre', 'liste'], ('un', 'tuple')]
```
