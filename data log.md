# data log for proj 4

## `training.json` and `development.json` 

```python
whole_file = {'data': [item_0, item_1, ..., item_N]}
```

```python
item_i = {
  'title': str,
  'paragraphs': [p_0, p_1, ..., p_M],
}
```

```python
p_j = {
  'context': str,
  'qas': [q_0, q_1, ..., q_K],
}
```

```python
q_k = {
  'question': str,
  'id': str,
  'answers': [a_0, a_1, ..., a_D],
  'is_impossible': bool,
}
```

```python
a_h = {
  'text': str,
  'answer_start': int,
}
```

## `test.json`

```python
whole_file = {'data': [item_0, item_1, ..., item_N]}
```

```python
item_i = {
  'title': str,
  'paragraphs': [p_0, p_1, ..., p_M],
}
```

```python
p_j = {
  'context': str,
  'qas': [q_0, q_1, ..., q_K],
}
```

```python
q_k = {
  'question': str,
  'id': str,
}
```

