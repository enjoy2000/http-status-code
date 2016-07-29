# http-status-code
List constant of http status codes

## Getting Started
```bash
php composer.phar install enjoy/http-status-code
```

## Example
```php
<?php
use Entoy/HttpStatusCode/StatusCodes;

class ExampleController extends BaseController
{
    public function indexAction()
    {
        $this->renderError("Bad request", StatusCodes::HTTP_BAD_REQUEST);
    }
}
```
