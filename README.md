```php
<?php

namespace AryaLavassani;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'TookanTech',
                'position' => 'Back-end Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            GraphQl::class,
            Mysql::class,
            Elasticsearch::class
            Javascript::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source and make world a better place';
    }
}
```
