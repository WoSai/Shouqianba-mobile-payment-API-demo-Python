shouqianba
==========

### Installation:

`pip install https://github.com/WoSai/Shouqianba-mobile-payment-API-demo-Python`

or

`python setup.py install`

### Example:

```python
import shouqianba


shouqianba.config.vendor_key = ''
shouqianba.config.vendor_sn = ''

client = shouqianba.ShouqianbaClient()
client.activate("", True)
client.checkin()
client.precreate(1, "1")
```
