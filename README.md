# Codeigniter-3-Debug-Helper
This is simple debug helper to print data in preformatted (pre) tag

##  How to use this helper
- Place this helper in application/helpers folder
- Load this helper in your controller
```php
$this->load->helper('cal_debug')
```
- Use of this helper
```php
$data=array('1','3','5');
_t($data)
```
