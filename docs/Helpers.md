# Helpers

## Selector

### **Hint**

**Member function call applied on the selector will apply to item(s) returned.**

```python
select_all(conf.Proxies, False, name="a").delete(globally=True)

# is equivalent to

for i in select_all(conf.Proxies, False, name="a"):
    i.delete(globally=True)
```

::: SmartMixin.select

::: SmartMixin.select_all

## Container Helper

::: SmartMixin.extend_back

::: SmartMixin.extend_front

::: SmartMixin.append_back

::: SmartMixin.insert_front
