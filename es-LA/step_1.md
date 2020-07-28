Las listas de Python son mutables. Esto significa que los datos pueden ser añadidos o eliminados de ellas. ¡Probemos esto!

- Comienza creando una lista vacía.

```python
mi_lista = []
```

- Al usar la palabra clave `append`, puedes agregar cualquier dato que desees a la lista.

```python
mi_lista.append('Una cadena')
```
- Esto producirá una lista que se verá así:
```python
['Una cadena']
```

- Las listas pueden contener datos de cualquier tipo:
```python
mi_lista.append(1)
mi_lista.append(['otra', 'lista'])
mi_lista.append(('una', 'tupla'))
```

- El resultado final de todas estas operaciones sería:
```python
['Una cadena', 1, ['otra', 'lista'], ('una', 'tupla')]
```
