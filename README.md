# Popup-more  < 2.2.0
Path traversal in the popup-more WordPress plugin.

### Description
Vulnerable file location: : /popup-more/classes/Ajax.php <br>
Link : https://en-gb.wordpress.org/plugins/stageshow/#description <br>
Version : - < **2.2.0** <br>
Paramter: formKey <br>
Status: unpatched <br>

### Code snippet: 

```php
require_once YPM_POPUP_CLASSES.'form/'.esc_attr($key).'Form.php';
```

### Proof of concept:
![lfi_poc (1)](https://github.com/0x9567b/popup-more/assets/72038577/eddd0850-0fb8-4672-893f-5fed5f540193)
