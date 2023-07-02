**papers** [finance, modeling, philosophy, metaphysics]: [SSRN](https://papers.ssrn.com/sol3/cf_dev/AbsByAuth.cfm?per_id=4163481) </br>
**musings** [philosophy, metaphysics, literature]: [Blog](https://nelson-n.github.io/)
**open-source 3d printer design**: [Mark 1 Resin 3d Printer](https://nelson-n.github.io/Mark1.github.io/) </br>

</br>

```python
cache = {0: 0, 1: 1}

def fibonacci(n):
    if n in cache:
        return cache[n]
    cache[n] = fibonacci(n-1) + fibonacci(n-2)
    return cache[n]

fibonacci(1e3) / fibonacci(999)
```
