# relag.core

## Graph construction

```{eval-rst}
.. autoclass:: relag.core.EdgeStore
   :members:

.. autoclass:: relag.core.CsrGraph
   :members:
```

## HNSW approximate nearest neighbours

```{eval-rst}
.. autoclass:: relag.core.HNSWConfig
   :members:

.. autoclass:: relag.core.HNSWState
   :members:

.. autoclass:: relag.core.HNSWIndex
   :members:
```

## Graph algorithms

```{eval-rst}
.. autoclass:: relag.core.INWeightType
   :members:

.. autoclass:: relag.core.LeidenObjective
   :members:

.. autofunction:: relag.core.find_communities

.. autofunction:: relag.core.find_components

.. autofunction:: relag.core.partition
```

## Exact search

```{eval-rst}
.. autofunction:: relag.core.exact_edges

.. autofunction:: relag.core.exact_nearest_neighbors
```
