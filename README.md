Opauth-VKontakte
=============
Opauth strategy for VKontakte authentication.

Based on Opauth's Facebook Oauth2 Strategy

Getting started
----------------
0. Make sure your cake installation supports UTF8

1. Install Opauth-VKontakte:
   ```bash
   cd path_to_opauth/Strategy
   git clone git://github.com/dgrabla/opauth-vkontakte.git VKontact
   ```
2. Create VK application at http://vk.com/developers.php

3. Configure Opauth-VKontact strategy with `key` and `secret`.

4. Direct user to `http://path_to_opauth/vkontakte` to authenticate

Strategy configuration
----------------------

Required parameters:

```php
<?php
'VKontakte' => array(
	'key' => 'YOUR APP KEY',
	'secret' => 'YOUR APP SECRET'
)
```

License
---------
Opauth-VKontakte is MIT Licensed  
