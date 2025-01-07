```php
<?php

namespace AryaLavasani;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Student',
                'position' => 'Back-end Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Java::class,
            Spring::class,
            Javascript::class,
            GoLang::class,
            GraphQl::class,
            Mysql::class,
            Elasticsearch::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source and make world a better place';
    }
}
```
