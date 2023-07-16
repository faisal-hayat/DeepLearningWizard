# Metrics

--- ---
## Metrics

- Torch tensors
- NNumpy to Tenosro and vice versa. 
- Element wise Addation vs. inplace addition
- Element wise multiplication vs. inplace multiplication
- Tensor Mean

```python
import torch

a = torch.Tensor([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])
print(a.size())

print(a.mean(dim=0))
print(a.mean(dim=1))


```

--- ---