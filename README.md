# ChatGPT Detector
## Usage
Translate language

```php
<?php

use OpenAiApi\Api;

$app = new Api(...);
$app->setPrompt("Translate this into 1.English, 2.French: Hallo");
$app->get();

echo $app->getResponseText();
```
